# 🎨 Codely VIM theme port

<p align="center">
    <img src="https://raw.githubusercontent.com/codingpotions/codely-vim-theme/master/media/example.png" alt="Codely Theme example"><br>
    <sub>A port of the modern, good-looking, productivity-increaser theme of Codely for VIM</sub>
</p>

## How to install

### Option 1: Manual

Download the repo and move `/colors/codely-theme.vim` to `~/.vim/colors` directory.

### Option 2: vim-plug

If you have [vim-plug](https://github.com/junegunn/vim-plug) installed, include this lines in your `.vimrc`:

```vim
Plug 'codingpotions/codely-vim-theme'

set background=dark

colorscheme codely-theme
```

## Troubleshooting

If the colors are wrong maybe is beacuse this theme requires `vim` to support the `+termguicolors` option.

Try to add this line into your `.vimrc`:

```vim
set termguicolors
```

## Contributing

This is my first theme so there may be certain bugs, if you find any and know how to fix it, feel free to send me a PR.


