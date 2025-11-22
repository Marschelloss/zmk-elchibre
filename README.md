# El Chibre Firmware

## How to use
- fork this repo
- `git clone` your repo, to create a local copy on your PC
- adjust the .keymap file (find all the keycodes on the [zmk docs pages](https://zmk.dev/docs))
- `git pushal your repo to your fork`
- on the GitHub page of your fork navigate to "Actions"
- scroll down, download and unzip the `firmware.zip` archive that contains the latest firmware
- connect the El Chibre to your PC, press reset and hold the boot key during reset
- the keyboard should now apppear as a mass storage device
- drag'n'drop the `.uf` file from the archive onto the storage device
