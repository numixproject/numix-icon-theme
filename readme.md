Numix icon theme
================
Numix is the official icon theme from the [Numix Project](http://numixproject.org). It is heavily inspired by, and based upon parts of the Elementary, Humanity and Gnome icon themes. Designed to be used along side the application icon theme [Numix Circle](https://github.com/numixproject/numix-icon-theme-circle). This readme provides information on [installation](https://github.com/numixproject/numix-icon-theme#installation) and [icon requests](https://github.com/numixproject/numix-icon-theme#icon-requests). Licensed under the GPL-3.0+

### Installation
If using this with one of our app icon themes (like [Numix Circle](https://github.com/numixproject/numix-icon-theme-circle)) make sure you install both parts using the same method. This makes sure that the panel icons keep working as intended.

If you use Ubuntu or any of its derivatives (including Mint and elementary OS) you can use our Numix PPA. Fire up a Terminal and run the following:

```bash
sudo add-apt-repository ppa:numix/ppa
sudo apt-get update
sudo apt-get install numix-icon-theme
```

If you use Fedora you can either use [Fedy](http://folkswithhats.org/) or using a terminal run:

```bash
sudo dnf copr enable numix/numix
sudo dnf install numix-icon-theme
```

For Arch users there's a [community maintained package](https://aur.archlinux.org/packages/numix-icon-theme-git/) in the AUR which builds from this GitHub.

### Icon Requests
Application icon requests should be posted in the [Numix Circle](https://github.com/numixproject/numix-icon-theme-circle) issue tracker. Folder icons requests should be posted in the [Numix Folders](https://github.com/numixproject/numix-folders/issues) issue tracker. Action icons, indicators, file types and everything else should be posted here.

### Hardcoded Icons
To deal with hardcoded status icons Numix recommends you use the [Hardcode Tray](https://github.com/bil-elmoussaoui/Hardcode-Tray) script.
