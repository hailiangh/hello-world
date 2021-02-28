## Backspace key not working in Vim/vi
https://askubuntu.com/questions/353911/hitting-arrow-keys-adds-characters-in-vi-editor.287

If you don't already have a .vimrc file in your home directory, create one using this:

vim ~/.vimrc
Add this line to the top of the file:

set nocompatible
Save the file and this should fix the problem for you. :)
