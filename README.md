# My-linux-customization
My Linux customization for everyday use. Also the daily app use.

----------------------
The things I need to do after install ubuntu

* **Update the linux** 
    ```
    sudo apt update && sudo apt upgrade
    ```
* **Install Media codecs**
  ```
  sudo apt install ubuntu-restricted-extras
  ```
* **Use Flatpak in Ubuntu 18.04 to get access to more applications**
  ```
  sudo apt install flatpak
  sudo apt install gnome-software-plugin-flatpak
  flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
  ```
* **Install GNOME Tweaks**
  ```
  sudo apt install gnome-tweak-tool
  ```
* **Installing GNOME Shell Extensions**
  ```
  sudo apt install gnome-shell-extensions
  ```
  then install brower add-on and install native connector

  ```
  sudo apt install chrome-gnome-shell
  ```
  ##Installing dconf-editor
  ```
  sudo apt install dconf-editor
  ```
  ##Install synaptic package manager
  search and istall from app store
  
  
  
## Installing themes 

* using ppa and install pop theme
  ```
  sudo add-apt-repository ppa:system76/pop
  sudo apt-get update
  sudo apt-get install pop-theme
  ```

 But I'm using the ANT Dracular Themes. It's quit good. TO install the themes automatically in our system i'm using OCS-URL

**OCS - URL**
first download the package form official link

[OCS - URL](https://www.pling.com/p/1136805/)

then following steps:
```
cd Downloads/
ls
sudo dpkg -i ocs-url........deb
sudo apt-get -f install
```

**ANT Theme link**
```
https://www.gnome-look.org/p/1099856/
```
**ICONS**
```
https://www.pling.com/p/1284047
```

# Softwares

* **Google Chrome**
  ```
  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

  sudo dpkg -i google-chrome-stable_current_amd64.deb
  ```

* **VS CODE**
  ```
  sudo apt updatesudo apt install software-properties-common apt-transport-https wget

  wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -

  sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"

  sudo apt updatesudo apt install code

  ```
* **GIT**
  ```
  sudo apt update
  sudo apt install git
  ```
* **PyCharm**
  ```
  sudo snap install pycharm-professional --classic
  ```


# Runing windows apps on linux

* **install wine**
  ```
  sudo apt update
  sudo apt install wine
  ```
  to add 32-bit support in the distro
  ```
  sudo dpkg --add-architecture i386
  ```
  **Getting Started with Wine**
  ```
  winecfg
  $HOME/.wine/c_drive
  ```

* **PlayOnLinux**
  ```
  sudo apt install playonlinux
  ```

Additional Information on wine
[How to use windows app on linux](https://itsfoss.com/use-windows-applications-linux/)

