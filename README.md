# Linux setup

## Configure SSH

First configure ssh files, I can't put their here so you need to create or clone your own `.ssh` directory and then execute these commands:

```sh
sudo chmod 700 ~/.ssh \
&& sudo chmod 600 ~/.ssh/* \
&& sudo chmod 644 ~/.ssh/*.pub
```

## Programs to install

- VSCode
- Google Chrome
- Docker
- OBS
- Vim
- Neovim
- Git
- Neofetch
- Insomnia
- Dbeaver
- Fish
- fzf
- ASDF
    - PHP
    - NodeJS
    - Python
- Kdenlive

## Configure FISH

Install fish.

Move `./configs/fish/conf.d` to `~/.config/fish/conf.d`.

## Configure TMUX

Mova o arquivo `.configs/tmux/.tmux.conf` para `~/.tmux.conf`.
