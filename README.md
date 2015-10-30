# ideavim
###Vim and Ideavim settings stored here for seamless integration. 
<hr>
-Ideavim refers to the vim plugin used by Jet Brains IDE(s) like Pycharm, CLION, RubyMine, etc.
<br>
" ========= Important MAPPING Notes =========
" Source: " 
[Stack Overflow Mapping](http://stackoverflow.com/questions/3776117/what-is-the-differen$)
- " `n`: normal only
- " `v`: visual and select
- " `o`: operator-pending
- " `x`: visual only
- " `s`: select only
- " `i`: insert
- " `c`: command-line
- " `l`: insert, command-line, regexp-search (and others. Collectively 
called "$
" ======= End Important MAPPING notes ========
<hr>


" turn off loud annoying bells triggered on error
`set visualbell` <br>
`set noerrorbells`<br>
<br>
" remappings
`inoremap jk <ESC>`<br>
`nnoremap <SPACE> <Nop>`  " needed in linux. Nop sets space to none.<br>