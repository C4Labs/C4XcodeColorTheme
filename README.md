# C4 Xcode Color Theme

A custom C4-colored theme for Xcode.

![preview](preview.png)


## Installation

### Using Git

Use this method if you want to keep up to date with changes.

```shell
git clone https://github.com/C4Framework/C4XcodeColorTheme
cd C4XcodeColorTheme
mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
cp C4.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
```

After executing these commands restart Xcode, go to preferences and select the C4 theme.

To update to the latest version:

```shell
cd C4XcodeColorTheme
git pull
cp C4.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

### Manually

1. Download [the .zip file](https://github.com/C4Framework/C4XcodeColorTheme/archive/master.zip).
2. Create the themes folder: `~/Library/Developer/Xcode/UserData/FontAndColorThemes/`.
3. Move `C4.dvtcolortheme` to the themes folder.
4. Restart Xcode and select the theme in *Preferences, Fonts & Colors*
