# OrangeFox Recovery Project

### How to build ###

```bash
# Create dirs
$ mkdir ofox ; cd ofox

# Init repo
$ repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

# Clone j5y17lte repo
$ git clone https://gitlab.com/OrangeFox/device/j5y17lte.git -b fox_9.0 device/samsung/j5y17lte

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv device/samsung/j5y17lte/build_ofox.sh .
$ . build_ofox.sh j5y17lte
```

## Credits
2019 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
