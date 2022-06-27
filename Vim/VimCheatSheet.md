# Vim Cheat Sheet

### Opening a file

* ```vim <file_name>```
* ```nvim <file_name>```

### Closing a file

* Simple quit ```:q```
* Quit without saving ```:q!```
* Quit with saving ```:wq``` | ```:x```

### Insert Mode

* Before cursor ```i```
* After cursor ```a```
* Line below ```o```
* Beginning of line ```I```
* End of line ```A```
* Line above ```O```

### Visual Mode

* Enter ```v```
* Line mode ```V```
* Block mode ```Ctrl + v```

### Editor Settings

* Line numbers ```:set number``` | ```:set nu```
* Remove line numbers ```:set nonumber``` | ```set nonu```
* Relative line numbers ```:set relativenumber``` | ```set rnu```
* Remove relative number ```:set norelativenumber``` | ```set nornu```
* Color scheme ```:colorscheme <name>```
* Enable mouse ```:set mouse=a```
* Tab spaces ```:set tabstop=4```
* Auto indent ```:set autoindent```
* Size of indent ```:set shiftwidth=4```
* Save vim settings ```~/.vimrc```
* Save neovim settings ```~/.config/nvim/init.vim```

### Editor

* Split window vertical ```Ctrl + w + v```
* Split window horizontal ```Ctrl + w + h```
* Move to window ```Ctrl + w + <arrow_key>```
* Edit new file ```:e <file_name>```
* List buffer ```:ls```
* Center the screen ```zz```

### Navigation

* Move down ```j```
* Move up ```k```
* Move left ```h```
* Move right ```l```
* Move n lines ```<n><h/j/k/l>```
* Next word ```w```
* Next word with separators ```W```
* Previous word ```b```
* Previous word with separators ```B```
* End of word ```e```
* Beginning of line ```0```
* End of line ```$```
* Beginning of file ```gg```
* End of file ```G```
* Jump to line ```<line_num>G``` | ```:<line_number>```

### Edit

* Undo ```u```
* Redo ```Ctrl + r```
* Delete current line ```d```
* Delete line ahead ```D```
* Copy ```y```
* Paste ```p```
* Replace ```r```
* Edit after delete ```c```
* Find char in line next ```f<char>```
* Find char in line before ```T<char>```
* Replace word in file ```:%s/<before>/<after>/g```
* Replace in selection ```:s/<before>/<after>/g```
* Repeat command ```.```

### Bindings

* Yank/Delete in between words ```<>iw```
* Edit in between quotes ```<>i"```
* Delete till quote ```dt"```

### Code Specific

* Jump braces [{()}] ```%```
* Comment lines ```Select``` + ```I<>```
* Uncomment lines ```Select``` + ```x```
* Indent a line ```==```
* Indent group of lines ```Select``` + ```=```
* Indent full file ```gg=G```
* Go to next ```*```
* Go to previous ```#```
* Mark position ```m<>```
* Move to mark ```'<>```

### Searching

* Search ```/<>```
* Next search ```n```
* Previous search ```N```
* Search from end ```?<>```