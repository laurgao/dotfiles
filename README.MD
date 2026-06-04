To edit bashrc:

```sh
vim ~/.bashrc
source ~/.bashrc # reloads it and allows you to use the new changes immediately
cp ~/.bashrc dotfiles/.bashrc # copy it to the dotfiles repo
```

To make caps lock an additional escape key:

```sh
sudo apt install gnome-tweaks
gnome-tweaks
```

Then, do Keyboard & Mouse > Additional Layout Options > Caps Lock behavior > Make Caps Lock an additional Esc
