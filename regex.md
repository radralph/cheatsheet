##REGULAR EXPRESSION

###Anchors
```
^  - Start of line
\A - Start of string
$  - End of line
\Z - End of string
\b - Word boundary
\B - Not word boundary
\< - Start of word
\> - End of word
```

###Character Classes
```
\c - Control character
\s - White space
\S - Not white space
\d - Digit
\D - Not digit
\w - Word
\W - Not word
\x - Hexadecimal digit
\O - Octal Digit
```

###Quantifiers
```
*  - 0 or more {3} Exactly 3
+  - 1 or more {3,} 3 or more
?  - 0 or 1 {3,5} 3,4 or 5
```

###Escape Sequences
```
\  - Escape following characters
\Q - Begin literal sequence
\E - End literal sequence
```

###Groups and Ranges
```
.  -  Any character except new line
(a|b) - a or b
(...) - group
(?...) - Passive (non-csapturing)
[abc]  - Range (a, b or c)
[A-Q]  - Upper case letter from A to Q
[0-7]  - Digit from 0 to 7
\x  - Group/subpattern number 'x'
```

###Pattern Modifiers
```
g  - Global match
i* - Case-insensitive
m* - Multiple lines
s* - Treat string as single line
x* - Allow comments and whitespace pattern
e* - Evaluate replacement
U* - Ungreedy pattern
```

