# dotfiles-zsh

Zsh configuration.
Oh My Zsh, bureau theme, autosuggestions.

---

## Stack

- **Shell** : Zsh
- **Framework** : Oh My Zsh
- **Theme** : bureau
- **Plugins** : zsh-autosuggestions, zsh-syntax-highlighting
- **Fetch** : Fastfetch

---

## Dependencies

```bash
sudo pacman -S zsh zsh-autosuggestions zsh-syntax-highlighting fastfetch

# Set zsh as default shell
chsh -s /usr/bin/zsh

# Install Oh My Zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install plugins
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

---

## Install

```bash
git clone git@github.com:Hugo-Fabresse/dotfiles-zsh.git ~/dotfiles/zsh
ln -s ~/dotfiles/zsh/zshrc ~/.zshrc
source ~/.zshrc
```

---

## Content

```
zsh/
└── zshrc
```
