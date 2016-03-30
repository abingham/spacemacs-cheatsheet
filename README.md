# spacemacs-cheatsheet

## Navigation

| Action                     | Keys    |
|----------------------------+---------|
| up,down,left,right         | k,j,h,l |
| top of buffer              | gg      |
| bottom of buffer           | G       |
| beginning of line          | 0       |
| first char of line         | ^       |
| end of line                | $       |
| goto line N                | SPC y N |
| goto line                  | SPC y   |
| start of next word         | w       |
| end of current word        | e       |

## Searching

| first char search          | SPC SPC   |
| start search               | /<string> |
| next match                 | n         |
| previous match             | N         |
| goto corresponding (, {, [ | %         |
| next occurrence of word    | *         |
| prev occurrence of word    | #         |


## Editing

| Action                       | Keys        |
|------------------------------+-------------|
| replace character            | r<new char> |
| insert mode                  | i           |
| append mode                  | a           |
| delete character             | x           |
| open new line below          | o           |
| open new line above          | O           |
| delete to end of line        | d$          |
| delete to end of word        | de          |
| delete to start of next word | dw          |
| delete current line          | dd          |
| replace current word         | ciw         |
| replace to end of word       | cw          |
| yank current selection       | y           |
| paste                        | p           |
| undo                         | u           |
| redo                         | C-r         |

## Selection

| Action           | Keys  |
|------------------+-------|
| initial expand   | SPC v |
| expand more      | v     |
| select within () | vi(   |
| select ()        | va(   |

## Buffers and files

| Action          | Keys   |
|-----------------+--------|
| my helm buffers | SPC bb |
| save buffer     | SPC fs |
| open file       | SPC ff |

## Misc

| Action                 | Keys       |
|------------------------+------------|
| repeat last command    | .          |
| repeat command N times | N<command> |
