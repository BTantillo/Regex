# Regex Tutorial: Match URL with Regular Expressions

URL Regex: A regular or rational expression defined as characters in a pattern or a sequence that replace or find string operations which may be useful locating a string in a URL.

## Summary

A Regex proves useful in matching a URL in order to locate special text patterns. 
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

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
Anchors are used at the beginning and end of searches to check if a string fully matches a pattern, although they themselves do not match characters. They strictly affirm a string matches a location. Anchors will create parameters.
* Use the ^ anchor to match the beginning of the text. 
* Use the $ anchor to match the end of the text.

### Quantifiers
Quantifiers will measure and set the limit on the the number of characters that we are wanting to match in our Regex: + searches the pattern one or more times, ? searches the pattern zero or one time, * searches the pattern zero or more times.
Curly braces provide:
* { x } searches the pattern x number of times
* { x, } searches the pattern a minimum of x times
* { x, y } searches the pattern a minimum of x and maximum of y
This expression : (https?:\/\/)?
is looking http or https


### OR Operator
The purpose of an OR operator is to match the characters on the left or right of the operator, essentially serving as an or, as in and/or. 

### Character Classes
A character class is  the set of characters that could occur in a string. The URL 
The \d character class is looking for any digits, a \D looks for non-digits, \s searches for space symbols, tab and newlines, \S looks for all but \s, \. any characters with the regex 's' flag, while the \w character is looking for an alphanumeric character. 

### Flags
Flags are used at the end of a regex, after a clsoing slash. They are tokens that will modify parameters of a search. Multiple flags can be set by writing one after another with NO spaces. Flags must be written in lowercase. This URL does not contain any flags. 
Flag Expressions:
* i: Ignores casing. Makes expression case-sensitive
* g: Global. Makes expression search for all occurences
* s: Dot All. Makes the wild characters . match newlines as well
* m: Multiline. Makes boudnary characters ^ and $ match beginning and end of every line.
* y: Sticky. Indicates that it matches only from the index indicated by the lastIndex property of this regular expression in the target string (and does not attempt to match from any later indexes)
* u: Unicode. Expression assumes individual characters are code points, not code units and will then match 32 bit characters.

### Grouping and Capturing
Capturing Group is a part of a pattern that can be enclosed in a parentheses and is a way to treat multiple characters as one unit. 

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

- Miranda Thompson is a University of Oregon: Bootcamp Student aspiring to be a web developer. Currently resides on Oregon Coast. 
[MirandaT77 Github](https://github.com/MirandaT77)  
[LinkedIn]
:e-mail:[Email me](mailto:ranileah7@gmail.com)
