# Linux-Catppuccin-Theme

![img](https://github.com/devcui/Linux-Catppuccin-Theme/blob/main/docs/screenshot.png)

# Install

## 1. Update your system

```bash
sudo apt update
sudo apt upgrade
```
- open `System Settings` -> `Desktop Settings`,choose `Desktop Layout` to `No desktop icons`

# 2. Installing nautilus file manager

```bash
sudo apt install nautilus nautilus-admin nautilus-extension-gnome-terminal
```

- open `System Settings` -> `Preferred Applications`, choose default file manager to `nautilus file manager(named files)`

- open `windows` -> `behavior` and set `Location of newly opened windows` to `center`

# 3. Installing GTK theme

```bash
mv -f themes ~/.themes
```

# 4. Installing icon and start menu icons

```bash
mv -f icons ~/.local/share
mv -f start-menu-icon ~/.local/share/icons
```

# 5. Installing cursors

```bash
mv -f cursors ~/.icons
```

# 6. Installing fonts and wallpapers

```bash
mv -f fonts ~/.local/share
sudo mv -f wallpapers /usr/share/backgrounds
```

# 7. 





# Original author

- Youtube: https://youtu.be/AnNx-Se9wkc
- Resources: https://www.pling.com/p/2033080/
- Kofi: https://ko-fi.com/s/99f7e73685
