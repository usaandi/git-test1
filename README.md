# Git basics


## Setup

Setup user name and emails identifying your commits.
```bash
git config --global user.name "John Doe"
git config --global user.email "john.doe@example.com"
```

Setup some nice defaults
```bash
git config --global push.default simple
git config --global branch.autosetuprebase always
git config --global diff.renames
```

You can see your configs
```bash
git config --list
```

## Aliases

You can setup aliases for your git commands.
```bash
git config --global alias.st status
git config --global alias.up "pull --rebase"
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
git config --global alias.ltree "log --oneline --graph --decorate --all"
```

## Links

 * [https://mislav.net/2010/07/git-tips/](https://mislav.net/2010/07/git-tips/)