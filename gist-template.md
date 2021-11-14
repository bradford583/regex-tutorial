# Regex Tutorial

I have created this tutorial to help teach you how to read and write Regex(Regular Expression). You can include Regex in your code and search algorithms to find certain patterns of characters within a string. This is a great way to validate input data.

## Summary

A Regex is a sequence of characters that define a search pattern. These patterns are used by searching algorithms for find or find and replace operations on strings.

Example :  Regex for an email address :
```
^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$
```


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

* `^exampletext$`
    * The caret `^`  markes the start of the Regex.
    * The dollar sign `$`  markes the end of the Regex.

### Quantifiers

A quantifier is a repition operator. They let the system know to match the preceding code a certain number of times.

The `+` will match one or more of the preceding token. In the case it will attempt to match `[a-zA-Z0-9_\-\.]`


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

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
