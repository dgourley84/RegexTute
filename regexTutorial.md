# Regex Tutorial

This Regex (Regular Expression) tutorial is created to help you understand and define the sequence of special characters to verify a search term. A Regex is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also used frequently to validate input data.

## Summary

Today I will be covering and breaking down the components of a regular expression used to match Hex Values. Hex values are commonly used for color using the hexadecimal color code format. In the web we can use hex triplet (hex color code) to represent colors on a web page. For the hex color code, there are two formats, a standard hex triplet and a shorthand hex format, where both formats start with a #./^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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
In regular expressions, we use anchors to check if the matching symbol is the starting symbol or ending symbol of the input string. Anchors are of two types: The first type is the caret ^ that checks if the matching character is the first character of the input and the second type is the dollar sign $ which checks if a matching character is the last character of the input string.

In the example above, the string should start with ```<``` to signify the opening of an HTML tag, ```^<```.

The end of the example above is checked using the ```$,``` and checks that the preceding character is correct, ```>$```


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

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
