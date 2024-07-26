# Zsh for Humans Quick

**WARNING:** This script is customized for my computer for automation usage.
If you want to install this awesome project, please visit [this repo](https://github.com/romkatv/zsh4humans)

## Installation

Run this command in bash, zsh, or sh:

```shell
if command -v curl >/dev/null 2>&1; then
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/dongguaguaguagua/zsh4humans_quick/v5/install)"
else
  sh -c "$(wget -O- https://raw.githubusercontent.com/dongguaguaguagua/zsh4humans_quick/v5/install)"
fi
```

## Uninstalling

1. Delete or replace `~/.zshenv` and `~/.zshrc`. If you had these files prior to the installation of
   Zsh for Humans and have replied in the affirmative when asked by the installer whether you want
   them backed up, you can find them in `~/zsh-backup`.
2. Restart your terminal. **Restarting zsh is not enough.**
3. Delete Zsh for Humans cache:
   ```zsh
   rm -rf -- "${XDG_CACHE_HOME:-$HOME/.cache}/zsh4humans/v5"
   ```
