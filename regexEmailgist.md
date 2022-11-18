># Regex Tutorial - Matching an Email

This tutorial will show how regex matches email address format by using. 

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Regex does not only support script languages such as __JavaScript__ or __Python__. Regex 

support text files such as __Word__ for searching text as well.

>## Summary
````
Regex stands for Regular Expressions, which is powerful in searching and manipulating. 

On "find" and "find and replace" data through specific search patterns by using text strings.

Combine with different components to create a syntax that you can use to match an Email. 

Regex are useful because they provide more flexible and powerful pattern matching with wildcards.

````
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy Search](#greedy-search)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

>## Regex Components

>### Anchors

`^` : matches the starting of the sentence.

`$`: indicates the end of the sentence.

>### Quantifiers

`+` : which will connect user' email name `+` `.com`

`{2,6}` : which will match between 2-6 characters by using `{2,6}` and set between `[a-z.]`. 


>### OR Operator

>### Character Classes
`\d` : matches a single character which is a digit.

>### Flags

>### Grouping and Capturing
`[a-z0-9_.-]` : On the first group matches one of the characters from the English alphabet `a-z`, `0-9`, `_` , `.` , and `-` before the `@` symbol

`[\da-z\.-]` : The second group matches one of the characters from a single digit `\d`, English alphabet `a-z`, `.` and `-` 
 after the `@` symbol.

`[a-z\.]`: The last group matches lower case alphabet between a-z `[a-z\.]` for `.com`

>### Bracket Expressions

For validation included characters that need to use Bracket Expressions to set of `[a-z0-9_.-]`, which matches lowercase `a-z` , `0-9` , `_` , `.` ,and `_` .

`[\da-z\.-]`, which matches a single digit, lowercase alphabet `a-z`, `.` ,and `-` .

`[a-z\.]` matches the lowercase alphabet and `.` only.

>### Greedy Search

The quantifier `+` will give a return as many times as possible as needed.

That quantifier `{}` matches `times` which are integer numerics inside the scope, indicating from a specific time to a particular time

>### Boundaries

>### Back-references

>### Look-ahead and Look-behind

## Author

Penelope Leung

Email: <url> penelope.c.leung@gmail.com

Github Gist: <url> https://gist.github.com/penelope-leung/
