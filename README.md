![archlive_logo](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Archlive.png) <br />

# Introduction

Yeah, the weekend was pretty borring... So i grabbed the arch iso and started doing... my stuff. <br />
As Result, i'm writing here the intro, like exactly what happend... i ended up creating a Arch based custom live linux distro, which is really awesome... (just appreciating myself 😜) <br />

Here's how it looks... [familiar](https://github.com/adi1090x/my_dotfiles/tree/master/previews/i3_wm), Right?... YES! But Now in an ISO, Live, For Everyone. <br />

![preview](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Head.png) <br />

So, This custom iso is based on latest [arch linux](https://archlinux.org), Ofcourse... Here's a list of all features i've added...

## Features

**1** : Latest December 17, 2018 updated <br />
**2** : Boots to desktop in just 20 seconds <br />
**3** : Plymouth installed / Arch-charge theme<br />
**4** : xorg/xserver installed <br />
**5** : lightdm/[lightdm-mini-greeter](https://github.com/prikhi/lightdm-mini-greeter) as Display Manager <br />
**6** : i3-gaps (highly configured, as can be seen) Window Manager <br />
**7** : [Polybar](https://github.com/jaagr/polybar) as Panel <br />
**8** : Compton as Compositing Manager <br />
**9** : [Rofi](https://github.com/DaveDavenport/rofi) For Menus & Networks <br />
**10** : Network Manager with [networkmanager_dmenu](https://github.com/firecat53/networkmanager-dmenu) installed and configured <br />
**11** : [yay](https://github.com/Jguer/yay) installed for AUR packages <br />
**12** : zsh with [ohmyzsh](https://github.com/robbyrussell/oh-my-zsh) latest <br />
**13** : vim with [vim_runtime](https://github.com/amix/vimrc) latest <br />
**14** : [eDEX-UI](https://github.com/GitSquared/edex-ui) Added <br />
**15** : Latest firefox for web browsing <br />
**16** : Full audio support with pulseaudio/alsa <br />
**17** : mpd, mpc, ncmpcpp, mplayer for media services (configured, ncmpcpp with album art support) <br />
**18** : termite, urxvt(compiled with pixbuf), xfce4-terminal as terminals <br />
**19** : Thunar, Geany, Evince, file-roller, etc graphical apps <br />
**20** : Full Notifications support with dunst <br />
**21** : Basic Programs like... vim, ranger, mc/mcedit, htop, gtop, bmon, nmon, neofetch... etc-etc <br />
**22** : Many More... I Don't even remember now, Just Try It Yourself... <br />

# Download

![download](https://raw.githubusercontent.com/adi1090x/archlive/master/images/download.png) <br />

# TOUR

**Appearance Overview**

- Gtk Theme : [Adapta-Nokto-Eta](https://github.com/adapta-project/adapta-gtk-theme) <br />
- Icon Pack : [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) <br />
- Bars : [Polybar](https://github.com/jaagr/polybar) <br />
- Fonts : [Siji](https://github.com/stark/siji) & Termsyn <br />
- Wallpaper : [Dark-Material](https://github.com/adi1090x/my_dotfiles/blob/master/.backgrounds/dark_material.png) <br />


**Desktop** : That's the default desktop. it's i3-gaps WM with polybar and compton as compositing manager. <br />

*Polybar - TOP >* Arch icon (menu), i3-Workspace, skippy-xd, keyboard, battery, volume, network, clock, powermenu. <br />
*Polybar - BOTTOM >* mpd, filesystem, cpu, memory, temperature, updates, net-speed, ssid, volume & brightness bar. <br />

![Desktop](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Desktop.png) <br />

**Menu** : There are tow type of menu, each with rofi... One With Icons, Other one is normal. both can be access with left click and  right click respectively on arch icon on polybar. Windows or Meta key is default Mod key of i3, so both can be access with M+d & M+S+d respectively with keyboard. please read the i3 config file for keybindings, there are a lot.

![Rofi_icon](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Rofi_Icon.png) <br />

![Rofi_list](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Rofi_List.png) <br />

**Web Browser** : Like many other linux distros, firefox is the default browser. 

![Web](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Web.png) <br />

**Media** : Running Mplayer, mpd/ncmpcpp with album art support. 

![Media](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Media.png) <br />

**File Manager** : Running Thunar and Geany. 

![FM](https://raw.githubusercontent.com/adi1090x/archlive/master/images/FM.png) <br />

**vim & mcedit** : vim editor with vim_runtime configs & mcedit.

![Docs](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Docs.png) <br />

**Notifications** : Dunst for notifications, volume & brightness notifications. 

![Dunst](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Dunst_Vol.png) <br />

![Dunst-alt](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Dunst_BL.png) <br />

**eDEX_UI** : i love sci-fi stuff & that's a good one. so i included it in the iso with it's own workspace.

![eDEX_UI_W](https://raw.githubusercontent.com/adi1090x/archlive/master/images/eDEX_W.png) <br />

![eDEX_UI](https://raw.githubusercontent.com/adi1090x/archlive/master/images/eDEX.png) <br />

**Networks** : networkmanager_dmenu for wifi and earthnet connections, configured. 

![Net](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Net.png) <br />

**Monitor** : htop, gtop, nmon, bmon, etc programs for monitoring processes and other stuff with own workspace. 

![Mon](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Mon.png) <br />

**Power Menu** : Just Simple Power menu, i3-lock-fancy as lockscreen.

![System](https://raw.githubusercontent.com/adi1090x/archlive/master/images/System.png) <br />

**i3 Tiling** : i3 tiling with gaps, programs - vim, ranger, cmatrix, pipes. 

![Tile](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Tiles.png) <br />

**Lab Workspace** : Just Stuff, tux, nmon, bmon

![Lab](https://raw.githubusercontent.com/adi1090x/archlive/master/images/Lab_1.png) <br />

**TTY Workspace** : Terminals - neofetch, cmatrix, pipes, color_panes, htop, gtop 

![](https://raw.githubusercontent.com/adi1090x/archlive/master/images/TTY.png) <br />

**More Screenshots** : [Here](https://github.com/adi1090x/my_dotfiles/tree/master/previews/i3_wm), Like What else you can make it, Like Mine Old Portable Hacking Machine, LOL! 

## Naming My OS

Such A Pain __ __ #@$$... So, first i though - "ARCH3", coz it's arch and use i3 as WM... NO!!! coz i is missing... <br />

Alright, How about - "Archy", Coz arch+i = archy... NO!!! Weird. <br />

Whatever... it's just *"ARCHLIVE"* <br />

## Few Points

- As it says *"LIVE"*... which means it can only run live (at least for now) coz i did not made any installer for it yet. <br />
- You need to read the i3 configs to fully operate it, like keybindings, windows tiling, etc. <br />
- You may need to modify polybar configs, like The BAT0 to BAT1 / wlan0 to wlp3s0... stuff like that. <br />
- I built it on a machine with intel pentium cpu & intel HD gpu so it have the intel video drivers. <br />
- There is only one person behind all this- ME, So appreciate it. it maybe not perfect or may not run on your machine. <br />
- This OS may not be for people who are beginners to linux, however i tried my best to make it simple and easy. <br />
- Well, That's it for now... try it, have fun. <br />
