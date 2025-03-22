# minui-simple-mode.pak

A MinUI app that enables MinUI's Simple Mode functionality.

> Not simple enough for you (or maybe your kids)? MinUI has a simple mode that hides the Tools folder and replaces Options in the in-game menu with Reset. Perfect for handing off to littles (and olds too I guess). Just create an empty file named "enable-simple-mode" (no extension) in "/.userdata/shared/".

## Requirements

This pak is designed and tested on the following MinUI Platforms and devices:

- `tg5040`: Trimui Brick (formerly `tg3040`), Trimui Smart Pro
- `rg35xxplus`: RG-35XX Plus, RG-34XX, RG-35XX H, RG-35XX SP

Use the correct platform for your device.

## Installation

1. Mount your MinUI SD card.
2. Download the latest release from Github. It will be named `Simple.Mode.pak.zip`.
3. Copy the zip file to `/Tools/$PLATFORM/Simple Mode.pak.zip`. Please ensure the new zip file name is `Simple Mode.pak.zip`, without a dot (`.`) between the words `Simple` and `Mode`.
4. Extract the zip in place, then delete the zip file.
5. Confirm that there is a `/Tools/$PLATFORM/Simple Mode.pak/launch.sh` file on your SD card.
6. Unmount your SD Card and insert it into your MinUI device.

## Usage

Browse to `Tools > Simple Mode` and press `A` to enter the app. You can enable simple mode by confirming in the app.

### Disabling Simple Mode

While the device is booting, press and hold the `R2` button until you see a message on the screen. The functionality will be disabled and MinUI will boot into normal mode.
