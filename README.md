# practice
 - Learning Python repository


# How to install Python

1. [x] Setup homebrew
2. [ ] install pyenv via homebrew
3. [ ] install latest python3 via pyenv

## 1. setup homebrew

see below link
https://brew.sh/

## 2. install pyenv

```install.sh
brew install pyenv

echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(pyenv init -)"' >> ~/.bash_profile

source ~/.bash_profile
```


## 3. install python3

```install.sh
# show all availavle Python versions 
pyenv install --list

# choose version what you need
pyenv install 3.7.0

# set global python version
pyenv global 3.7.0
```

