# Core
## Registries
- https://gist.github.com/Logerfo/5640d7a3c00f54e703ef8c04b4733381

## Git
```sh
winget install -e --id Git.Git
```
- https://git-scm.com/download/win
```sh
git config --global merge.tool vscode
git config --global mergetool.vscode.cmd 'code --wait $MERGED'
git config --global diff.tool vscode
git config --global difftool.vscode.cmd 'code --wait --diff $LOCAL $REMOTE'
```

## Oh-My-Posh
```sh
winget install JanDeDobbeleer.OhMyPosh -s winget
```
```sh
eval "$(oh-my-posh --init --shell bash --config ~/AppData/Local/Programs/oh-my-posh/themes/logerfo.omp.jsonc)"
```
- https://gist.github.com/Logerfo/78539902addeb12e40e4f031cae35172

## Edge Reflector
- ~~https://github.com/da2x/EdgeDeflector/releases~~
- https://github.com/rcmaehl/MSEdgeRedirect

## Disable Edge Pre-Load
- https://www.wisecleaner.com/how-to/140-how-to-disable-microsoft-edge-pre-launching-in-windows-10.html

## Auto Hotkey
```sh
winget install -e --id Lexikos.AutoHotkey
```
- https://www.autohotkey.com/download/ahk-install.exe
- https://gist.github.com/Logerfo/45d0009ad12f7ccd9015713cc9a60bb9

## 7+ Taskbar Tweaker
- https://rammichael.com/7-taskbar-tweaker

## Shortcuts
- https://winaero.com/blog/change-hotkeys-switch-keyboard-layout-windows-10/

# Theming
## Ultra UX Theme Patcher
- https://www.syssel.net/hoefs/software_uxtheme.php?lang=en

## Penumbra
- https://www.deviantart.com/scope10/art/Penumbra-10-Windows-10-visual-style-568740374

# Visual Applications
## Google Chrome
```sh
winget install -e --id Google.Chrome
```
- https://www.google.com/chrome/
- [Shortcut flags](chrome.txt)

## Visual Studio Code
```sh
winget install -e --id Microsoft.VisualStudioCode
```
- https://aka.ms/win32-x64-user-stable  
- `shan.code-settings-sync`

## Discord
```sh
winget install -e --id Discord.Discord
```
- https://discordapp.com/api/download?platform=win

## GitKraken
```sh
winget install -e --id Axosoft.GitKraken
```
- https://www.gitkraken.com/download/windows64

## Xming
```sh
winget install -e --id Xming.Xming
```
- https://sourceforge.net/projects/xming/files/latest/download
- [Config file](config.xlaunch)

# System Tray
## RBTray
- https://github.com/Logerfo/RBTray/releases

## Crycker
- https://github.com/davidvidmar/Crycker/releases

## Instant Eyedropper
- http://instant-eyedropper.com/
