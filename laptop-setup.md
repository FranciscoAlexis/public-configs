# Laptop set up notes 

## Basic software
* [iTerm2](https://iterm2.com)
* [brew](https://brew.sh) -- Make sure to install/use arm64 version.
* `brew install mise`
* `mise install --global node@latest`
* `mise install --global python@latest`
* `$ brew install zsh`
* [oh my zsh](https://ohmyz.sh)
* XCode Command Line Tools
* `$ brew install gh`
* `$ brew install wget`
* `$ brew install nvim`
* `$ brew install tmux`
* `$ brew install tree-sitter-cli`
* `$ brew install cmake`
* [Checkout dot files in .config/nvim](https://github.com/FranciscoAlexis/nvim-dotfiles)
* [Karabiner](http://karabiner-elements.pqrs.org/)
* [Rectangle Pro](https://rectangleapp.com/pro)

## .zshrc
```
export PATH=$HOME/.cargo/env:$PATH
eval "$(/opt/homebrew/bin/brew shellenv)"
eval "$(mise activate zsh)"
```

## Iterm 
* Appearance theme minimal
* Profiles -> Colors -> Color preset [Ayu Dark](https://github.com/hwyncho/ayu-iTerm)
* Profiles -> Text -> Anti aliased text on retina displays
* Profiles -> Text -> Font -> [DejaVuSansM Nerd Font Mono](https://www.programmingfonts.org/#dejavu)


