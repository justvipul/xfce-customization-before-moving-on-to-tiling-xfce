# **Things to do**


make two folders in home directory
`.icons` and `.themes`
```
mkdir ~/.icons ~/.themes
```
#### however, a small note,
if you want the themes and icons to apply everywhere in the system. to every application that requires root privilage then you should copy themes and icons respectively to 
`/usr/share/themes and /usr/share/icons`.
#### ok then,
add your favourite gtk themes and window manager to .themes folders
and add your favourite icons and cursor's icons to .icons folder.

some useful links for theme content install any one of cursor, gtk and icon theme atleast

## gtk3 themes and window manager themes

[ Yaru-Colors ](https://www.xfce-look.org/p/1299514/) | 
[McMojave](https://www.xfce-look.org/p/1275087/) | 
[Nordic](https://www.xfce-look.org/p/1267246/) | 
[xfwm4 gaps themes](https://github.com/addy-dclxvi/xfwm4-theme-collections) | 
[orchis themes easy install](https://github.com/vinceliuice/Orchis-theme) | 
[gaps xfwm themes](https://www.xfce-look.org/p/1174081/) | 
[another gaps theme](https://www.xfce-look.org/p/1230476/) | 

## cursors and icons
[vimix cursors](https://www.xfce-look.org/p/1358330/) | 
[Capitaine Cursors ](https://www.xfce-look.org/p/1148692/) | 
[Flatery ](https://www.xfce-look.org/s/XFCE/p/1332404) | 
[Qogir icon theme ](https://www.xfce-look.org/s/XFCE/p/1296407)| 
[Papirus](https://www.xfce-look.org/s/XFCE/p/1166289) | 
 
### a complete tutorial to customise xfce in a specific way
https://www.youtube.com/watch?v=oQ8RWtD3MTQ
 
### xfce customization by a friend of mine, its a long video though ;p
https://www.youtube.com/watch?v=eQQ0d57iVnU

## question 1. how do i get the dope shadows below the panel?
i use compton for that. get shadows for docks as true and shadow radius more than 10 and shadow opacity as whatever you want. i have added my compton.conf for reference. 
#### you have to disable xfwm compositor 
![disabled_compositor](/uploads/6116c373c5b64d409fe3e5bfdea5696d/disabled_compositor.png)

## question 2. how do i make compton work like normal?
add 
`bash -c "sleep 5; exec compton -b"`
#### **note: if you want fading with compton use `bash -c "sleep 5; exec compton -b -f"` instead. and if you want blur use this fork of compton made by an awesome guy, [ComptonWithCapitalC](https://github.com/Aeres-u99/ComptonWithCapitalC)



## not completely necessary. 

I have included  starship.rs prompt's config file aka starship.toml.
to install starship prompt,type in terminal
```
sudo apt update && sudo apt upgrade
```
```
sudo apt install aptitude tasksel curl
```
```
sudo aptitude install  fonts-noto-color-emoji fonts-symbola ttf-ancient-fonts-symbola fonts-powerline 

```
```
curl -fsSL https://starship.rs/install.sh | bash

```
copy this line to your .bashrc file which is a text file in your home directory. it is generally hidden type `ctrl+h` to make it visible

```
eval "$(starship init bash)"

```
```
source ~/.bashrc
```
then copy the starship.toml file in `.config` directory


## my xfce rice looks like this, 

![xfce-after-customization](/uploads/f47fd9005004b8a49d05198b8a4ef331/xfce-after-customization.png)











