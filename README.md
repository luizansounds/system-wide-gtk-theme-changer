## gtk4-theme-changer
Theme changer for Libadwaita

### Disclaimer!
Use this script at your own risk!
### How it works?
It just create simlinks between .themes and .config folder with assets and GTK 4.0 theme CSS files.

### Requirements
Theme must be prepared for GTK 4.0.<br/>
In downloaded theme directory should be ``gtk-4.0`` and ``assets`` directories.

### How to use?
1. Download Python script from git:
```
git clone https://github.com/ersanmaz/gtk4-theme-changer.git
```
2. Add run permissions to file:
```
chmod +x theme_changer.py
```
3. Run script:
```
./theme_changer.py
```

### How to reset to default Adwaita theme?
Run script with --reset parameter:
```
./theme_changer.py --reset
```
### Credits
Thanks to [OdzioM](https://github.com/odziom91) for this nice script.
