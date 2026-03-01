# SwayFX-VOID-dot
SwayFX on VOID linux
Deps:
``` 
sudo xbps-install -Syu void-repo-multilib void-repo-multilib-nonfree 
sudo xbps-install -Syu swayfx rofi alacritty grim xdg-desktop-portal xdg-desktop-portal-wlr swaykbdd waybar
```
FONT: https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/JetBrainsMono.zip 

extract to ~/.local/share/fonts   ^^^

Wallpaper: https://github.com/franckey02/SwayFX-VOID-dot/blob/e69094c0c85d8a149426d146411c70440b5fdeb6/1385178.png 
put this file in your picture folder ^^^

Rofi:```git clone https://github.com/dracula/rofi && cp rofi/theme/config1.rasi ~/.config/rofi/config.rasi```

GTK: https://github.com/dracula/gtk/archive/master.zip
Extract the .zip file to the themes directory i.e. /usr/share/themes/ or ~/.themes/ (create it if necessary)
``` gsettings set org.gnome.desktop.interface gtk-theme "Dracula" gsettings set org.gnome.desktop.wm.preferences theme "Dracula" ``` 

For the latest versions of Gnome using Gtk4(libadwaita) some extra steps should be done in order to get it working properly, you could do it in two ways:
 Manual way
 
    Copy the assets folder to the ~/.config directory
    Copy the gtk-4.0/gtk.css and gtk-4.0/gtk-dark.css files to ~/.config/gtk-4.0/

Icon Theme:
https://github.com/dracula/gtk/files/5214870/Dracula.zip
extract the .zip file to the icons directory i.e. /usr/share/icons/ or ~/.icons/ (create it if necessary).
gsettings set org.gnome.desktop.interface icon-theme "Dracula" 
NOTE: CHANGE USERNAME IN CONFIG FILE OF SWAY
<img width="1280" height="768" alt="20260301_01h42m06s_grim" src="https://github.com/user-attachments/assets/744c0604-5dcf-431d-b921-f9badeb9b955" />

<img width="1280" height="768" alt="20260301_01h42m24s_grim" src="https://github.com/user-attachments/assets/aa7dd456-8de8-48eb-9226-04260f3f09ef" />
