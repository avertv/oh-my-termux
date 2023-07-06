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
bash -c "$(curl -fsSL https://bit.ly/oh-myzsh)"
```

# Revert to back
```bash
rm -r $HOME/.termux/*; rm -rf $HOME/.oh-my-zsh; rm -rf $HOME/.termux.bak; touch termux.properties; termux-reload-settings
```
