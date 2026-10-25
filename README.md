# a port of hollow knight cursors
i really loved these hollow knight cursors (since i love hollow knight in general) so i ported them to linux since i couldnt find any

## installation methods

### 1- zip thing
1. go to the releases section of this repository.
2. download the `HollowKnight-Cursor-Linux.zip` file.
3. extract it into your local icons directory (create the directory if it doesn't exist):
```
mkdir -p ~/.local/share/icons/
unzip HollowKnight-Cursor.zip -d ~/.local/share/icons/
```

### 2- manual clone (i personally do this one)

If you prefer to clone the repository directly:
Bash
```
git clone https://github.com/Tolepi/hollowknight-cursor-linux ~/.local/share/icons/HollowKnight
```
how to apply
Via Terminal (GNOME / Compatible Environments):
```
gsettings set org.gnome.desktop.interface cursor-theme 'HollowKnight'
```
Or using graphical tools like lxappearance or nwg-look.
