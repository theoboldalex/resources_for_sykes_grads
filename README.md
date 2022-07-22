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
- [Phinx docs. You will need these for creating Database migrations](https://book.cakephp.org/phinx/0/en/index.html)
- [PHPUnit docs. A great reference that you will use a lot](https://phpunit.readthedocs.io/en/9.5/installation.html)

## Our Environments

- [A conference talk from our own Scott Dutton on the code quality tools we use at Sykes (helpful for understanding our build processes)](https://www.youtube.com/watch?v=MmoZz_j2Y1A&t=671s)
- [A Docker crash course from our own James Lockhart](https://www.youtube.com/watch?v=zIOqJhlk9VY&list=PL16WqdAj66SBSLZ2-TrZ5q_39UhtKyL9U)
- [BitBucket Pipeline Validator. Check here if you ever make changes to a pipline](https://bitbucket-pipelines.atlassian.io/validator)

## Tips for setting up you local machine

- Alias all the things - TODO: add repo aliases
```
alias zshrc="vim ~/.zshrc"
alias srczsh="source ~/.zshrc"

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

- Embrace [OhMyZSH](https://ohmyz.sh/) and the [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) plugin
