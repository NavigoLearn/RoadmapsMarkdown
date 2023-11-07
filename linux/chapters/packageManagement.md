# 4. Package Management
- Package management is the process of installing, updating, and removing software packages.
- There are many different package managers, but the most common ones are `apt`, `yum`, `pacman`, and `portage`.
- [Article - Package Manager](https://en.wikipedia.org/wiki/Package_manager)

## 4.A Debian-based distros (apt-get, dpkg)
- `apt-get` is the most common package manager on Debian-based distros. It is a command-line tool that allows you to install, update, upgrade, and remove packages.
- `apt-get update` updates the list of available packages.
- `apt-get upgrade` upgrades all installed packages.
- `apt-get install <package>` installs a package.
- `apt-get remove <package>` removes a package.
- `dpkg` is a command-line tool that allows you to install, update, upgrade, and remove packages.
- [Documentation - apt-get](https://manpages.org/apt-get/8)
- [Documentation - dpkg](https://manpages.org/dpkg)
- [Article - Debian Package Management](https://wiki.debian.org/PackageManagement)

## 4.B Red Hat-based distros (dnf, yum, rpm)
- `dnf` is the most common package manager on Red Hat-based distros.
- `dnf` is a fork of `yum`, and it is the default package manager on Fedora. It uses the same syntax as `yum`.
- `yum` is a command-line tool that enables you to manage packages on Red Hat-based distros
- `dnf/yum update` updates and upgrades all installed packages.
- `dnf/yum install <package>` installs a package.
- `dnf/yum remove <package>` removes a package.
- `rpm` is a command-line tool that allows you to install, update, and remove packages.
- [Documentation - dnf](https://www.man7.org/linux/man-pages/man8/dnf.8.html)
- [Documentation - yum](https://www.man7.org/linux/man-pages/man8/yum.8@@yum.html)
- [Documentation - rpm](https://manpages.org/rpm/8)

## 4.C Arch Linux distros (yay, pacman)
- `yay` (Yet Another Yogurt) is an AUR helper that allows you to install packages from the AUR. It overlays on top of `pacman`.
- `pacman` is the default package manager on Arch Linux distros.
- `yay/pacman -Syu` updates and upgrades all installed packages.
- `yay/pacman -S <package>` installs a package.
- `yay/pacman -R <package>` removes a package.
- [Documentation - yay](https://linuxcommandlibrary.com/man/yay)
- [Documentation - pacman](https://linuxcommandlibrary.com/man/pacman)

## 4.D Source-based distros (Portage in Gentoo)
```diff
- I have never used a source-based distro, so I don't know much about them.
- If you have experience with source-based distros, please contribute to this section. 
- And correct any mistake I might have made
```
- `emerge` is the default package manager on Gentoo. It is a command-line tool that enables you to download, compile, and install packages from source.
- `emerge --sync` updates the list of available packages.
- `emerge --update --deep --newuse @world` updates and upgrades all installed packages.
- `emerge <package>` installs a package.
- `emerge --unmerge <package>` removes a package.
- [Documentation - emerge](https://wiki.gentoo.org/wiki/Emerge)