# Setup

## Preparation

### For vim user

If you have not installed any syntax checker, you should install [`syntastic`](https://github.com/scrooloose/syntastic:).

### For atom user

If you have not installed [`linter`](https://atom.io/packages/linter), you should install it before (`apm install linter`).


## JavaScript

### common

### vim

### atom

## Ruby

### Common

1. Install rubocop `gem install rubocop`

### vim

#### with syntastic (auto syntax highlight) (Recommended)

1. Just let the variable `let g:syntastic_ruby_checkers = ['rubocop']`
2. You may have some errors, then see the [wiki](https://github.com/scrooloose/syntastic/wiki/Ruby:---rubocop)

#### with vim-rubocop (manually invoke rubocop [:RuboCop])

1. Install the [plugin](https://github.com/ngmy/vim-rubocop) anyhow

### atom

1. Install rubocop `gem install rubocop`
2. Intall `linter-rubocop` `apm install linter-rubocop`

## SCSS

### common

### vim

### atom
