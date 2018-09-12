# Aperture OS

This repository will contain the configuration files, the wallpaper and other miscelaneous things that'll allow you to rice your distro like [mine](https://www.reddit.com/r/unixporn/comments/9er5t0/i3gaps_arch_my_first_rice_super_excited_aperture/).

# How to install

Assuming you're on Linux, and assuming you have brain cells, copy each config into the corresponding file.
Example: `cat compton.conf > ~/.config/compton.conf`

Remember to make backups in case of problems.

# Neofetch Custom ASCII

To use the custom ascii file `aperture.txt` do the following:

```bash
neofetch --ascii aperture.txt
```

# Info

- OS: ArchLinux
- WM: i3-gaps
- Bar: polybar
- Terminal: termite
- Compositor: compton
- Font: Verdana
- Audio: alsa
- Launcher: rofi
- Screenshot Utility: maim
- System Info Gen: neofetch

# Warning

I didn't remove all commands from my packages inside the configs. You might be missing some packages. Make backups!
The i3 config contains a shortcut (Mod1+Shift+P) to take a screenshot with maim

