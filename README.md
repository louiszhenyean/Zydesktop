## ZyDesk
Setup for my Desktop, some configurations for my Desktop themes and shortcuts.  

## My Current Desktop

### With Default Panel
<p align="center">
  <img src="wallpaper/my-panel.png">
</p>

### With Latte Dock
<p align="center">
  <img src="wallpaper/my-latte.png">
</p>

### Personal Shortcuts
Always use easy shortcuts XD
```
sudo ln -s /bin/xdg-open /bin/open
sudo ln -s /bin/python3 /bin/py
sudo ln -s /bin/python3 /bin/python
sudo ln -s /bin/clear /bin/c
sudo ln -s /bin/ranger /bin/r
```

### Keyboard Shortcuts
Sometimes I forgot to setup personal keyboard shortcuts
```
Home folder                         - Ctrl + Alt + F
Launch Web Browser                  - Ctrl + Alt + G
Settings                            - Shift + Ctrl + S
Hide all normal windows             - Disabled
Move to workspace above/below       - Ctrl + Alt + Up / Down
Move window one workspace up/down   - Super + Up / Down
Eject                               - Ctrl + Alt + Backspace
Close window                        - Alt + W
```

### Shell EVERYWHERE!
```
python3 -c 'import pty;pty.spawn("/bin/bash")'
```

### To Clean Up APT Bundles
- https://github.com/davidfoerster/aptsources-cleanup
```
sudo apt install python3-apt python3-regex
chmod a+x aptsources-cleanup.pyz
sudo ./aptsources-cleanup.pyz
```

### Fix VirtualBox Guest Permission
```
sudo adduser $USER vboxsf
```

[Fix DNS issue](https://askubuntu.com/questions/951057/ubuntu-dns-error-chrome-dns-probe-finished-nxdomain-firefox-similar)  
[Fix Dual Boot Wrong Time](https://www.howtogeek.com/323390/how-to-fix-windows-and-linux-showing-different-times-when-dual-booting/)

