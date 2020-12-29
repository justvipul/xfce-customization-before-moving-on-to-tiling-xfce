make two folders in home directory
`.icons` and `.themes`
```
mkdir ~/.icons ~/.themes
```
add your favourite gtk themes and window manager to .themes folders
and add your favourite icons and cursos icons to .icons folder.

some useful links for theme content install any one of cursor, gtk and icon theme atleast
gtk3 themes and window manager themes

[ Yaru-Colors ](https://www.xfce-look.org/p/1299514/) | 
[McMojave](https://www.xfce-look.org/p/1275087/) | 
[Nordic](https://www.xfce-look.org/p/1267246/) | 
[xfwm4 gaps themes](https://github.com/addy-dclxvi/xfwm4-theme-collections) | 
[orchis themes easy install](https://github.com/vinceliuice/Orchis-theme) | 
[gaps xfwm themes](https://www.xfce-look.org/p/1174081/) | 
[another gaps theme](https://www.xfce-look.org/p/1230476/) | 

cursors and icons
[vimix cursors](https://www.xfce-look.org/p/1358330/) | 
[Capitaine Cursors ](https://www.xfce-look.org/p/1148692/) | 
[Flatery ](https://www.xfce-look.org/s/XFCE/p/1332404) | 
[Qogir icon theme ](https://www.xfce-look.org/s/XFCE/p/1296407)| 
[Papirus](https://www.xfce-look.org/s/XFCE/p/1166289) | 
 
a complete tutorial to customise xfce in a specific way
https://www.youtube.com/watch?v=oQ8RWtD3MTQ
 
xfce customization by a frien of mine, its a long video though ;p
https://www.youtube.com/watch?v=eQQ0d57iVnU
the terminal i prefer is xfce4-terminal.
i have included files for terminal aesthetics, namely panes ascii art and starship.rs prompt.
to install starship prompt,type in terminal
```
sudo apt update && sudo apt upgrade
```
```
sudo apt install aptitude tasksel
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
then copy the starship.toml file in `.config` folder
```











