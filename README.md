# Codex GPT Pets

Animated Codex v2 pets for Freud and Euclid, packaged as 8×11 WEBP spritesheets.

## Pets

- `pets/freud/`: Freud, with silver beard, dark suit, and pipe.
- `pets/euclid/`: Euclid, with white beard, tall cap, red cloak, and geometry tablet.

Each pet directory contains `pet.json` and `spritesheet.webp`.

## Installation

1. Copy the desired pet directory into `~/.codex/pets/`.
2. Keep the directory name aligned with the `id` in `pet.json`.
3. Restart Codex, then select the pet in Settings > Pets.

For example:

```sh
cp -R pets/freud ~/.codex/pets/
cp -R pets/euclid ~/.codex/pets/
```

The spritesheets use `spriteVersionNumber: 2` and include the complete 8×11 atlas required by the v2 pet format.

## License

Copyright (c) 2026 Mateusz Hohol

The pet artwork, metadata, and documentation in this repository are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See [LICENSE](LICENSE) and the [official license text](https://creativecommons.org/licenses/by/4.0/legalcode).
