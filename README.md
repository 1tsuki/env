# dotfiles
Personal environment setup kit. Would become an `ansible script` in future.

## At first
Copy private keys to new device, dotfiles are saved in private repo.

## OSX System Preferences
### Keyboard
`System Preferences` -> `Keyboard` -> `Keyboard` -> `Modifier Keys...``

Bind `Caps Lock Key` to `Control`

## homebrew
### install homebrew
follow instructions [here](https://brew.sh/index_ja)

## brew install things
```bash
% brew install zsh zplug go rbenv mysql tree
% brew cask install atom google-chrome google-japanese-ime alfred slack jetbrains-toolbox docker kindle vlc iterm2 evernote firefox zoom yt-music karabiner-elements
```

## setup brewed apps
### karabiner(to swap opt/cmd in majestouch)
- Launch karabiner-elements
- copy karabiner.json to ~/.config/karabiner


### google-japanese-input
`System preferences` -> `Keyboard` -> `Input Sources`
Add `Alphanumeric (Google)`, `Hiragana (google)` then remove all existings.

### iterm
Set iterm coloring as [dracula](https://draculatheme.com/iterm/)

### oh-my-zsh
```bash
% sudo vi /etc/shells
# add `/usr/local/bin/zsh`
% chsh -s /usr/local/bin/zsh
% curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
```

### oh-my-zsh agnoster theme
Setup fixed version of [agnoster](https://github.com/CyberLight/agnoster.zsh-theme)
- install powerline fonts
- set iterm font as powerline

### .zshrc
replace .zshrc

If the username is not 1tsuki, `sed` it.
```bash
% sed -i -e "s/1tsuki/[new_username_here]/g" ~/.zshrc
```

## setup Appstore apps
- todoist (task management)
- spark (mailer)
- [kensington works](https://www.kensington.com/ja-jp/software/kensingtonworks/)
