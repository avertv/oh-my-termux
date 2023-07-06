# oh-my-termux

Setup Termux with:

 - Solarized Dark
 - Ubuntu Mono with powerline patch
 - oh-my-zsh

# Requirement
- curl
```bash
pkg install -y libcurl curl
```

# Installation
```bash
bash -c "$(curl -fsSL https://git.io/oh-my-termux)"
```

# Revert to back
```bash
rm -r $HOME/.termux/*; touch termux.properties; termux-reload-settings
```
