# Sway-WM Setup and Theme for EndeavourOS

**Sway EndeavourOS Community Edition**

[![Maintenance](https://img.shields.io/maintenance/yes/2025.svg)]()

## To Install Sway

### With the EOS Installer

1. In the live environment, choose "Fetch your install customization file" from the Welcome app.
2. Type or paste the URL for the Sway user_commands.bash file.
```
https://raw.githubusercontent.com/EndeavourOS-Community-Editions/sway/main/setup_sway_isomode.bash
```
![welcome_install-customization-file](https://github.com/user-attachments/assets/b4b9e882-0e53-4e11-be10-a92e5b55cefb)

3. Click <kbd> OK </kbd>, then back in the Welcome app click <kbd> Start the Installer </kbd> and proceed with an online installation. Be sure to choose "no desktop" on the DE selection screen.

![installer-no_desktop](https://github.com/user-attachments/assets/f9146bf2-e0ab-4e0a-9b6a-89ad5eed5a29)


### Manually (Post-Installation)

Alternatively, you can add Sway after the installation is complete by cloning the repo and running the `sway-install.sh` script.

    git clone https://github.com/EndeavourOS-Community-Editions/sway.git

    cd sway

    sudo ./sway-install.sh
    
## Post install

- Keyboard layout in: `~/.config/sway/config.d/input`
- Screen settings in: `~/.config/sway/config.d/output`
- Keybindings Cheatsheet: press keyboard icon in waybar

- If you are experiencing issues with your cursor, edit `/etc/greetd/regreet.toml` and uncomment `WLR_NO_HARDWARE_CURSORS = "1"`
 
## Get involved at our forum:
https://forum.endeavouros.com/t/sway-edition-general-conversation

## Tutorial for sway-wm settings:

 - Background handled by Azote
 - Filebrowser = Thunar
 - Default Terminal-Emulator = Foot
 - Text-Editor = xed/nano
 - Bar = Waybar
 - Sound = Pulseaudio

Keyboard shortcuts:

<kbd>Mod</kbd> key is set to the Super/Windows/Command key

 - <kbd>Mod</kbd>+<kbd>Return</kbd> = Open terminal (Foot)
 - <kbd>Mod</kbd>+<kbd>O</kbd> = Open Browser (Firefox)
 - <kbd>Mod</kbd>+<kbd>N</kbd> = Open File Manager (Thunar)
 - <kbd>Mod</kbd>+<kbd>D</kbd>= App launcher (Fuzzel)
 - <kbd>Mod</kbd>+<kbd>Shift</kbd>+<kbd>D</kbd>= App menu (nwg-drawer)
 - <kbd>Mod</kbd>+<kbd>Q</kbd> = Close focused app [kill]
 - <kbd>PrtSc</kbd> = Snip a screenshot
 - <kbd>Ctrl</kbd>+<kbd>PrtSc</kbd> = Screenshot a window
 - <kbd>Shift</kbd>+<kbd>PrtSc</kbd> = Screenshot the display
 - <kbd>Mod</kbd>+<kbd>Shift</kbd>+<kbd>E</kbd> = Power menu
 - <kbd>Ctrl</kbd>+<kbd>Mod</kbd>+<kbd>↑ ↓ → ←</kbd> = Resize window
 - <kbd>Mod</kbd>+ right click = Resize window
 - <kbd>Mod</kbd>+<kbd>Shift</kbd>+<kbd>Space</kbd> = Float window
 - <kbd>Mod</kbd>+<kbd>Shift</kbd>+<kbd>↑ ↓ → ←</kbd> = Move window
 - <kbd>Mod</kbd>+ left click = Move window
 - <kbd>Mod</kbd>+<kbd>↑ ↓ → ←</kbd> = Switch focused window
 - <kbd>Mod</kbd>+<kbd>Shift</kbd>+<kbd>-</kbd> = Send to scratchpad
 - <kbd>Mod</kbd>+<kbd>-</kbd> = Cycle through scratchpad

See also a keybinding cheatsheet when you click the keyboard icon in the Waybar.
 

## Tiling:

Windows are set to tile by default in Sway. This can be changed to:

- stacking: Only the focused window in the container is displayed. You get a list of windows at the top of the container. 
   - <kbd>Mod</kbd>+<kbd>S</kbd> = Vertical List
   - <kbd>Mod</kbd>+<kbd>W</kbd> = Horizontal List
     - navigate lists with <kbd>Mod</kbd>+<kbd>↑ ↓ → ←</kbd> 
   - <kbd>Mod</kbd>+<kbd>E</kbd> = Back to tiling
   
![sway](https://github.com/user-attachments/assets/9f4bbdac-e478-4918-bdac-da4d83cece42)

Fuzzel:
![fuzzel](https://github.com/user-attachments/assets/fa4d38ba-abcd-4cd9-af9b-4ef6f678b594)

Waybar:
![waybar](https://github.com/user-attachments/assets/6a4cc6f0-95dc-4a47-a6f9-7c5f853b9b70)

