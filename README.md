<p align="center">
  <img src="https://github.com/user-attachments/assets/40e0d134-35cc-40a5-a55a-242d96d037df" style="width: 128px; height:128px"/>
</p>

# Mintows-Theme
A simple GTK theme made originally for Linux Mint by combining Adwaita and Graphite.  

To install just download the repository and put one of the theme variants in `~/.themes`.

## Notes
Currently the theme doesn't change the colors of Cinnamon apps like Calculator or Screenshot due to Adwaita not generating the colours for Cinnamon specifically.

Here is some css for improved desktop font shadows on brighter wallpapers. Just put at the end of `~/.config/gtk-3.0/gtk.css` the css code.
```css
.nemo-desktop.nemo-canvas-item {
    color: #fff;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 1),
                 1px 1px 2px rgba(0, 0, 0, 1),
                 0px 0px 2px rgba(0, 0, 0, 1),
                 0px 0px 3px rgba(0, 0, 0, 1);
}

.nemo-desktop.nemo-canvas-item:selected {
    color: #fff;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.85);
    box-shadow: none;
}

.nemo-desktop.nemo-canvas-item:hover {
    text-shadow: 1px 1px 0px rgba(0, 0, 0, 0.85);
}
```
![image](https://github.com/user-attachments/assets/3a04d3f6-923f-43d2-9fb4-0322c5bca4cb)

## Images
![image](https://github.com/user-attachments/assets/7d40e79a-b468-4890-8b92-bcdc1fa380f5)

![image](https://github.com/user-attachments/assets/3c143177-75d2-44dd-b80a-8f1e9c34ea81)

![image](https://github.com/user-attachments/assets/9d496e30-9eec-4f45-8de5-c7a5e490a02b)

![image](https://github.com/user-attachments/assets/7eac57e8-8e64-4429-b16f-8dc5630a1433)
