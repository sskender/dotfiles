# dotfiles

My dotfiles library

## Quickstart

### Submodules

Cloning with submodules

```bash
git clone --recurse-submodules git@github.com:sskender/dotfiles.git
```

Updating

```bash
git pull
git submodule update --init --recursive
```

### Installation

#### Alacritty

```bash
ln -s ~/Documents/dotfiles/alacritty/alacritty.toml ~/.alacritty.toml
```

#### Tmux

```bash
ln -s ~/Documents/dotfiles/tmux/tmux.conf ~/.tmux.conf
```

#### Vim

```bash
ln -s ~/Documents/dotfiles/vimrc/vimrc ~/.vimrc
```

#### Neovim

```bash
ln -s ~/Documents/dotfiles/vimrc/nvim ~/.config/nvim
```

#### zshrc

```bash
ln -s ~/Documents/dotfiles/zshrc/zshrc ~/.zshrc
```
