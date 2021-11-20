# Regex Tutorial

I have created this tutorial to help teach you how to read and write Regex(Regular Expression). You can include Regex in your code and search algorithms to find certain patterns of characters within a string. This is a great way to validate input data.

## Summary

A Regex is a sequence of characters that define a search pattern. These patterns are used by searching algorithms for find or find and replace operations on strings.

Example :  Regex for an email address :
`^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$`


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

The `|` is an alternation. It will match the former or latter expression. This quantifier can affect specific characters or a whole expression.  

### Character Classes

A charcter class will match one of several characters. The order does not affect it. A character set will match any single character in the set. Anything in the square brackets will be matched.

### Flags

Flags follow the closing forward slashof an expression and change how it is interpreted.

Here are some examples:
* `i` Ignore Case - This will make the expression case sensitive.
* `g` Global Search - This will store the index of the last match.
* `m` Multi-line - The will case the beginning and end anchore to match the start and end of a line instead of the whole string.
* `u` Unicode - This will allow extended unicode escapes in the form \x{FFFFF}.
* `y` Sticky - This will match from its last index position and ignores the global search flag.
* `s` Dotall - This will cause dot to match any charcter.


### Grouping and Capturing

Groups let a group of tokens to be combined to operate on them together.

`^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$`

Capturing group `(abc)` puts multiple tokens together for extracting a substring. Our example has 3 groups `([a-zA-Z0-9_\-\.]+)`, `([a-zA-Z0-9_\-\.]+)` and `([a-zA-Z]{2,5})`.


### Bracket Expressions

A bracket expression will match a specific set of single charcter. It match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.

### Greedy and Lazy Match

A greedy quantifier will match as many characters it can as it goes backwards through the string. This is the default.

A lazy quantifier will match as little characters as possible as it goes backwards through the string.

### Boundaries

A Boundary is  a position between `\w` and `\W` to define a word character.

### Back-references

The backreference `\` allows a previously matched subexpression to be identified subsequently in the same regular expression. 

### Look-ahead and Look-behind

`(?=check)` Positive Lookahead-This asserts what immediately follows the current position in the string is check

`(?<=check)` Positive Lookbehind-This asserts that what immediately precedes the current position in the string is check

`(?!check)` Negative Lookahead-This assers that what immediately follows the current position in the string is not check

`(?<!check)` Negative Lookbehind-This asserts that what immediately preceds the current position in the string is not check

## Author

Chris Bradford is a student in the Full Stack Web Development pregram at the University of Utah. 

Github: https://github.com/bradford583
