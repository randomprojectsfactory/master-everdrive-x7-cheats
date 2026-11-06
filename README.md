# Master EverDrive X7 Cheats

Game Genie cheat menu for Master EverDrive X7. **No flashing required**—installation only replaces files on the SD card.

Tested on a **Master System Model 1 (USA)** and a **Japanese Game Gear via Master System Player**.

[Download v11](Master-EverDrive-X7-Cheats-v11.zip?raw=1)

## Install

1. Back up your SD card’s `SMSSYS` folder and download the [original SMSOS v1.04](https://krikzz.com/pub/support/master-everdrive/x-series/OS/SMSOS-v1.04.zip).
2. Extract the patch package. From its folder, run with Python 3:
   ```sh
   python3 apply_patch.py "/path/to/SMSOS-v1.04.zip"
   ```
   This creates `Master-X7-Cheats-v11-ready`. Use the original OS, not an already modified version.
3. With the console off, copy `SMSOS.BIN` and `CHTEDIT.BIN` from the generated `SMSSYS` folder into the card’s existing `SMSSYS` folder. Create `SMSSYS/CHEATS` if missing. Keep existing saves, settings and cheats.
4. Safely eject the card and boot. **Cheats** is the third in-game menu option.

## Uninstall

Restore your backed-up `SMSOS.BIN`, or the original v1.04 file, in `SMSSYS`. You can then delete `CHTEDIT.BIN`. Keep `SMSSYS/CHEATS` if you want your saved cheat entries. No flashing is required.
