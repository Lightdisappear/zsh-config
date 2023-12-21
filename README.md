# zsh-config

```bash
apt install curl zsh -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# get themes and plugins
wget -P ${HOME}/.oh-my-zsh/themes https://raw.githubusercontent.com/ChesterYue/ohmyzsh-theme-passion/master/passion.zsh-theme
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# get .zshrc
wget -P ${HOME} -O .zshrc  https://raw.githubusercontent.com/Lightdisappear/zsh-config/master/.zshrc
```