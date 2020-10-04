# Mod updater for FS19
Updates all the mods in your mod folder to the latest version. No more updating each mod individually!

This does however not account for mods that break saves on updates, there isn't really a way to manage that as of now.
Hence this might be better to use for sporadic players who just wants to quickly jump in and plow some fields or cut down a forrest.

(Mods that cant be matched exactly by name and author are left "as is". Shouldn't be many, but you'll have to update those yourself.)
## Usage
### Perquisite
Python3.8+
```
pip install -r .\requirement.txt
```

```
py ./update_mods.py -f "path to mod-directory"
```
### Help
```
py .\update_mods.py -h
usage: mod updater [-h] -f MOD_DIR

Commandline tool to update mods in FS19.

optional arguments:
  -h, --help            show this help message and exit
  -f MOD_DIR, --mod-dir MOD_DIR
                        Path to mod-directory (usually "HOME/my games/FarmingSimulator2019/mods/")

There is no guarantee that this will work when you use it, please don't be mad.
```
## Problems
If you stumble upon this and get stuck with something, open an issue and we hopefully have the time to look at it. Or do a PR :)
