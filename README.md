# rpgm-asset-decrypter-rs

A CLI tool for decrypting/encrypting RPG Maker MV/MZ audio and image assets.

## Installation

Get the binaries in Releases section.

## Usage

```bash
asset-decrypter decrypt --engine mv -i "./rpg-maker-mv-game/www/img/tilesets"

# Uses default key, provide manually using `--key` if game has different key.
asset-decrypter encrypt --engine mv -i "./decrypted-images"
```

## License

Project is licensed under WTFPL.
