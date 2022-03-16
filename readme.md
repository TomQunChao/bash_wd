# wd

类似[oh-my-zsh的wd插件](https://github.com/mfaerevaag/wd)

a script work like [wd plugin of oh-my-zsh](https://github.com/mfaerevaag/wd)

## Install

1. download the `wd` script file
2. copy the script to PROGRAM_DIR(According to you)
3. link the script to `/usr/local/bin` or `~/.local/share/bin`

```sh
sudo ln -s PROGRAM_ABSOLUTE_DIR/wd /usr/local/bin/wd
```
4. set alias to `.bashrc`

edit the ```~/.bashrc```

add a line below the last line

```
alias wd="source wd"
```
5. restart your terminal

## Documention

- wd add NAME

add the current path with nick name NAME

- wd remove

remove the current path

- wd remove NAME

remove NAME

- wd

list the all nick name and path

all information are saved in ~/.config/wd/config
