# new-computer-setup

setting up a new machine

## terminal

- [Dimmed Monokai](files/DimmedMonokai.terminal)
- `brew install eza`

#### zsh / .zshrc

zsh
- `touch ~/.hushlogin`

.zshrc
```
nano ~/.zshrc

# add
alias ls='eza'
PS1="%{$(tput setaf 196)%}%n%{$(tput setaf 245)%}@%{$(tput setaf 249)%}%m %{$(tput setaf 131)%}%1~ %{$(tput sgr0)%}$ "
```

## keyboard

- install [Karabiner](https://pqrs.org/osx/karabiner/)
- [mapping](files/karabiner.json)
- system preferences -> keyboard -> press X to do `Nothing`
- system preferences -> keyboard -> keyboard shortcuts -> services -> searching -> uncheck `look up in dictionary`

## git config

```bash
git config --global user.name "your name"
git config --global user.email "your email"
git config --global pull.rebase false
git config --global core.editor "nano"
```

## mac trackpad

- system preferences -> trackpad -> look up & data detectors -> `off`

## window management

- download [rectangle](https://rectangleapp.com/)
- [config](files/RectangleConfig.json)

## vs code

- theme: [Atom One Dark](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
- change `go to definition` key binding from `F12` to `cmd+shift+d`

## dygma

- if needed, restore [backup](files/20231201093839-.json)
