# Title (replace with your title)

Regular expressions are powerful tools for pattern matching and text processing. In this tutorial, we will explore various components of regular expressions and understand how to use them effectively.

## Summary

In this tutorial,  we will break down the compenents of comprehensive regular expression, including anchors, quantifiers, OR operator, character classes, flags, grouping and capturing, bracket expressions, greedy and lazy match, boundaries, back-references, and look-ahead and look-behind.

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
Anchors are used to assert positions in the text. Here are examples of some common anchors and how they look in Regex:

^: Asserts the start of a line.
$: Asserts the end of a line.

Example in regex notation:

`/^start/`

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

Example in Regex notation:
`/\d+/g`

The above expression means:  "123", "4567", etc.

### OR Operator
The OR operator allows for matching one of several possible options.

An example in Regex notation:
`/apple|orange/`

The above code matches "apple" or "orange"

### Character Classes
Character classes allow you to match any one of a set of characters.

Example in Regex notation:
`/[aeiou]/`

The above matches any vowel character

### Flags
Flags are optional parameters that can be added to a regex pattern to modify its behavior. Common flags include:

i: Case-insensitive matching
g: Global matching
m: Multiline matching

An example of this in Regex notation:
`/regexpattern/gi`

The above example code matches "regexpattern", case-insensitive and globally

### Grouping and Capturing
Grouping allows you to treat multiple characters as a single unit. Capturing allows you to store the result of the match for later use.

Example in Regex notation:
`/(ab)+/`

The above code matahces "ab", "abab", "ababab" etc.

### Bracket Expressions
Bracket expressions are used to specify a set of characters.

Example in Regex notation:
`/[0-9]/`

The above matches any digit character (0-9)

### Greedy and Lazy Match
Greedy matching matches as much as possible, while lazy matching matches as little as possible.

Example in RegEx notation:
`/<.*?>/`

The above code considers an HTML context and matches any of "<html>", "<head>", etc. 

### Boundaries
Boundaries define the edge of a word or line.

Example in Regex notation:
`/\bword\b/`

The above code matches "word" but not "words" or "keywords"

### Back-references
Back-references allow you to refer back to captured groups within the regex pattern.

Example in Regex notation:
`/(abc)\1/`

The above code matches "abcabc"

### Look-ahead and Look-behind
Look-ahead and look-behind assertions assert that a pattern is or is not followed by or preceded by another pattern.

Example in Regex notation:
`/\d+(?= dollars)/`

The above code matches "123" within "123 dollars" (ie targets the interger amount)

## Author
This tutorial has been written by Brendan McGinty, and their contact details are included below. Brendan is a current full-time software development student through UC Berkeley, and has put together this tutorial both to help others who are learning as well as to solifidy the knowledge for himself.

email: brendan.mcginty14@gmail.com
Github: https://github.com/mcgintyb14

