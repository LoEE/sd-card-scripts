## SD Card Scripts

To use the scripts you will need `pv` but you probably want to install `lzop` and `xz` as well. On OS X you can install all of them via:
```
brew install pv lzop xz
```

To save an SD card image:
```
imgdump /dev/rdisk2 sd-card-backup-2016.03.08.img
```

To burn it on a card:
```
imgburn sd-card-backup-2016.03.08.img.xz /dev/rdisk2
```
