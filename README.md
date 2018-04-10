# WhiteFox and NightFox
A Mac compatible configuration for the WhiteFox and NightFox keyboards. I use this layout on both my WhiteFox and NightFox. Feel free to [open an issue](https://github.com/kortsmit/whitefox/issues/new) if you have any suggestions!

![WhiteFox and NightFox Layout](https://github.com/kortsmit/whitefox/raw/master/assets/layout.jpg "WhiteFox and NightFox Layout")

## Mac Installation Instructions

1. `brew install dfu-util`
2. Press the flash button on the bottom of the keyboard
3. Navigate to the directory you downloaded the firmware to
4. Flash using `dfu-util -D kiibohd.dfu.bin`
5. Orange led will turn off
6. Keyboard is ready to go!
