# new-computer-setup

setting up a new machine

## terminal

- [Dimmed Monokai](files/DimmedMonokai.terminal)
- `brew install exa`

#### zsh

```
# ~/.zshrc
alias ls="exa -bghl"
PROMPT='%F{red}%n%f %~ :$ '
```

- `touch ~/.hushlogin`

## keyboard

- install [Karabiner](https://pqrs.org/osx/karabiner/)
- [mapping](files/karabiner.json)
- system preferences -> keyboard -> press X to do `Nothing`
- system preferences -> keyboard -> keyboard shortcuts -> services -> searching -> uncheck `look up in dictionary`

## mac trackpad

- system preferences -> trackpad -> look up & data detectors -> `off`

## window management

- download [rectangle](https://rectangleapp.com/)
- [config](files/RectangleConfig.json)

## vs code

- theme: [Atom One Dark](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
- extensions:
    - [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
    - [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
- change `go to definition` key binding from `F12` to `cmd+shift+d`

## dygma

- if needed, restore [backup](files/20231201093839-.json)
