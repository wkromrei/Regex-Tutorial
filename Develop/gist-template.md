# Title (replace with your title)

Regex's, or regular expressions, are sequential expressions that use literal characters, metacharacters, character classes, quantifiers, and finally groups and alternation to make specific searches or find specific matches, or even carry out managing a text in a specific way. 


## Summary

Today I will be breaking down the matching a hex value regex: 

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/. 

 Hexadecimal codes are codes that represent colors, and this regex matches and validates those codes. The ^ asserts the start of the string. The '#?' means that the color code may or may not start with a hashtag. '([a-f0-9]{6}' means the number must match exactly six characters which can be any digit or letter(a-f). The | means or. The second half of the regex means that this search can apply to a 3 digit code as well, and the first half means that it can apply to a six digit hex code. The dollar sign at the end states that the regex has ended. 

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
The ^ and $ symbols are both considered to be anchors. 

### Quantifiers
Quantifiers set the limits of the string the regex matches. Frequently they include the minimum and maximum number of characters that the regex searches for.

### OR Operator
The OR operator is called by using the bar |. 

### Character Classes
A regex character class defines a character set, which can occur in an input string in order to fulfill a match. 

### Flags
Flags do not have to be wrapped in / characters. They are placed at the end of a regex, and they define addtionality functionality, or regex limits. There are 6 optional flags. 

### Grouping and Capturing
Regex Grouping is done by using parenthesis (). Grouping can be done by either capturing or non-capturing. 

### Bracket Expressions
Bracket expressions take place within square brackets [], and what is within signifies a range of characters that we want to match.

### Greedy and Lazy Match
Quantifiers can either be Greedy or Lazy. When they are Greedy, it means they match as many occurences of particualr patters as possible. They are Lazy when a ? is added to a quantifier, which means it will match as few occurences as possible. 

### Boundaries
Regex boundaries are a type of special anchor.

### Back-references
Regex back-references allow us to reuse part of the regex inside the pattern. 

### Look-ahead and Look-behind
Look-aheads, and look-behinds, which are referred to as lookarounds, allow us to match a pattern only if it is, or isn't, preceded or followed by another pattern. 

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
