# Ubuntu dotfiles &nbsp; <img src="Images/ubuntu.png" width="30">
These dotfiles are used to set up Ubuntu-GNOME systems (you can slightly modify some commands to adapt it to any Debian-based distribution). To run the setup, simply run the commands:

```ssh
# Clone the repository
git clone https://github.com/DanieleBertagnoli/LinuxDotfiles
cd LinuxDotfiles

# Make the script executable
sudo chmod +x Ubuntu/install.sh

# Run the script
./Ubuntu/install.sh
```

## Select Themes

This step can be automatically done through the script, however if you don't like the installed themes, you can manually change them through this step. Open *Gnome Tweaks* and select from the left menu: "Appearance". 
Now you can select the theme for each element in the list:
- Applications: `/usr/share/themes`
- Cursor: `/usr/share/icons`
- Icons: `/usr/share/icons`
- Shell: `/usr/share/themes`

If you want to add more themes, just download them from [Gnome Look Official Website](https://www.gnome-look.org/) and place the elements in the right folder as indicated in the list. 

## Wallpapers

We also ship a set of wallpapers that will be copied into `~/Pictures/Wallpapers`. 
