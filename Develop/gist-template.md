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

`^` This matches the starting position of the string. When in line-based work, it matches the starting point of a line.

`$` This matches the end of the string. When in line-based work, it matches the ending point of a line.

These are used near the start and end of the string: /`^`(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?`$`/

This lets the program know where this code will start and where it will end.

### Quantifiers


### OR Operator


### Character Classes


### Flags


### Grouping and Capturing


### Bracket Expressions


### Greedy and Lazy Match


### Boundaries


### Back-references


### Look-ahead and Look-behind


## Author

Ethan Alexander: OSU Web Development Student
Github: https://github.com/ALiteralWaffle
