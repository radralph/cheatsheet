##vim 

### Cursor Movement / Navigation

```
h  -  move cursor left
j  -  move cursor down
k  -  move cursor right
w  -  skips to the start of the word
W  -  skips to the start of the word with punctuations
e  -  skips to the end of the word
E  -  skips to the end of the word with punctuations
b  -  skip back to the start of the word
B  -  skip back to the start of the word with punctuations
0  -  skip to the start of the line
^  -  skip to the first non-block character of the line
$  -  skip to the end of the line
gg -  go to the first line of the file
G  -  go to the last line of the document
5g -  go to line 5
fx -  find next character x
tx -  find recent character x
}  -  skip to next block
{  -  skip to previous block
```

### Insert mode

```
i - insert before cursor
I - insert at beginning of the line
A - insert at the end of the line
o - insert in new line
O - insert new line above current line
ea - insert at end of the word
Esc - exit
```

### Editing
```
r  - replace a single character
j  - join line below
cc - replace entire line
cw - replace till the end of the word
c$ - replace till the end of the line
s  - delete character and substitute text
S  - delete line and and substitute texts
xp - delete and paste
u  - undo
ctrl +r - redo
.  - repeat last command
yy - copy a line
2yy - copy 2 lines
y$  - copy to end of line
p   - paste after cursor
P   - paste before cursor
dd  - delete a line
2dd - delete 2 lines
dw  - delete characters of a word from the current position till the next word
D   - delete to the end of the line
d$  - delete to the end of the line
x   - delete character
/pattern - search for pattern
?pattern - search back for pattern
n  - repeat search forward
N  - repear search backward
:%s/old/new/g - replace old file with new pattern in all files
:%s/old/new/gc - replace old file with new pattern with confirmation
:noh - remove highlighting of search matches
```

### Visual mode 
```
v  - enter visual mode
V  - start visual mode in line
o  - skip to the end of marked area
O  - move to the corner of block
aw - mark a word
ab - block with ()
aB - block with {}
ib - inner block with ()
iB - inner block with {}
<  - shift right text
<  - shift left text
y  - copy
d  - delete mark text
~  - switch case
ctrl+v - start visual block
ESC - exit
```
