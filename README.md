# new-computer-setup

setting up a new machine

## terminal

- [Dimmed Monokai](files/DimmedMonokai.terminal)
- `brew install exa`

#### zsh

```
# ~/.zshrc
alias ls="exa -bghl"
PROMPT='%F{red}%n%f:~$ '
```

- `touch ~/.hushlogin`

## keyboard

- install [Karabiner](https://pqrs.org/osx/karabiner/)
- [mapping](files/karabiner.json)
- system preferences -> keyboard -> press X to do `Nothing`

## vs code

- theme: [Atom One Dark](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
- extensions:
    - [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
    - [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
