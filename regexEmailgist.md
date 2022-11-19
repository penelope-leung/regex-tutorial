># Regex Tutorial - Matching an Email

This tutorial will show how regex matches the email address format by using. 

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Regex does not only support script languages such as __JavaScript__ or __Python__. Regex 

also supports text files such as __Word__ for searching text as well.

>## Summary
````
Regex stands for Regular Expressions, which is powerful for searching and manipulating. 

User for the "find" and "find and replace" data through specific search patterns by using text strings.

Combine with different components to create a syntax that you can use to match an Email. 

Regex is useful because its provide more flexible and powerful pattern matching with wildcards.

````
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers or Operator](#quantifiers-or-operator)
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

`^` Are used to match the beginning of a sentence and `$` to indicate the end of a sentence.


>### Quantifiers or Operator

`+` Are used to connect the user email names and email service with `.com`

`{2,6}` Are used for matching between 2-6 characters by using `{2,6}` and set between `[a-z.]`. 


>### Character Classes

`\d` Are used to match a single character; which is a digit.

>### Flags

`i`, `g`, `s`, `m`, `y`,and `u` are flags, for matching Email Regex doesn't need to use all of them.

>### Grouping and Capturing

`[a-z0-9_.-]` The first group matches one of the characters from the English alphabet `a-z`, `0-9`, `_` , `.` , and `-` before the `@` symbol

`[\da-z\.-]` The second group matches one of the characters from a single digit `\d`, English alphabet `a-z`, `.` and `-` 

 after the `@` symbol.

`[a-z\.]` The last group matches the lower case letters between a-z `[a-z\.]` for `.com`

>### Bracket Expressions

The email validation will include bracked expressions which will have character sets of `[a-z0-9_.-]` which will match all the letters between  `a-z` , 

`0-9` , `_` , `.` ,and `_`  is case sensitive. `[\da-z\.-]` Will match a single digit and lowercase alphabet `a-z`, `.` ,as well as `-` . 

`[a-z\.]` Will match the lowercase alphabet and `.` only.

>### Greedy Search

The quantifier `+` will give a return for as many times possible as needed.

The quantifier `{}` matches `times` which are integer numerics inside the scope, indicating from a specific time to a particular time

>### Boundaries

`\b` is used to search for some words that have a specific character at the first one or last one in the article.

>### Back-references

Backreferences match the same text by a capturing group. 

When you want to match a pair of opening and closing such as HTML tags, and the text in between. So, when doing a match on the Email address is not 

possible to use this.

>### Look-ahead and Look-behind

`?=` or `?!` are similar to Back-references, most of the time they are used to match with a specific word/s in the articles.

## Author

Penelope Leung

Email: <url> penelope.c.leung@gmail.com

Github Gist: <url> https://gist.github.com/penelope-leung/
