# wox-plugin-symenu
SyMenu integration for WoX keystroke launcher.

I always enjoy the huge flexibility when working with keystroke launchers like [Wox](https://github.com/Wox-launcher/Wox) on the one hand and having a browseable collection of (portable) software like [SyMenu](https://www.ugmfree.it/) is providing on the other.

Why not bringing both 'worlds' together? So I did write this plug-in for Wox launcher. It brings software configuration made in SyMenu as searchable list into Wox.

## Screenshot

![Screencast](/assets/screen.gif?raw=true "SyMeny for Wox")

## Features:

* Lists all program entries made in SyMenu
* Searches as you type and filters the SyMenu list in Wox
* Program icons generated by SyMenu are used too
* 'config.json' to setup software root and location of SyMenu
* Program items are read from the SyMenu configuration file, so a SyMenu process doesn't necessarily need to be running on your system

## Installation

As long this plug-in is in development it is not in the official Wox plug-in directory yet. Just checkout the code:

```
%USERNAME%\AppData\Roaming\Wox\Plugins\
```

## ToDo:

- [ ] Proper plug-in icon
- [ ] SyMenu folder support, allowing searches like 'code/atom'
- [ ] Argument support for selected programs
- [ ] Icons with better resolution

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
