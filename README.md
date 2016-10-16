###Maple Mini with New USB
This is an arduino hardware addon for [STM32duino](https://github.com/rogerclarkmelbourne/Arduino_STM32) boards. It only includes one board and that is a board that is a Maple mini clone but does not include the USB reset hardware. All that is required is a 1.5k pullup on the USB D+ and inline 22 ohm resistors on both usb lines.

This is generally used when making your own Maple Mini clones, but you dont want to have to put all the transistors used by maple mini on the usb hardware to re-enumeration.

You must have the regular [STM32duino](https://github.com/rogerclarkmelbourne/Arduino_STM32) for this to work. Add it to your hardware folder just like you did for the STM32duino files. It pulls directly from the core, so updates to your STM32duino core will work here as well.