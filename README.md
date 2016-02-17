## Getting started

### Xcode
```
xcode-select --install
```

### Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Ruby
```
brew update

brew install rbenv ruby-build

# Add rbenv to bash so that it loads every time you open a terminal
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile

# Install Ruby
rbenv install 2.2.2
rbenv global 2.2.2
ruby -v

export PATH="$HOME/.rbenv/bin:$PATH"
eval "$(rbenv init -)"
```

### Bundler
```
gem install bundler
```

### Node
```
brew install node
```
