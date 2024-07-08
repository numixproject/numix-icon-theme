# Numix icon theme
Numix is the official icon theme from the [Numix Project](https://numixproject.github.io/). It is heavily inspired by, and based upon parts of the Elementary, Humanity and Gnome icon themes. Numix is designed to be used along-side an application icon theme like [Numix Circle](https://github.com/numixproject/numix-icon-theme-circle) or [Numix Square](https://github.com/numixproject/numix-icon-theme-square). This readme provides information on [installation](https://github.com/numixproject/numix-icon-theme#install-it) and [icon requests](https://github.com/numixproject/numix-icon-theme#icon-requests). Licensed under the GPL-3.0+

## Install it
If using this with one of our app icon themes (like [Numix Circle](https://github.com/numixproject/numix-icon-theme-circle)) make sure you install both parts using the same method. This makes sure that the panel icons keep working as intended.

### Distro Packages
If you use, Fedora, Debian, Ubuntu, or any of their derivatives then you're sorted! Numix is available from the official repositories.
`numix-icon-theme` is available also on `conda-forge`

|Distro|Install Command/Links|
|:----:|:----:|
|![fedora][fedora]|`sudo dnf install numix-icon-theme`|
|![debian][debian] &nbsp;![ubuntu][ubuntu]|`sudo apt install numix-icon-theme`|
|![conda][conda]|`conda install -c conda-forge numix-icon-theme`|

### Nightly Packages
If you use Ubuntu or any of its derivatives (including Mint and elementary OS) you can use our Numix PPA to get the very latest version of the theme. Fire up a Terminal and run the following:

```bash
sudo add-apt-repository ppa:numix/ppa
sudo apt-get update
sudo apt-get install numix-icon-theme
```

For Arch users there's a [community maintained package](https://aur.archlinux.org/packages/numix-icon-theme-git/) in the AUR which builds from this GitHub.

## Icon Requests
Application icon requests should be posted in the [Numix Core](https://github.com/numixproject/numix-core) issue tracker. Folder icons requests should be posted in the [Numix Folders](https://github.com/numixproject/numix-folders/issues) issue tracker. Action icons, indicators, file types and everything else should be posted here.

## Hardcoded Icons
To deal with hardcoded status icons Numix recommends you use the [Hardcode Tray](https://github.com/bil-elmoussaoui/Hardcode-Tray) script.

[fedora]: https://user-images.githubusercontent.com/17854950/86288769-c3351a00-bbea-11ea-908c-156c7bf0b778.png
[ubuntu]: https://user-images.githubusercontent.com/17854950/86288823-e069e880-bbea-11ea-9214-4764c5628f39.png
[debian]: https://user-images.githubusercontent.com/17854950/86288828-e4960600-bbea-11ea-9a46-4eb19621b3ae.png
[conda]: https://user-images.githubusercontent.com/16744101/162778090-0a2c6316-5a41-4c98-8d32-41a6ed7e5cd3.png
