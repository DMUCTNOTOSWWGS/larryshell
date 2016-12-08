# LarryShell

![LarryShell](logo.png "LarryShell")

LarryShell is a variation of `bash` which makes it behave more like Larry.

## What does LarryShell do?

LarryShell modifies `bash` to create a more affluent command-line interface, complete with a response telling you whether or not you are rich or poor depending on whether or not the previous command you ran was successful.  LarryShell also sasses you and calls you bad if your command does not run successfully.

## Running LarryShell
### From source
To run LarryShell, simply execute `chmod +x larryshell` to make the file executable, then run `./larryshell`.
### From the Arch User Repository
[LarryShell is on the AUR](https://aur.archlinux.org/packages/larryshell/), so it can be installed with `yaourt` or `pacaur` or by downloading the PKGBUILD and installing it manually.  
Using `yaourt`, the installation is
```shell
yaourt -S larryshell
```
Installing using the PKGBUILD from the AUR
```shell
makepkg
sudo pacman -U larryshell-*.tar.gz
```
