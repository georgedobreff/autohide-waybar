This is a simple script for Hyprland that hides Waybar and shows it when the cursor hits the top edge of the screen (y0).

This was written specifically for Omarchy installations but should work on any system using Hyprland.

### For Omarchy installs

* Place autohide.conf in ~/.config/waybar/

* Place autostart.conf in ~/.config/hypr/

* In the same folder edit hyprland.conf and make sure this line is in there:

```source = ~/.config/hypr/autostart.conf
```

* Reboot
