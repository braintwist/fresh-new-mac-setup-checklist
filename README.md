# fresh-new-mac-setup-checklist

---

## Format the drive

1. Restart with cmd-R or cmd-D
2. Erase drive / 3x if second-hand
3. Reinstall MacOS

---

## First boot

### Change system password.

### System Prefs
```
  Security & Privacy
      disable Location services
      allow apps
      enable Filevault
  Desktop
      disable screen saver
      background: 17% grey
  Spotlight
      turn off command keys
      disable almost everything
  Network
      add DNS (http://www.opendns.com/opendns-ip-addresses/)
      208.67.222.222
      208.67.220.220
```

### Get online

- Safari: download [Dropbox](//www.dropbox.com/downloading?src=index)
- Dropbox: selective sync: just /Writing + /1Password
- Safari: download [1Password](//agilebits.com)
- Safari: download [Quicksilver](//qsapp.com/download.php)
- Quicksilver: download Quicksilver plugins, especially Extra Scripts
- Safari: download [Firefox Developer](//www.mozilla.org/en-US/firefox/channel/#developer)
- Safari: download [Chrome](//www.google.com/chrome/browser/desktop/)
- Firefox: Sync
- Chrome: Sync

### Download applications
- App Store: download purchased apps (especially UnArchiver)
- [iTerm 2](//iterm2.com/)

### Zsh

  > [Download](https://github.com/robbyrussell/oh-my-zsh)

  > curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh

  > https://gist.github.com/maxfenton/515f9f6fcfab0eadfd1a

### Install OS X CLI Tool
*and/or install Xcode if you want, from the App Store*

  > [Command Line](https://developer.apple.com/downloads/index.action?name=for%20Xcode%20-)

### install Git
*  do directly through GitHub app b/c why not *
  
> cf. https://help.github.com/articles/set-up-git\

### Install [Homebrew](http://brew.sh/)
* see the brew.md file attached to this gist*

### Run system stuff in gist
  
  > https://gist.github.com/maxfenton/515f9f6fcfab0eadfd1a
  
  > https://gist.github.com/maxfenton/515f9f6fcfab0eadfd1a/edit

### Download specific software on Dropbox
- BBEdit - BBEdit_10.1.2.dmg
- Automator Dispense - Install%20Automator%20Action.pkg
- CSS Edit - CSSEdit2.6.1.dmg
- iTunes 11

### Setup writer folder and nvAlt
- Dropbox selective sync: `Writer` folder
- Download [nvAlt](http://brettterpstra.com/projects/nvalt/)
- set nvAlt to use `Writer` folder

### Download apps from the Web
- [AppZapper](//www.appzapper.com/)
- [Arq](//www.haystacksoftware.com/arq/)
- [Bartender](//www.macbartender.com/)
- [Codekit](//incident57.com/codekit/)
- [CSS Comb](//csscomb.com/)
- [Disk Inventory X](//www.derlien.com/)
- [Divvy](//mizage.com/divvy/)
- [Fluid](//fluidapp.com/)
- [Flux](//justgetflux.com/)
- [GitHub](//mac.github.com/)
- [GPGtools](https://gpgtools.org)
- [ImageOptim](//imageoptim.com/)
- [MAMP Pro](//www.mamp.info/en/downloads/index.html)
- [OmniFocus](//www.omnigroup.com/omnifocus/)
- [Pacifist](//www.charlessoft.com)
- [Postbox](//www.postbox-inc.com/)
- [Quicktime 7](//support.apple.com/kb/DL923)
- [Sequel Pro](//www.sequelpro.com/download)
- [ShrinkIT](//www.panic.com/~will/shrinkit/)
- [SourceTree](//www.sourcetreeapp.com/download/)
- [Sublime Text](//www.sublimetext.com/3)
- [SublimeText Package Control](https://sublime.wbond.net/)
- [Superduper](//www.shirt-pocket.com/SuperDuper SuperDuperDescription.html)
- [Synergy](//synergy-project.org)
- [TextExpander](//smilesoftware.com/TextExpander/index.html)
- [TextMate](//macromates.com/download)
- [Transmission](https://www.transmissionbt.com/download/)
- [Transmit](//panic.com/transmit/)
- [Vagrant](//www.vagrantup.com/downloads.html)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Web Sharing Pref](//clickontyler.com/web-sharing/)
- [xScope](//iconfactory.com/software/xscope)

### AppZap built in apps
  > Chess, GarageBand, Maps, iBooks, Game Center, iTunes

### Downgrade iTunes
  > Downgrade to lowest iTunes that works (11.4) using Pacifist to install.

### Calendars
  > setup Google and Fastmail accounts in BusyCal

### Email
  > setup Fastmail account in Postbox

### Firefox, Safari, Chrome
- adblock + settings
- stylebot + settings

### Install virtual machines
  > Download [ievms](//github.com/xdissent/ievms)
  > curl -s https://raw.github.com/xdissent/ievms/master/ievms.sh | bash

----

## Additions

- https://github.com/powerline/powerline
*https://powerline.readthedocs.org/en/latest/installation/osx.html*

> brew install python
> brew install coreutils
> brew install vim --with-python --with-ruby --with-perl 
> brew install macvim --env-std --override-system-vim

> pip install powerline-status
- https://github.com/powerline/fonts // Powerline fonts
- https://github.com/nathco/Office-Code-Pro // Office Code Pro font

- [GPG](http://notes.jerzygangi.com/the-best-pgp-tutorial-for-mac-os-x-ever/) and Keybase
