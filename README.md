# new-computer-setup
setting up a new machine

## Terminal

- [Dimmed Monokai](files/DimmedMonokai.terminal)
- `brew install exa`
- bash profile
```
export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls="exa -bghl"
```

## Keyboard

- install [Karabiner](https://pqrs.org/osx/karabiner/)
- [mapping](files/karabiner-config.json)

## VS Code

- theme: [Atom One Dark](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
- extensions:
    - [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
    - [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
