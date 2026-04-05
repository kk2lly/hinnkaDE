-----------------------------

# Start The Installation:

Before you started, get these pakages:

Arch:
`sudo pacman -S feh openbox xfce4-panel`

Debian:
`sudo apt install feh openbox xfce4-panel`

Fedora:
`sudo dnf install feh openbox xfce4-panel`

(ONLY FOR LINUX USERS)

(whatever you distro on, like Arch, Debian, and Fedora)

# Non-Manual:

Get `install.sh` from [release](https://github.com/kk2lly/hinnkaDE/releases/tag/Shell)

-----------------------------

# Manual:

1: Open the terminal and type:

`git clone https://github.com/kk2lly/hinnkaDE-i3-WM`

Or

`git clone https://github.com/HinnkaStudios-Open-Sources-Project/hinnkaDE-i3-WM`

Once done, type `cd hinnkaDE`

2: Make `hinnkaDE` folder on `/usr/local/bin` like this:

`sudo mkdir /usr/local/bin/hinnkaDE`

Copy the bash script to: `/usr/local/bin/hinnkaDE`

`sudo cp hinnkaDE.sh /usr/local/bin/hinnkaDE`

Make shell file executable:

`sudo chmod +x /usr/local/bin/hinnkaDE/hinnkaDE.sh`

Copy the wallpaper image to: `/usr/local/bin`

`sudo cp Wallpaper.png /usr/local/bin/hinnkaDE`


3: Copy the desktop session file must be to `/usr/share/xsessions`

Before doing that, create `xsessions` like this:

`sudo mkdir /usr/share/xsessions`

Then, type copy the desktop session file:

`sudo cp hinnkaDE.desktop /usr/share/xsessions/`


4: Once done, log out to change desktop session to ''hinnkaDE'' and log back on and done!

NOTE: If you forgot to do `sudo chmod +x /usr/local/bin/hinnkaDE/hinnkaDE.sh` or installing `openbox` and `xfce4-panel`, it may not working




# Previews

Virtual machine:
<img width="1920" height="1080" alt="Screenshot_20260330_132643" src="https://github.com/user-attachments/assets/3048445b-49d3-49a8-aa59-df9b4dae0004" />

-----------------------------

# Changing Wallpaper Without Logging Off And Re-Logging On

Before getting starting, Open the terminal and type:

`rm -rf hinnkaDE`

`git clone https://github.com/kk2lly/hinnkaDE`

Once done, type `cd hinnkaDE`

Overwrite the wallpaper image to: `/usr/local/bin`

`sudo cp Wallpaper.png /usr/local/bin/hinnkaDE`

Overwrite the shell file executable:

`sudo chmod +x /usr/local/bin/hinnkaDE/hinnkaDE.sh`

Execute it

`cd /usr/local/bin/hinnkaDE/`
`./hinnkaDE.sh`

Your done!

Chaning wallpaper without logging off is easy!

If the panel bugged, logoff and re-logon
