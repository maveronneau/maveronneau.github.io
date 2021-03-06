## Getting started

### Xcode
```bash
xcode-select --install
```

### Homebrew
```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Ruby
```bash
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
```bash
gem install bundler

bundle install
```

### Node
```bash
brew install node
```
### Serve local website
```bash
bundle exec jekyll serve
```
