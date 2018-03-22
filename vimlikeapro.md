#Vim Like a Pro

##Comands

- **vim commands format:** `register repeats operation movement `

		example: 13 y y will copy the next 13 lines 

###Opening files

- **vimdiff file1.txt file2.txt** `will open the editor with merge tool kinda style`
- **vim -o file 1 file N** `will open multiple files horizontally `
- **vim -O file 1 file N** `will open multiple files vertically `
- **vim -p file 1 file N** `will open multiple files with tabs 
    gt will move between tabs `


###Basic operations

- **yy** `copy the text of the current line`
- **p** `paste the content on the clipboard`
- **dd** `delete the current line`

###Advanced Delete operations
- **d}** `delete from the cursor until the end of the paragraph`
- **dG** `delete from the cursor until the end of file`

###Special operations
- **dot** `repeat the last operation in register`
- **star** `move to next instance of word under cursor`
- **hashtag** `move to previous instance of word under cursor`
    
###Searching

- **/** `searches forward `
- **?** `searches backward `
- **n** `repeats last search `
- **N** `repeats last search in opposite direction `
- **tx** `moves to next lettr “x” and stops before it `
- **fx** `finds lettsr “x” and stops on it `

###Moving

- **gg** `goes to start of file `
- **G** `goes to end of file `
- **0** `goes to start of line `
- **zt** `moves current line to top of page`
- **zz** `moves current line to middle of page`
- **zb** `moves current line to bottom of page`
- **w** `moves to start of next word `
- **W** `moves to start of next word ignoring punctuation`
- **b** `moves backward one word`
- **B** `moves backward one word ignoring punctuation`
- **e** `moves to end of word`
- **E** `moves to end of word ignoring punctuation`
- **$** `jumps to end of line`
- **%** `moves to matching brace 
} end of paragraph (next blank line) 
{ start of paragraph (next blank line)`

###Reloading

- **:e!** `reloads file from disk`

###Insert Mode

- **i** `inserts before current position`
- **I** `inserts at the beginning of current line`
- **a** `inserts after current position`
- **A** `inserts at the end of current line`
- **o** `create a new line and enters in insert mode`
- **s** `deletes character under cursor and enters insert mode`
- **cw** `deletes word and enters insert mode`
- **cc** `deletes line and enters insert mode `


###Replace Mode

- **rx** `replace the character under cursor with “x”`
- **R** `enters replace mode until pressing ESC`


###Back to last changings

- **ctrl-r** `is redo`
- **u** `is undo`

