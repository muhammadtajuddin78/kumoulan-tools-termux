# termux-tools
#### This is unofficial repository for termux 

### List Of Available Packages (Aarch64)
1. hping3
2. libdbus
3. libdbus-glib
4. libgtk2
5. libvte
6. libxfce4ui
7. libxfce4util
8. libxfconf
9. libxml-parser-perl
10. wireless-tools
11. wireshark
12. xfce4-terminal
13. Thunar
14. libexo

### List Of Available Packages (arm)
1. wireless-tools
2. wireshark

### List Of Available Packages (for all platforms)
1. beef-xss
2. intltool
3. xerosploit

#### How To Add My Repo In Sources.list File
1. For AARCH64 Add new sources list file `mkdir -p $PREFIX/etc/apt/sources.list.d && printf "deb [trusted=yes arch=all,aarch64] https://hax4us.github.io/termux-tools/ termux extras" > $PREFIX/etc/apt/sources.list.d/hax4us.list` and if you have **ARMHF/ARMV7 OR ARM 32BIT DEVICE** so you can add this `mkdir -p $PREFIX/etc/apt/sources.list.d && printf "deb [trusted=yes arch=all,arm] https://hax4us.github.io/termux-tools/ termux extras" > $PREFIX/etc/apt/sources.list.d/hax4us.list`
2. Update `apt update`

#### Inatall Any Package 
`apt install pkg_name`

#### Packages Will Be Add As Per Your Demand Guys :) (Just Open Issue As A Package Request)



