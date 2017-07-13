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

I also recommend to add these line to `~/.zshrc` to disable alternative keymap when sending backward-word command.

```bash
# Bindkey
bindkey -e
bindkey '[B' backward-word
bindkey '[F' forward-word
```
