# setfiles

My configuration settings for:

-   [VS Code](https://code.visualstudio.com)
-   [ESLint](https://eslint.org)
-   [Prettier](https://prettier.io/)
-   [oh-my-zsh](https://ohmyz.sh/)
-   [iTerm2](https://iterm2.com/)
-   [Starship Prompt](https://starship.rs/)

### Fonts

-   JetBrains Mono - [https://www.jetbrains.com/lp/mono/](https://www.jetbrains.com/lp/mono/)
-   Or use default  fonts: `Menlo, Monaco, 'Courier New', monospace `

### Terminal theme

-   Starship Prompt (current) - [https://github.com/starship/starship](https://github.com/starship/starship) or [starship.rs](https://starship.rs/)
-   Spaceship Prompt - [https://github.com/denysdovhan/spaceship-prompt](https://github.com/denysdovhan/spaceship-prompt)

### Terminal font

-   JetBrainsMono Nerd Font - [Download](https://www.nerdfonts.com/font-downloads)

...and than update the setting in VS Code:

`"terminal.integrated.fontFamily": "JetBrainsMonoMedium Nerd Font Mono, Menlo for Powerline, monospace"`

### Terminal aliases

```
alias gs="git status"
alias vim="nvim"
alias lla="ll -a"
alias gl="git log --graph --abbrev-commit --decorate --format=format:'%C(bold yellow)%h%C(reset) - %C(bold blue)(%aD) %C(dim blue)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold magenta)%d%C(reset)' --all"
```

Also added a custom alias for the commit message - `gcv`:

```
function gcv {
  YELLOW="\e[33m"
  ENDCOLOR="\e[0m"
  RED="\e[31m"

  if [[ "$1" = "" ]]
    then
      echo "${RED}✗ error: enter your commit message!${ENDCOLOR}"
  elif [[ "$1" != "" ]] && [[ "$2" = "--no" ]]
    then
      echo "${YELLOW}⚡ hint: skipped pre-commit!${ENDCOLOR}"
      git commit --no-verify -m "$1"
  else
    git commit -m "$1"
  fi
}
```

### VS Code

All settings and extensions [here](./vs-code-extensions.md#update-2025-extension-package-names)
