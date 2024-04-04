# Environment Setup

## Terminal

```shell
git config --global credential.helper store  
git config --global user.email "<email>"  
git config --global user.name "Jem Gunay"  
git config --global color.ui auto
```

### zsh

- oh-my-zsh - set your theme with this  
- https://github.com/zsh-users/zsh-syntax-highlighting  
- https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md  

### tmux

- set .tmux.conf to use zsh instead of bash  
- `chmod 755 ~/.tmux`
- tmux plugin manager (TPM)  
- tmux continuum (persist tmux sessions)  
- tmux resurrect (auto load session on tmux startup)  
- tmux-cpu (cpu in corner)  
- tmux-sensible (standardised tmux enhancements)  

### Term colours

- set terminal colour schemes: https://github.com/Mayccoll/Gogh  
- terminal > edit > colors > set background transparency  
- terminal > edit > text > font size 10  
 
## MacOS

- Install homebrew
- Enable backspace word deletion: https://stackoverflow.com/questions/327664/mac-os-x-terminal-map-optiondelete-to-backward-delete-word
- Preferences -> Keyboard -> Key Repeat + Delay Until Repeat (max out to the right) 
- Desktop & Dock -> Mission Control -> Disable "Automatically rearrange Spaces ..."
- Show hidden files: Open the Finder and press `Command + Shift + .`
 
## Apps/Tools

- Go
  - https://go.dev/doc/install
  - Add `~/go/bin` to `PATH` var
  - `golangci-lint`: [https://staticcheck.io/docs/getting-started/](https://golangci-lint.run/usage/install/#local-installation)
  - AIR (live reloads): https://github.com/cosmtrek/air
- Editors
  - Goland/JetBrains Toolbox
    - Disable code folding  
    - Refine import ordering settings  
    - Plugins: Material Theme UI (Arc Dark), Material Theme Icons, GitToolBox  
  - VSCode
- General Tools
  - Update `git`
  - `brew install bat htop tree jq tldr kcat`
  - `brew install kubectl k9s` (k8s tools)
  - `gcloud` & `aws` (CSP tools)
  - `psql`/`cqlsh` (DB tools)
  - NPM
  - Docker Desktop/Docker compose
  - Postman
  - Obsidian
  - ngrok
