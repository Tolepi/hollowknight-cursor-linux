# a port of hollow knight cursors
i really loved these hollow knight cursors (since i love hollow knight in general) so i ported them to linux since i couldnt find any

## installation methods (theres only one lmfao)

### 1- zip thing
1. go to the releases section of this repository.
2. download the `HollowKnight-Cursor-Linux.zip` file.
3. extract it into your local icons directory (create the directory if it doesn't exist):
```
mkdir -p ~/.local/share/icons/
unzip HollowKnight-Cursor.zip -d ~/.local/share/icons/
```

how to apply
Via Terminal (GNOME / Compatible Environments):
```
gsettings set org.gnome.desktop.interface cursor-theme 'HollowKnight'
```
Or using graphical tools like lxappearance or nwg-look.
