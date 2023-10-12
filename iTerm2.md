# iTerm2 Installation

## Step 1 - Install iTerm2
You can download iTerm2 from the [official website](https://iterm2.com/downloads.html), unzip it and move the app into Application folder, or you can use homebrew to install it instead.
```bash
brew install --cask iterm2
```

If you haven't installed Homebrew yet, please use the following command in your command line interface to do so:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
``` 

## Step 2 - Install Oh-My-Zsh
### Install with curl
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
    
### Using powerlevel10k as the default theme
```bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
``` 

### Edit the ~/.zshrc and change ZSH_THEME="powerlevel10k/powerlevel10k"
```bash
vim ~/.zshrc
```
### Apply the change and config the theme via iTerm.
```bash
source ~/.zshrc
```

## Step 3 - Make VS Code use the same terminal theme.
Go to the VS Code menu: Preferences > Settings, and edit the following settings:
```json
"terminal.explorerKind": "external",
"terminal.external.osxExec": "iTerm.app",
"terminal.integrated.defaultProfile.osx": "zsh",
"terminal.integrated.fontFamily": "Meslo LG M for Powerline",
```


[Go Back](./README.md)
