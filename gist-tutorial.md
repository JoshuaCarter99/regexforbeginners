# REGEX FOR BEGINNERS 

## Summary

Hello, and welcome to my regex tutorial! I will be talking to you about the list of subjects (pertaining to Regex) shown in the Table of Contents.

Regex is short for "regular expression", and is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. Let's take an in depth look at all the different types of regular expression! 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors have special meaning in regular expressions. They do not match any character. Instead, they match a position before or after characters "^" and "$". The code must start with ^([a-z0-9_\.-]+) and end with .([a-z\.]{2,6})$.To pass the match test the given anchor component must start and end with the above mentioned paremeters without any errors.

### Quantifiers
Quantifiers indicate numbers of characters or expressions to match. More specifically, the quantifier is used to determine how many times a perticular character or group of characters reoccurs or needs to be present to pass the match test.

*: 0 or More
+: 1 or More
?: 0 or One
{n}: Exact Number
{n,m}: Min and Max range of numbers

### Grouping Constructs
Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string.

Constructs are grouped by being enclosed withing parenthesis ()

### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" ) is an expression that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.

When it comes to password strength validation, bracket expressions include [a-z]/[A-Z] which match any character from lowercase and uppercase a through z. The bracket expression [!@#\$%\^&\*] will match any of the special characters within that set as well!

### Character Classes
A character class in a regex defines a set of characters, any one of which can occur in an input string to fulfill a match. Character classes also distinguish the kinds of characters such as, for example, distinguishing between letters and digits. 

### The OR Operator
A | or vertical line that shows the alternation between either side of the operator.

The OR operator is more technically referred to as the alternation or union operator.

### Flags
A flag is an optional parameter to a regular expression that modifies its behavior of searching. A flag changes the default searching behavior of a regular expression. It makes a regex search in a different way. A flag is denoted using a single lowercase alphabetic character. In JavaScript regex, we have a total of 6 flags, each serving a different purpose.

i(ignore casing), 
g(global), 
s(dot all), 
m(multiline), 
y(sticky), 
u(unicode)

### Character Escapes
These are characters that have a specified function but when you want to use them as strings you preface it with a backslash \.

The backslash in a regex escapes a character that otherwise would be interpreted literally. For example, the open curly brace { is used to begin a quantifier, but adding a backslash before the open curly brace means that the regex should look for the open curly brace character instead of beginning to define a quantifier.

## Author

You can find the rest of my repoistories at: https://github.com/JoshuaCarter99

Thank you for reading!!!
