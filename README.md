# Resources for Sykes new grads

Welcome to the team, I have tried to keep this as platform agnostic as possible. However, I am on a mac
so some of what is listed below (especially in the terminal section) may need some alteration depending on you chosen OS.

Also, disclaimer. There are some very opinionated choices in here so I can only advise that you try things out and see what works for you.
Hopefully you find some gems here.

Finally, if you are interested in learning Vim 🥷. I'd be happy to answer any questions you have and help to get a solid config setup for working with 
our projects.

## Git

- [Git Pro (The Official Git Book)](https://git-scm.com/book/en/v2)
- [Advanced Git Magic](https://www.youtube.com/watch?v=x5Ib33eUUvo)
- [Git Legit](https://www.youtube.com/watch?v=O7LAeqng-SI)
- [13 Advanced (but useful) Git Techniques and Shortcuts](https://www.youtube.com/watch?v=ecK3EnyGD8o)
- [Git Good](https://www.youtube.com/watch?v=Uk5TnFL7jh4)
- [Using Vim: Vim + Git - Fugitive Part 1 - Usage and Merge Conflicts](https://www.youtube.com/watch?v=PO6DxfGPQvw)
- [Git's Best And Most Unknown Feature](https://www.youtube.com/watch?v=2uEqYw-N8uE)
- [What makes a good commit message Twitter thread](https://twitter.com/kuizinas/status/1541496585275727875)

## PHP

- [PHP The Right Way](https://phptherightway.com/)
- [Start as you mean to go on. PHP-FIG sets out standards that we should follow as a community](https://www.php-fig.org/)
- [Clean Code PHP](https://github.com/jupeter/clean-code-php)
- [Phinx docs. You will need these for creating Database migrations](https://book.cakephp.org/phinx/0/en/index.html)
- [PHPUnit docs. A great reference that you will use a lot](https://phpunit.readthedocs.io/en/9.5/installation.html)
- [A list of awesome PHP things](https://github.com/ziadoz/awesome-php)
- [Docker image providing static analysis tools for PHP](https://github.com/jakzal/phpqa)
- [Setup XDebug with Docker and PHPStorm](https://www.youtube.com/watch?v=4opFac50Vwo)
- [What does this PHP operator do?](https://stackoverflow.com/questions/3737139/reference-what-does-this-symbol-mean-in-php)

## Our Environments

- [A conference talk from our own Scott Dutton on the code quality tools we use at Sykes (helpful for understanding our build processes)](https://www.youtube.com/watch?v=MmoZz_j2Y1A&t=671s)
- [A Docker crash course from our own James Lockhart](https://www.youtube.com/watch?v=zIOqJhlk9VY&list=PL16WqdAj66SBSLZ2-TrZ5q_39UhtKyL9U)
- [BitBucket Pipeline Validator. Check here if you ever make changes to a pipline](https://bitbucket-pipelines.atlassian.io/validator)
- [Sykes Github page. Dig into our docker images and public libraries here](https://github.com/SykesCottages)

## Database

- [Use the Index Luke! A Guide to Database Performance for Developers](https://use-the-index-luke.com/)

## AWS

- [CDK Workshop](https://cdkworkshop.com/)

## TDD

- [Katalyst TDD Katas](https://katalyst.codurance.com/browse)
- [Test Driven Laravel Conference talk (Adam Wathan's course of the same name is also awesome)](https://www.youtube.com/watch?v=MdApmmK71WM)

## Design

- [PHP Design Patterns](https://designpatternsphp.readthedocs.io/en/latest/README.html)

## Terminal

- Get a [proper terminal](https://iterm2.com/). Alacritty, Kitty and Hyper are also worth a look if you don't get on with iterm.
---
- [The terminal theme I keep getting asked about](https://github.com/herrbischoff/iterm2-gruvbox)
---
- [Execute artisan from anywhere within the project file tree](https://github.com/jessarcher/zsh-artisan)
---
- Alias all the things - Especially alias cd to project dirs. Saves loads of time.
```bash
alias zshrc="vim $HOME/zshrc"
alias srczsh="source $HOME/zshrc"

alias ga="git add"
alias gcm="git commit -m"
alias gs="git status"
alias gp="git push"
alias nah='git reset --hard;git clean -df'

alias d="docker"
alias dc="docker-compose"
alias dps="docker ps"
alias art="php artisan"

alias c="composer"
alias cu="composer update"
alias cr="composer require"
alias ci="composer install"
```
---
- Embrace [OhMyZSH](https://ohmyz.sh/) and the [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) plugin
---
- Learn to spin up containers for quick tests
```bash
d run --platform=linux/amd64 --rm -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root mysql:5.7
```
---
- Fall in love with [RipGrep](https://github.com/BurntSushi/ripgrep)
---
- Create a very basic .vimrc config for when you need to use vim (or go wild with it and become an elitist).
```
set number
set noswapfile
set shiftwidth=4
set scrolloff=10
set nowrap
set autoindent
```
