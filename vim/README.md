## Overview

If you installed a [yadr](https://github.com/skwp/dotfiles) and found your strange behavior of vim such as a color and copy & paste malfunction.
You can fix them by just copy my `.vimrc` to `~/.vimrc`

#### Fix copy and paste
Remove this line from `.vimrc`

```
set autoindent
```

#### Fix colors on Mac
Add these line to `.vimrc`

```
let g:solarized_termcolors= 16
let g:solarized_termtrans = 16
let g:solarized_bold = 1
let g:solarized_underline = 1·
let g:solarized_italic = 1
let g:solarized_contrast = "high"
let g:solarized_visibility= "high"
set background=dark
colorscheme solarized
```
