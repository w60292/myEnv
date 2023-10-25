# Node Version Manager (nvm) installation

```bash
# Install via homebrew
$ brew install nvm

# Paste the following commands into `~/.zshrc`
export NVM_DIR="$HOME/.nvm"
  [ -s "/usr/local/opt/nvm/nvm.sh" ] && \. "/usr/local/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/usr/local/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion

# Apply changes
$ source ~/.zshrc

# install Node.js 
$ nvm install 16
$ nvm use 16
Now using node v16.20.2 (npm v8.19.4)
$ node -v
v16.20.2
```

[Go Back](./README.md)
