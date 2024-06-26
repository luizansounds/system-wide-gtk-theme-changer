# gtk4-theme-changer

Theme changer for gtk4, including Libadwaita, and flatpaks

## Disclaimer

Use this script at your own risk! it requires sudo to change themes for flatpaks

## How it works?

It creates simlinks between /usr/share/themes and .config folder with assets and GTK 4.0 theme CSS files and applies chosen theme, Also it enables the ~/.themes folder for flatpaks, them uses override theme to enable the selected theme.

## Requirements

Theme must be prepared for GTK 4.0.
In downloaded theme directory should be ``gtk-4.0`` and ``assets`` directories.

## How to use?

1. Download Python script from git:

```bash
git clone https://github.com/luizansounds/system-wide-gtk-theme-changer
```

1. Add run permissions to file:

```bash
chmod +x theme_changer.py
```

1. Run script:

```bash
./theme_changer.py
```

## How to reset to default Adwaita theme?

Run script with --reset parameter:

```bash
./theme_changer.py --reset
```

## single line install for ~/.local/bin folder

```bash
wget -P ~/.local/bin https://raw.githubusercontent.com/luizansounds/system-wide-gtk-theme-changer/main/theme_changer.py && chmod +x ~/.local/bin/theme_changer.py
```

## Credits

Base script is from [libadwaita-theme-changer](https://github.com/odziom91/libadwaita-theme-changer) repo. Thanks to [OdzioM](https://github.com/odziom91) for that.
Also Thanks to [ersanmaz](https://github.com/ersanmaz) for providing the Fork that Changes the gnome themes in [gtk4-theme-changer](https://github.com/ersanmaz/gtk4-theme-changer)

