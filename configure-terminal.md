# Configure terminal

Install zsh.

Install oh-my-zsh.

Install the following plugins for oh-my-zsh:

- zsh-autosuggestions:
    - git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
- zsh-syntax-highlighting:
    - git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
- fast-syntax-highlighting:
    - git clone https://github.com/zdharma-continuum/fast-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting
- zsh-autocomplete:
    - git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autocomplete
- fzf:
    - Install fzf in operational system.

Put this settings in `~/.zshrc`: [ZSHRC](./.zshrc).
