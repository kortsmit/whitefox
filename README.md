# WhiteFox
A Mac compatible configuration for the WhiteFox keyboard.

![WhiteFox Layout](https://github.com/kortsmit/whitefox/raw/master/assets/layout.jpg "WhiteFox Layout")

## Mac Installation Instructions (Command-line)

1. `brew install dfu-util`
2. Press the flash button on the bottom of the keyboard
3. Navigate to the directory you downloaded the firmware to
4. Flash using `dfu-util -D kiibohd.dfu.bin`
5. Orange led will turn off
6. Keyboard is ready to go!
