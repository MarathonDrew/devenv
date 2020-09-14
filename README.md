# Development Environment Setup

## Install oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Install Git

```
brew install git
```

## Link config files

```
git clone https://github.com/MarathonDrew/devenv.git
ln -s devenv/gitconfig .gitconfig
```

## Install Homebrew Casks

```
brew install node
brew install pyenv
brew tap caskroom/cask
brew cask install iterm2
brew cask install firefox
brew cask install google-chrome
brew cask install visual-studio-code
brew cask install docker
brew cask install virtualbox
brew cask install spotify
```