# Vim command

##### general
1. insert new lines: o O
2. c delete and enter insert mode
3. f + character you want jump to
4. vip  select the paragraph
5. CTRL+\[  exit insert mode
6. 5+s delete 5 chars from cursor
7. :noh clear the highlights
[more](http://www.worldtimzone.com/res/vi.html)
[Link to another page](https://www.keycdn.com/blog/vim-commands).

##### replace multiple places
search then cgn n. n.
[You don't need a cursur](https://medium.com/@schtoeffel/you-don-t-need-more-than-one-cursor-in-vim-2c44117d51db)

##### NERDTree
1. gt = next tab
2. gT = previous tab

##### resize window
1. vertical resize +/-20N
2. res +/-20N

##### move file in insert mode
1. ctrl+X ctrl+E
2. ctrl+X ctrl+Y

##### unindent in insert mode
1. cmd+d unindent
2. cmd+t indent

##### indent/unindet in normal mode
1. \>\> indent the current line
2. \<\< to uninden
2. shift+V + < >

##### Find/replace
1. :%s/find/replace/g 

##### delete words in insert mode
1. ctrl+w delete the words before the cursor
2. ctrl+u delete current line

##### Ctags
1. ctags . 
2. :tn next tags      
3. :tp previous tags   
4. :ts list all  
5. ^]	Jump to definition
6. ^t	Jump back from definition
7. ^W }	Preview definition
8. g]	See all definitions

##### search
1. :grep  -r (recursive) -i (ignore-case) --include (search only files that match the file pattern)
2. ]q next
3. [q previous
4. :cclose
5. :copen

##### CtrlP: search files
1. ctrl+v split vertically
2. ctrl+x split h

##### modify multiple lines
1. ctrl+v -> select lines -> shift + I -> do whatever(example //) -> ESC after esc it the change will apply to all the lines
2. ctrl+v -> select -> shift+X to delete
