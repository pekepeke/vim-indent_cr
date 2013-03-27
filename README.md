# indent_cr

indent braces and move cursor to suitable position

Version: 0.0.1
OriginalAuthor: acustodioo <http://github.com/acustodioo>
Author : pekepeke <pekepekesamurai+vim@gmail.com>
License: GPL
         <http://www.gnu.org/licenses/gpl.html>

## INTRODUCTION

*indent_cr* is a Vim plugin to provide indent braces 
and move cursor to suitable position at press <CR> key

Notes:
	- vim-enter-indent : https://github.com/acustodioo/vim-enter-indent

Latest version:
	https://github.com/pekepeke/vim-indent_cr


### KEY MAPPINGS

#### <Plug>IndentCR


### EXAMPLES

- At first, you have to map. like the following:


	nmap <expr> <CR> <Plug>IndentCR


- Suppose that you edit a buffer with the following content:( note `|` indicates the cursor position)


	<?php | ?>

- If you press <CR>, the buffer will be changed as following content.


	<?php
		|
	?>

