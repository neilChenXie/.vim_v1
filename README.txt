my vim setting files
install pathogen:
	download from github
install extensions via pathogen:
	mkdir bundle
	clone as websites say

plugin list:

	surround.vim:
	ZenCoding.vim:
	Syntastic: error check
	phpfolding.vim:
		in vimrc, add map command
	c.vim:
		in ./c-support/templates revise to meet my habit:
			\im <iostream> <cstdlib> <type.h> using namepace std;
	YouCompleteMe
	tern_for_vim
		need run: npm install

3/3/2015:
	add C++11 support for syntastic (one line in vimre)
	rm jslint because syntastic included.
3/14/2015:
	ubuntu 12.02 must fork under /etc/vim
5/10/2015:
	YouCompleteMe autocompletion with CMake succeed
	add Node.js autocompletion--Tern for Vim (need node.js and npm)
5/31/2015:
	Solve the compatibility between YouCompleteMe and Syntastic
