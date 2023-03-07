# Regex Introduction

This is an introduction into Regex that can help you understand it and how to apply it to any future code/projects you work on in the future.

## Summary

A Regex, also know as a regular expression is a sequence of characters that states a specific pattern through text. These patterns tend to be used by string-searching algorithms in "find" or "find and replace" operations on strings or input validation. There use is mostly with theoretical computer science and in formal language theory.

This page will look into the Regex string for a match URL tag. Below you can read more about this line of code and other interesting things regarding Regex.

Example:
> /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

Anchors let the program know where the start and end of the line of code is.

* `^`: This matches the starting position of the string. When in line-based work, it matches the starting point of a line.

* `$`: This matches the end of the string. When in line-based work, it matches the ending point of a line.

These are used near the start and end of the string: /`^`(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?`$`/

This lets the program know where this code will start and where it will end.

### Quantifiers

Quantifiers indicate that the previous character must be matched a certain number of times. There are different types of quantifiers that are better explained in [Greedy and Lazy Match](#greedy-and-lazy-match).

* `?`: Matches previous character between 0 and 1 times.
* 
*  `(*)`: Matches the previous character between 0 or more times.

*  `(+)`: Matches the previous character between 1 or more times.
*  
*  `{2,6}`: forces the input of characters to be between two and six characters long.

Here are some of the areas these are used in: /^(https`?`:\/\/)`?`([\da-z\.-]`+`)\.([a-z\.]`{2,6}`)([\/\w \.-]`*`)`*`\/?$/

These tell the program how many instances of the character or group must be present in the input.

### OR Operator

OR Operator acts as a boolean, it will need to match the character it is attached to.

* `|`: Acts as a boolean that matches characters before or after where it is input.

### Character Classes

Character Classes match characters from a specified set, whether these are already existing sets or sets you define yourself.

* `[ABC]`: Character in the brackets will match any character in the set.

* `[^ABC]`: Adding a caret will match any chracter not in the set.

* `[A-Z]`: Adding a dash between characters will select a range.

* `\w`: Matches any word character.

* `\d`: Matches any digit character.

Here are some of the areas these are used in: /^(https?:\/\/)?(`[\da-z\.-]`+)\.(`[a-z\.]`{2,6})(`[\/\w \.-]`*)*\/?$/

This is one of the primarily used parts of Regex and will likely be seen in any code using it.

### Flags

Flags can change how an expression is read.

### Grouping and Capturing

Capturing groups multiple characters together in use for extracting a substring or for referencing.

### Bracket Expressions

Bracket Expressions use square brackets to make regular expressions to match a single character or element that is assigned.

Examples of these can be found in [Character Classes](#character-classes).

### Greedy and Lazy Match

* "Greedy" quantifiers will match the longest possible string, it will have the program try to match as many of its quantified characters as possible.

* "Lazy" quantifiers will match the shortest possible string, it will have the program try to match as little of its quantified characters as possible.

### Boundaries

### Back-references

## Author

Ethan Alexander: OSU Web Development Student

Github: https://github.com/ALiteralWaffle
