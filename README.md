<strong>Question:</strong> <em>What are the differences between all these mapping commands anyways!?</em><br> <code> map remap noremap inoremap vnoremap </code><br>
<strong>Answer:</strong> [Stack Overflow Vim Mapping](http://stackoverflow.com/questions/3776117/what-is-the-differen$)
-  <kbd>n</kbd>: normal only
-  <kbd>v</kbd>: visual and select
-  <kbd>o</kbd>: operator-pending
-  <kbd>x</kbd>: visual only
-  <kbd>s</kbd>: select only
-  <kbd>i</kbd>: insert
-  <kbd>c</kbd>: command-line
-  <kbd>l</kbd>: insert, command-line, regexp-search
<hr>


<strong>turn off loud annoying bells triggered on error push</strong>
- `set visualbell` <br>
- `set noerrorbells`<br>

<strong>Hit <kbd>jk</kbd> to enter normal mode!</strong>
- `inoremap jk <ESC>`<br>
    <strong>Question:</strong> <em> ... But what if I want to write <kbd>jk</kbd>!? </em><br>
    <strong>Answer:</strong> No problem! Just hit <kbd>j</kbd> wait one second, and hit <kbd>k</kbd>!
