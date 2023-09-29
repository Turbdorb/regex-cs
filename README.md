# Regex CS

I'll be going over Regex Components for Computer Science. This will be a helpful exercise for me to better understand regex.

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

Regex anchor components include ^ (Caret) to match patterns at the start of a line or string, $ (Dollar Sign) to match patterns at the end, \b (Word Boundary) to identify word boundaries, and \B (Not Word Boundary) to find positions within text where two word characters or non-word characters appear consecutively. These anchors are crucial for precisely specifying where patterns should be located within a text, enabling accurate pattern matching and extraction.

### Quantifiers

Quantifiers in regex components are special symbols that specify how many times a character or group of characters should be repeated in a pattern. They allow you to define the exact quantity or a range of occurrences for a particular element in a regular expression. Common quantifiers include * (matches zero or more), + (matches one or more), ? (matches zero or one), {n} (matches exactly n times), {n,} (matches n or more times), and {n,m} (matches between n and m times). These quantifiers are essential for specifying the flexibility and precision of your pattern matches in regular expressions.

### OR Operator

The OR operator in regex components is represented by the vertical bar | and allows you to specify multiple alternative patterns. It functions like a logical OR, enabling you to match any one of the provided patterns. For example, pattern1|pattern2 will match either "pattern1" or "pattern2" in the input text. The OR operator is useful when you want to find occurrences of different patterns within the same regular expression, providing flexibility in pattern matching.

### Character Classes

Character classes in regex, represented by [ ], let you match a single character from a defined set. For example, [aeiou] matches any vowel, and [0-9] matches any digit. You can use shortcuts like \d for digits and \w for word characters. Adding a caret ^ at the start, like [^0-9], matches any character not in the defined set. These classes help you match specific character patterns in regular expressions.

### Flags

Flags in regex components are optional modifiers that you can append to a regular expression to change how it behaves during matching. Common flags include "i" for case-insensitive matching, "g" to find all matches in a string rather than just the first one, and "m" for multiline matching where "^" and "$" anchor characters work on each line. Flags provide flexibility and control in adapting regular expressions to different matching scenarios.

### Grouping and Capturing

Grouping in regex involves using parentheses `( )` to create subpatterns within a larger expression, allowing you to apply quantifiers and modifiers to specific portions of the pattern. Capturing groups, denoted by parentheses, not only group elements but also capture and remember the matched text for potential reuse through numbered backreferences. Non-capturing groups are created by adding `?:` at the beginning of a group and are used for grouping without capturing, which can be helpful for optimization or when you don't need to store the matched content. Grouping and capturing are essential for creating complex regex patterns and extracting specific information from text.

### Greedy and Lazy Match

In regular expressions (regex), the terms "greedy" and "lazy" refer to quantifiers that dictate how much text is matched. "Greedy" quantifiers, such as `*` and `+`, try to match as much text as possible, extending the match to the longest substring that fits the pattern. On the other hand, "lazy" quantifiers, represented by `*?` and `+?`, seek to match as little text as necessary, stopping as soon as the pattern is satisfied. This distinction in quantifiers is important for controlling the extent of text matched in regex patterns, offering flexibility in matching behavior.

## Author

Jared Brymer, student at UT bootcamp.

Github: https://github.com/Turbdorb
