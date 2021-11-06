## system clipboard support

First of all always check if vim has +clipboard support using 
```bash
vim --version | grep "+clipboard"
vim --version | grep "+xterm_clipboard"

```
if it doesn't have it then 
```bash
sudo apt install `vim-gtk`
```
check it again

this command command will allow to use clipboard
```vim
:set clipboard=unnamedplus
```

.vimrc file
```bash
set clipboard=unnamedplus
set relativenumber
```