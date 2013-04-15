landfall
========

File structure:
```
  landfall
  |-landfall            core files
  | |-src                 contains core program source code (everything that is platform-independant)
  | |-libs                contains core libgdx library files and platform independant extensions/libraries
  | `-etc                 contains texture files waiting to go through the texture packer
  |-landfall-android    android specific files and game assets
  | |-src                 android specific source files
  | |-assets              all assets that are shipped with the game
  | |-res                 android resource files
  | `-libs                android specific binaries and libgdx stuff
  `-landfall-desktop    desktop specific files
    |-libs                desktop specific binaries and libgdx stuff
    `-src                 desktop specific source files
```
