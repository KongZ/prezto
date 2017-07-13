# prezto
My custom theme and script for zsh and prezto

## Prezto Theme
To install a prezto theme, you need to copy a theme file to `~/.zprezto/modules/prompt/functions`

And add the following line to `~/.zshrc`

```bash
# Prezto Prompt
autoload -Uz promptinit
promptinit
prompt kongz
```

![kongz prompt screenshot](https://github.com/KongZ/prezto/raw/master/prompt/kongz_prompt.png)

I also recommend to add these line to `~/.zshrc` to disable alternative keymap when sending backward-word command.

```bash
# Bindkey
bindkey -e
bindkey '[B' backward-word
bindkey '[F' forward-word
```
## Terminal Color
If you want to change a color, you may need to find out the color code of your terminal. Add this line to `~/.zshrc` and type `color` to get a list of color code and sampling on your terminal.

```bash
function color() { for code in {000..255}; do print -P -- "$code: %F{$code}Color%f"; done }
```

## VIM

![vim screenshot](https://github.com/KongZ/prezto/raw/master/vim/vim.png)
