# Welcome to the dotFiles wiki!

Simple and easy to use basic configurations for [iTerm2](https://www.iterm2.com/) and [Oh My Zsh](https://ohmyz.sh/) on MacOS. 

## 1. Install Homebrew. 
    
    `$ /usr/bin/ruby -e “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

## 2. Install Oh my Zsh
    
    `sh -c “$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)”`
    
    ### Set ZSH default Mac terminal
    * Open Apple > System Preferences > User& Groups
    * Input Admin Password to unlock settings Right Click an our User in Advanced Options
    * In Login shall choose /bin/zsh and click OK
    * Restart Mac and open iterm2 again.

## 3. Install iTerm2 

   Download iTerm2 on https://www.iterm2.com.

### Configure color pallets. (material-design-colors.itermcolors file attached to this repo)

   1. Open terminal and paste.
   
      `cd Downloads`
      
      `curl -O https://raw.githubusercontent.com/MartinSeeler/iterm2-material-design/master/material-design-colors.itermcolors`
      
   1. Open iTerm2 that we already downloaded at the first section
   1. Go to iTerm2 > Preferences > Profiles > Colors Tab
   1. Click Color Presets… at the bottom right
   1. Click Import…
   1. Select the material-design-colors.itermcolors file
   1. Select the material-design-colors from Load Presets…

## 4. Install PowerLevel9k!

Then it’s time to install PowerLevel9k using the OMZ way!

`$ git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

PowerLevel9k on Github

Then we set it on $HOME/.zshrc. Open a text editor and set:

`ZSH_THEME="powerlevel9k/powerlevel9k"`

