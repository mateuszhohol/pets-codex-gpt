# Codex GPT Pets

Animated Codex v2 pets for Aaron Beck, Freud, Euclid, René Descartes, Eddie, and Pan Spinacz, packaged as 8×11 WEBP spritesheets.

## Pets

- `pets/aaron-beck/`: Aaron Beck, with white hair, clear round glasses, a red bow tie, and a brown tweed jacket.
- `pets/freud/`: Freud, with silver beard, dark suit, and pipe.
- `pets/euclid/`: Euclid, with white beard, tall cap, red cloak, and geometry tablet.
- `pets/descartes/`: René Descartes, with dark curls, scholarly coat, raised finger, and leather book.
- `pets/eddie/`: Eddie, a dark rock mascot with wild yellow hair, leather clothing, and a hand axe.
- `pets/pan-spinacz/`: Pan Spinacz, a purple paperclip helper with large eyes and an attached sheet of lined paper.

Each pet directory contains `pet.json` and `spritesheet.webp`.

## Installation

1. Copy the desired pet directory into `~/.codex/pets/`.
2. Keep the directory name aligned with the `id` in `pet.json`.
3. Restart Codex, then select the pet in Settings > Pets.

For example:

```sh
cp -R pets/freud ~/.codex/pets/
cp -R pets/euclid ~/.codex/pets/
cp -R pets/descartes ~/.codex/pets/
cp -R pets/aaron-beck ~/.codex/pets/
cp -R pets/eddie ~/.codex/pets/
cp -R pets/pan-spinacz ~/.codex/pets/
```

The spritesheets use `spriteVersionNumber: 2` and include the complete 8×11 atlas required by the v2 pet format.

## License

Copyright (c) 2026 Mateusz Hohol

The pet artwork, metadata, and documentation in this repository are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See [LICENSE](LICENSE) and the [official license text](https://creativecommons.org/licenses/by/4.0/legalcode).
