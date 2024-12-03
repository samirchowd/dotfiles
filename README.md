# dotfiles
Welcome to my dotfiles! Here is where I store all the configurations that I have grown to like.

I try to keep this config as minimal as possible but with enough bells and whistles to keep it fun. 

## Dependencies 

Install the follwing dependencies with your favorite package manager

[chezmoi](https://www.chezmoi.io/)
[kitty](https://sw.kovidgoyal.net/kitty/)
[tmux](https://github.com/tmux/tmux/wiki)
[eza](https://github.com/eza-community/eza)
[fzf](https://github.com/junegunn/fzf)
[git](https://github.com/git/git)
[oh-my-posh](https://ohmyposh.dev/)
[neovim](https://neovim.io/)
[zoxide](https://github.com/ajeetdsouza/zoxide)

## Installation 

First, ensure git is properly configured 

```zsh
git config --global user.name "Your Name Here"
git config --global user.email "your_email@youremail.com"
```

Optionally, you can choose to set the credential helper if you're on mac.

```zsh
git config --global credential.helper osxkeychain
```

Once git is properly configured, you can init my dotfile repos with the following commands.

```zsh
chezmoi doctor
chezmoi init --apply samirchowd
```

## TODOs
- [] Disable `cd` fuzzy find
- [] Create cross-platform zshrc 
- [] Install dependencies through chezmoi/ansible w/ cross platform support 
- [] Post screenshots and demos
