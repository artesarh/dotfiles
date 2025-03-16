my dot files.

---
# Install apps
``` bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Terminals etc.
```bash

brew install ghostty
brew install neovim
brew install zellij

brew install fzf
brew install yazi
brew install lazygit

```

# php

``` bash

brew install composer
```

## Python
``` bash

curl -LsSf https://astral.sh/uv/install.sh | sh
```


### API testing
``` bash

uv tool install --python 3.12 posting
```


## go/node
from website

## .zshrc
- oh-my-zsh
- starship prompt
.config/starship.toml

## neovim
.config/nvim

kickstart:
``` bash
git clone https://github.com/nvim-lua/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
