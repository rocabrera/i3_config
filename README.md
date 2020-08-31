# i3_config

UBUNTU 20.04

# Must install

* urxvt ---> sudo apt install rxvt-unicode

* feh ---> sudo apt-get install feh



# Ricing

* ranger ---> sudo apt install ranger

* gotop --> {

 1. wget https://github.com/cjbassi/gotop/releases/download/3.0.0/gotop_3.0.0_linux_amd64.deb
 
 2. sudo dpkg -i gotop_3.0.0_linux_amd64.deb

  }

* neofetch ---> sudo apt install neofetch


# Config needed


* use this command to set the default terminal:
sudo update-alternatives --set x-terminal-emulator /usr/bin/urxvt

* run: chmod +x .Xresources
* run: chmod +x .xsettingsd


# Other packages
sudo apt-get install compton rxvt-unicode xsel rofi fonts-noto fonts-mplus xsettingsd lxappearance scrot viewnior


* Compton is a compositor to provide some desktop effects like shadow, transparency, fade, and transiton.

* URxvt is a lightweight terminal emulator, part of i3-sensible-terminal.

* Xsel is a program to access X clipboard. We need it to make copy-paste in URxvt available. Hit Alt+C to copy, and Alt+V to paste.

* Rofi is a program launcher, similar with dmenu but with more options.

* Noto Sans and M+ are my favourite fonts used in my configuration.

* Xsettingsd is a simple settings daemon to load fontconfig and some other options. Without this, fonts would look rasterized in some applications.

* LXAppearance is used for changing GTK theme icons, fonts, and some other preferences.

* Scrot is for taking screenshoot. I use it in my configuration for Print Screen button. I set my Print Screen button to take screenshoot using scrot, then automatically open it using Viewnior image viewer. 
