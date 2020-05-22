# Install

## Get proper ZSH version Centos 7
wget http://mirror.ghettoforge.org/distributions/gf/el/7/plus/x86_64/zsh-5.1-1.gf.el7.x86_64.rpm\n
rpm -Uvh zsh-5.1-1.gf.el7.x86_64.rpm

## Install "OhMyZSH"
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

## Clone Powerlevel10k as a theme for Zsh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k

## Copy '.xxx' files
Copy files to a $HOME directory

## Install Fonts on SSH client side (optional)
	• MesloLGS NF Regular.ttf
	• MesloLGS NF Bold.ttf
	• MesloLGS NF Italic.ttf
	• MesloLGS NF Bold Italic.ttf
