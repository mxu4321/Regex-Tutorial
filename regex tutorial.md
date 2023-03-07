# Regex Tutorial 

This regex tutorial is a guide that shows how to use regular expressions (regex) to search for and manipulate text. Regular expressions are a powerful tool for pattern matching and string manipulation, used in many programming languages and text editors. A regex tutorial typically covers the syntax and basic concepts of regex, as well as examples of common use cases and tips for writing efficient and effective regular expressions.


## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors are used to match patterns at the beginning or end of a line, word, or string. For example, the "^" character matches the beginning of a line, while the "$" character matches the end of a line.
Sample code snippet: The following regex will match any string that starts with "Hello":
```
/^Hello/
```

### Quantifiers
Quantifiers specify how many times a pattern should be repeated. For example, the "*" quantifier matches zero or more occurrences of the preceding character, while the "+" quantifier matches one or more occurrences.
Sample code snippet: The following regex will match any string that contains one or more digits:
```
/\d+/
```

### OR Operator
The "|" character is used as the OR operator in regular expressions, allowing you to match one of several alternatives.
Sample code snippet: The following regex will match either "apple" or "orange":
```
/apple|orange/
```

### Character Classes
Character classes are used to match a range of characters, such as all lowercase letters or all digits.
Sample code snippet: The following regex will match any string that contains a vowel:
```
/[aeiou]/
```

### Flags
Flags are used to modify the behavior of a regular expression, such as making it case-insensitive or allowing it to match across multiple lines.
Sample code snippet: The following regex will match any string that contains the word "hello", regardless of case:
```
/hello/i
```

### Grouping and Capturing
Grouping and Capturing: Parentheses are used to group parts of a regular expression together and capture the matched text.
Sample code snippet: The following regex will match a valid email address and capture the username and domain:
```
/(\w+)@(\w+\.\w+)/
```

### Bracket Expressions
Bracket expressions allow you to match a range of characters, such as all uppercase letters or all punctuation marks.
Sample code snippet: The following regex will match any string that contains a digit or punctuation mark:
```
/[\d\p{P}]+/
```

### Greedy and Lazy Match
Greedy and Lazy Match: Greedy matching is the default behavior of regular expressions, where the pattern matches as much as possible. Lazy matching, on the other hand, matches as little as possible.
Sample code snippet: The following regex will match the shortest possible string that starts with "a" and ends with "z":
```
/a.*?z/
```

### Boundaries
Boundaries are used to match patterns at specific positions, such as the beginning or end of a word.
Sample code snippet: The following regex will match any word that starts with "hello":
```
/\bhello\w*/
```

### Back-references
Back-references allow you to match the same text that was previously matched by a capturing group.
Sample code snippet: The following regex will match any string that contains a repeated word:
```
/\b(\w+)\b.*\b\1\b/
```

### Look-ahead and Look-behind
Look-ahead and look-behind assertions allow you to match a pattern only if it is followed or preceded by another pattern.
Sample code snippet: The following regex will match any string that contains "hello" followed by "world":
```
/hello(?=.*world)/
```

## Author

My name is Mengxue Xu. I am currently attending a full stack development bootcamp while writing this regex tutorial. Here is my GitHub: [https://github.com/mxu4321](https://github.com/mxu4321)
