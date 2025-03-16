my dot files.

---
# Install apps
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## Terminals etc.
brew install ghostty
brew install neovim
brew install zellij

brew install fzf
brew install yazi
brew install lazygit

# php
brew install composer

## Python
curl -LsSf https://astral.sh/uv/install.sh | sh

### API testing
uv tool install --python 3.12 posting

## go/node
from website

## .zshrc
- oh-my-zsh
- starship prompt
.config/starship.toml

## neovim
.config/nvim

kickstart:
git clone https://github.com/nvim-lua/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
