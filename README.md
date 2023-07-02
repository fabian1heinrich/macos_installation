# MACOS

## brew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
  
### formulaes

```bash
brew install \
docker \
docker-compose \
git \
jq \
k9s \
kind \
kubernetes-cli \
mkcert \
python@3.11 \
wget \
zsh
```

```bash
xargs brew install < configs/list-brew.txt
```

### --cask formulaes

```bash
brew install --cask \
arc \
ccleaner \
discord \
google-chrome \
google-drive \
hiddenbar \
iterm2 \
languagetool \
megasync \
monitorcontrol \
mos \
obsidian \
raycast \
selfcontrol \
shottr \
signal \
spotify \
stats \
visual-studio-code \
zoom
```

```bash
xargs brew install --cask < configs/list-brew-cask.txt
```

## download

- [functionkeypro](https://functionkey.pro/download/FunctionKeyPro.dmg)
- [later](https://github.com/alyssaxuu/later/raw/master/Later.dmg)
- [Ooooo](https://apps.apple.com/us/app/ooooo/id1482773008?mt=12)
- [TeamDrive](https://download.teamdrive.net/5.0.2.3333/TMDR/mac/Install-TeamDrive-5.0.2.3333_TMDR.dmg)
- [magnet](https://apps.apple.com/de/app/magnet/id441258766?mt=12)
- [proxy-audio-device](https://github.com/briankendall/proxy-audio-device)
- [hiddenbar](https://apps.apple.com/us/app/hidden-bar/id1452453066?mt=12)

## configs

### iterm2

import iterm2 config

### zsh

```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
cp configs/robbyrussel.zsh-theme ~/.oh-my-zsh/themes/
cp configs/.zshrc ~/
```
