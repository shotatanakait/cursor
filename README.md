## Git clone

```sh
cd ~/.config
git clone git@github.com:shotatanakait/cursor.git
```
## Set symlink

```sh
# Option
mkdir ~/Library/Application\ Support/Cursor/User/bk
mv ~/Library/Application\ Support/Cursor/User/settings.json ~/Library/Application\ Support/Cursor/User/bk/settings.json
mv ~/Library/Application\ Support/Cursor/User/keybindings.json ~/Library/Application\ Support/Cursor/User/bk/keybindings.json

ln -s ~/.config/cursor/settings.json ~/Library/Application\ Support/Cursor/User/settings.json
ln -s ~/.config/cursor/keybindings.json ~/Library/Application\ Support/Cursor/User/keybindings.json
```

## Unset symlink (Reset symlink)

```sh
unlink ~/Library/Application\ Support/Cursor/User/settings.json
unlink ~/Library/Application\ Support/Cursor/User/keybindings.json
```

## Used plugins

#### Appearance
- https://github.com/sainnhe/everforest-vscode
- https://github.com/wraith13/unsaved-files-vscode
- https://github.com/PKief/vscode-material-icon-theme

#### Vim
- https://github.com/VSCodeVim/Vim

#### Other
- https://github.com/usernamehw/vscode-error-lens
- https://github.com/silesky/vscode-toggle-bool
