## Installation

For when I forget how to ruby...

```
$ brew install rbenv
# ensure `eval "$(rbenv init -)"` is in ~/.zshrc
# open new shell
$ rbenv install
$ rbenv rehash
$ gem install bundler
$ bundle install
$ bundle exec jekyll serve
```

# flake.nix & direnv
```
direnv allow
bundle install
bundle exec jekyll serve
```
