# Zathura configuration

Zathura is available in `apt` so to install just run 

```shell
sudo apt-get update
sudo apt-get install zathura
```

Zathura supports viewing different file formats via plugins, see [Zathura wiki](https://wiki.archlinux.org/title/Zathura) for more information. Luckily, the Poppler plugin should be included by default when installing Zathura on (newer) Ubuntu. 

To make Zathura the default PDF viewer, check first that `/usr/share/applications/org.pwmt.zathura.desktop` exists after installation. Then, run 

```shell
xdg-mime default org.pwmt.zathura.desktop application/pdf
```

To configure the software, clone this repo to your configuration directory via 

```shell
cd ~/.config
git clone git@github.com:vohonen/zathurarc.git zathura
```
