# Environment Setup

## Dotfiles & Terminal

git config --global credential.helper store  
git config --global user.email "<email>"  
git config --global user.name "Jemil Gunay"  
git config --global color.ui auto  

zsh (yum)  
oh-my-zsh - set your theme with this  
https://github.com/zsh-users/zsh-syntax-highlighting  
https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md  

set .tmux.conf to use zsh instead of bash  
chmod 755 ~/.tmux  
tmux plugin manager (TPM)  
tmux continuum (persist tmux sessions)  
tmux resurrect (auto load session on tmux startup)  
tmux-cpu (cpu in corner)  
tmux-sensible (standardised tmux enhancements)  

set terminal colour schemes: https://github.com/Mayccoll/Gogh  
terminal > edit > colors > set background transparency  
terminal > edit > text > font size 10  

## Apps

* Goland (JetBrains Toolbox)  
  * Disable code folding  
  * Refine import ordering settings  
  * Plugins: Material Theme UI, Material Theme Icons, GitToolBox  
* VSCode  
* Update git 
* Install jq: https://stedolan.github.io/jq/
