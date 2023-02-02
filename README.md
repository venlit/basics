# basics
neovim plugins and languages for myself 

download nvim folder using https://download-directory.github.io/

universal ctags: https://github.com/universal-ctags/ctags-win32/releases/download/p6.0.20230122.0/ctags-p6.0.20230122.0-x64.zip

python: https://www.python.org/downloads/

extract to userprofile\appdata\local

run neovim

:PlugInstall


below are notes

# commentary
gcc to comment out a line

gc to comment out the target of a motion (for example, gcap to comment out a paragraph)

gc in visual mode to comment out the selection

gc in operator pending mode to target a comment

gcgc uncomments a set of adjacent commented lines

# surround
brackets & parenthesis as example

hello + ysiw] = [hello]

hello + ysiw[ = [ hello ]

ds[ -> removes delimeters - either [ or ] can be used

[hello] + cs[( -> ( hello )

hello world + yss( = ( hello world )

# vim-terminal
install python

:Terminal cargo run -> compile rust code

# tagbar
install universal ctags and add to path

f8: toggle tagbar

# nerdtree
ctrl + t -> toggle tree

ctrl + f -> cursor to tree

ctrl + n -> does something idk

# multiple cursors
https://github.com/terryma/vim-multiple-cursors

# icons
look here: https://github.com/ryanoasis/vim-devicons

# airline
look here: https://github.com/vim-airline/vim-airline

# autocomplete
install node.js: https://nodejs.org/dist/v18.13.0/node-v18.13.0-x64.msi


