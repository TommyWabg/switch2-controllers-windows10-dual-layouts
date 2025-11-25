# switch2 controllers
An app to use switch 2 joycons on pc as gamepad and mouse

### Usage

No need to pair the controller in the bluetooth settings.

Simply launch the app, and do what it says.

If you already paired the joycons in windows bluetooth settings, remove it before attempting to use it with this app.

### Using as a mouse

By default the app switches a joycon to mouse mode when it detects it's being used a mouse (side of of the joycon against a flat surface)

When in mouse mode, the following buttons are used as mouse buttons and no longer useable as gamepad buttons :
L/R : left click
ZL/ZR : right click
joystick : mouse wheel and middle button (click)

If you do not wish to use mouse mode, you can disable it in the config

### Using joycons sideways

By default, the app will always try to combine a right and left joycons together to make a single virtual controller.

If you wish to use both joycons sideway, you can hold SL\SR while turning them on
An other option is to set `combine_joycons` in the config to false so that the app will never try to combine joycons
