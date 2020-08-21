## xfce4-terminal  
  
DESCRIBE  
  
requires:    
```
apt install xfce4-terminal
```  
```
yum install xfce4-terminal
```  
```
pacman -S xfce4-terminal
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/xfce4-terminal/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/xfce4/terminal" "$HOME/.config/xfce4-terminal.bak"
git clone https://github.com/dfmgr/xfce4-terminal "$HOME/.config/xfce4/terminal"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/NAME" target="_blank">xfce4-terminal wiki</a>  |  
  <a href="NAME" target="_blank">xfce4-terminal site</a>
</p>  
