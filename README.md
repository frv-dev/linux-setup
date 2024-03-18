# Linux setup

## Configure SSH

First configure ssh files, I can't put their here so you need to create or clone your own `.ssh` directory and then execute these commands:

```sh
sudo chmod 700 ~/.ssh \
&& sudo chmod 600 ~/.ssh/* \
&& sudo chmod 644 ~/.ssh/*.pub
```

## Essential to install

- sxhkd
- dunst
- picom
- pywal
- feh
- Vim
- Neovim
- Astronvim
- Fish
- polybar
- rofi

## Programs to install

- VSCode
- Google Chrome
- Docker
- OBS
- Git
- Neofetch
- Insomnia
- Dbeaver
- fzf
- ASDF
    - PHP
    - NodeJS
    - Python
- Kdenlive

## Configure FISH

Install fish.

Copy `~/.config/fish/conf.d` to `~/.config/fish/conf.d`.

Copy `~/.config/fish/config.fish` to `~/.config/fish/config.fish`.

Execute the command `mkdir -p ~/.config/fish/completions;` and `ln -s ~/.asdf/completions/asdf.fish ~/.config/fish/completions`.

On the `~/.config/fish/conf.d/pywal.fish` set the image file for extract terminal colors.

## Configure TMUX

Copy the file `.configs/tmux/.tmux.conf` to `~/.tmux.conf`.
