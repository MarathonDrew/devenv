# Development Environment Setup

## Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Install Brew Basics

```
brew install git
brew cask install iterm2
```

Note:  close stock terminal and open iTerm2 now

## Install oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install PowerLevel10k

See [PowerLevel10k](https://github.com/romkatv/powerlevel10k#oh-my-zsh)

## Link config files

```
git clone https://github.com/MarathonDrew/devenv.git
ln -s devenv/gitconfig .gitconfig
```

## Install Homebrew Casks

```
brew install node
brew install pyenv
brew cask install firefox
brew cask install google-chrome
brew cask install visual-studio-code
brew cask install docker
brew cask install virtualbox
brew cask install spotify
```
