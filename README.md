# Common

- git, zsh, ohmyzsh
- VS code, extensions
- linux aliases
- ohmyzsh, zshrc plugins, themes

# Windows

Install WSL Ubuntu 18.04

https://www.microsoft.com/en-us/p/ubuntu-1804-lts/9n9tngvndl3q?SilentAuth=1&wa=wsignin1.0
https://docs.microsoft.com/en-us/windows/wsl/install

```
# powershell
wsl --install
```

Create symlinks

```
ln -s /mnt/c/Users/lk_le/Downloads Downloads
```

Install Windows Terminal

https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab

- color scheme = One Half Dark

Install git

```
sudo apt-get update
sudo apt-get install git
```

Install zsh

```
apt-get update
sudo apt install zsh
chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)""

# ~/.zshrc
plugins=(themes,git,aliases,common-aliases,history,aws,gcloud,docker,kubectl,kubectx,pyenv,terraform)
```

Install docker

Install kubectl

Install terraform

Install gcloud

https://cloud.google.com/sdk/docs/install#linux

Install awscli

Install common

# Mac OS

```
xcode-select --install
```

Install brew, iterm2

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew cask install iterm2 visual-studio-code

```

Install zsh, ohmyzsh

```
brew install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
upgrade_oh_my_zsh
```

Restart a new iterm2 terminal

```
echo $SHELL
```

https://medium.com/ayuth/iterm2-zsh-oh-my-zsh-the-most-power-full-of-terminal-on-macos-bdb2823fb04c

- Themes
- Plugins
  https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins

# Web2 dev

- amplify
- graphql
- rest
- django, flask
- express

# Web3 developpment

- remix
- js, nextjs
- react
- node
- aliases

# Devops

- python, venv
- docker, packer, ansible
- kubectl, kubens,kubectx, helm, kind
- terraform, chtf
- awscli, gcloud,
- aliases

# datascience

- python panda numby sciktlearn tensorflow
