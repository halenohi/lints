# Setup

## Preparation

### For vim user

If you have not installed any syntax checker, you must install [`syntastic`](https://github.com/scrooloose/syntastic:).

### For atom user

If you have not installed [`linter`](https://atom.io/packages/linter), you must install it before (`apm install linter`).


## JavaScript

### common

If you have not installed `nodejs`, you must install it.

1. Install [nvm](https://github.com/creationix/nvm). Please follow the instruction on the page.
2. Install nodejs `nvm install stable` and set it as default `nvm alias default stable`.

Then `npm` command is available now. Install `jshint`

1. `npm install jshint`

### vim

1. Let the variable `let g:syntastic_javascript_checkers = ['jshint']`

### atom

1. Install linter-jshint `apm install linter-jshint`

## Ruby

### Common

1. Install rubocop `gem install -g rubocop`

### vim

#### with syntastic (auto syntax highlight) (Recommended)

1. Just let the variable `let g:syntastic_ruby_checkers = ['rubocop']`
2. You may have some errors, then see the [wiki](https://github.com/scrooloose/syntastic/wiki/Ruby:---rubocop)

#### with vim-rubocop (manually invoke rubocop [:RuboCop])

1. Install the [plugin](https://github.com/ngmy/vim-rubocop) anyhow

### atom

1. Intall linter-rubocop `apm install linter-rubocop`

## SCSS

### common

1. Install scss-lint `gem install scss-lint`

### vim

1. Just let the value `let g:syntastic_scss_checkers = ['scss_lint']`

### atom

1. Intall linter-scss-lint `apm install linter-scss-lint`
