# All-About-Regex

Regular Expressions or Regex for short, can be used for many different cases when writing code. Regex is parameters for strings in an application. Regex can be used in many cases but the most useful one is search parameters. You can set parameters on what to search for so if I'm looking for 'abc' on a page, I will use
`/abc/`
The code will search for anytime the letters abc show up together.
If you wished to perform a search on how many times the word 'to' shows up on a page, you use `/to/` in your search.
Lets say that you don't want to look for anything specifically. you just want to set a certain structure of characters to search for. With regex, you can.

## Summary

```
    ^(\(?(?<area>[\d]{3})\)?[ -][\d]{2}[ -][\d]{4})$
```

The regex above looks like someone ran their hand across the keys but this expression is actually a social security number check. It checks for (xxx)-xx-xxxx , xxx-xx-xxxx , xxx xx xxxx. These are all ways someone may write their social and this checks for all of the ways.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors Used

^ -This anchor is checking for a match at the beginning of a string.<br>
$ -This anchor is checking for a match at the end of the string.

### Quantifiers Used

\* -This quantifier is used to match a previous element zero or more times.<br>
\? - this is quantifier is used to say that the element before the question mark is ok but its also okay to not have that element.<br>

### Grouping Constructs

() -Anything inside the parentheses is a subexpression. It works like parentheses in order of operations. It will check them independently.<br>
(?<area>) -This is setting a name of the subexpression so when it is logged, it will be titled area.

### Character Classes

[ -] This is used in my regex expression above and is checking for a space or a dash in between a group of numbers. both are allowed and read as a social security number.

### Character Escapes

If you want to use a character that is a specified regex character, you have to use a backslash and then you can put the character you want. This is called escaping.

## Author

My name is Fisher Davis and i'm studying to be a junior developer. I was first introduced to coding in highschool
where I had to program a robotic arm to run a specific set of tasks. I knew I had a love for coding and wanted to do it ever since.<br>
My Github: https://github.com/Fisher-Davis
