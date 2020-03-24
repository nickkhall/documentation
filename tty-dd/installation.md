# Ubuntu Server 18.04 TTY Daily Driver Installation Setup

## Steps
----
1. Install ubuntu server iso

2. Flash iso to usb drive

3. Install operation system

### After Internet is figured out...

4. ### Software
----
#### 4.1: tmux
##### - install tmux if not installed : `sudo apt install tmux`
##### - get .tmux.conf from tty-dd and add to ~/

#### 4.2: i3
##### - install i3 : `sudo apt install i3`
##### - get .config/ dir from tty-dd and add to ~/

#### 4.4: zsh
##### - install zsh : `sudo apt install zsh`
##### - get .zshrc from tty-dd and add to ~/

#### 4.5: xinit
##### - install xinit : `sudo apt install xinit`
##### - get .xinitrc from tty-dd and add to ~/
##### - get .Xdefaults from tty-dd and add to ~/

#### 4.6: rofi
##### - install rofi : `sudo apt install rofi`

5. ### Daily Setup
##### - get .bash_profile from tty-dd and add to ~/

##### - change your shell to bash
#####		- `chsh` --> '/bin/bash'

##### - set Vim as default
#####   - `export VISUAL=vim`
####    - `export EDITOR="$VISUAL"`

##### - set up font
#####   - get .fonts from tty-dd and add to ~/

##### - install browser
#####   - install chromium first : `sudo apt install chromium-browser`
#####   - after installing chrome, use chrome to install firefox dev
#####   - tar -xvjf .tar.b2z
#####   - move firefox/firefox executable to /usr/bin (PATH)
#####   - when running firefox, run as daemon `firefox&`

6. ### Extras

#### Sound
----
##### ALSA
#####  - `sudo apt install alsa alsa-tools`
