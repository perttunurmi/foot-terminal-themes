# foot-terminal-themes
Themes for foot terminal

<h1> How to install </h1>

You can copy the file content straight to your foot.ini or install them to 
/usr/share/foot/themes which will keep your ini file cleaner.

the ini file should be ~/.config/foot/foot.ini

if the file does not exist you can copy a template from /etc/xdg/foot/foot.ini
```
mkdir ~/.config/foot/foot.ini
cp /etc/xdg/foot/foot.ini ~/.config/foot/foot.ini
```

<h3> installing to foot/themes <h3>

1. Create folder /usr/share/foot/themes

2. Copy your chosen the to
```
/user/share/foot/themes/name-of-theme
```
3. Put this into the ini file but remember to rename the file!
```
[main]
include=/usr/share/foot/themes/name-of-theme
```
