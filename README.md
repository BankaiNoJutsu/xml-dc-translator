# xml-dc-translator

Utility for auto-translating the Tera DataCenter based on XML files.   
You can unpack and pack the DataCenter using the https://github.com/vezel-dev/novadrop.   
For correct repacking the DC of patch 100.02, you need to use an [updated XSD files](https://drive.google.com/drive/folders/1U1w4GgEgEoeayX3dmMryIX70ztdisCl9?usp=sharing).

### Installaction and usage

1. Install latest node.js.
2. See `config.js`.
3. Run `translate.bat` or `node --max_old_space_size=4096 index`.

## Item names restoration tool

Most of the items are already in the game, but have different IDs.   
The this tool compares the unique parameters of the item and finds a similar item (in fact the same one) and transfers the translation from it.

### Usage

1. See `restorate_config.js`.
2. Run `restorate.bat` or `node --max_old_space_size=4096 restorate`.
