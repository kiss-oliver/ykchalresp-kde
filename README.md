# ykchalresp-kde
Simple zenity-based script to simplify Yubikey challenge-response process. Sends challenge to slot 2. To send it to slot 1 modify the script by changing `-2` to `-1` right after the `ykchalresp` command.

## Requires

- yubikey-personalization
- zenity
- xclip

## Usage
Simply issue `bash chalresp.sh` with your yubikey plugged in then enter your challenge. The response is automatically copied to the clipboard and then the whole klipper kistory is emptied once you click OK.

