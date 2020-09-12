# Joystick Diagrams - Visualise your binds

## What is this tool for?
Learning flight simulators is a daunting task, with lots of buttons to remember. I built this tool for myself, and then thought others might also enjoy it, automating what is a time consuming task!

- Export your joystick/throttle/custom HID buttons to a SVG, and print with your browser
- Overlay your buttons onto an actual Joystick profile/picture
- Learn your joystick setup easier and be a better pilot!

## What's supported?

### Joystick Gremlin
- Custom SVG templates can be built to suit your joystick, throttle, custom HID device
- Support for multiple profiles in Joystick Gremlin

## What's not supported (yet)

### Joystick Gremlin
- Importing/inheriance of base templates into button profile exports (In progress)
- POV hats (In POV mode) - If your POV is configured for button outputs, then it will work

### Support for other programs/games (yet)
I'm currently working on DCS World - if you have a game you think will benefit from this, let me know and I might add it.

## Installation
None required, use the supplied binary in latest release.

Run joystick-diagram.exe

### From Source
Want to run from source? You'll need Python 3.8+

## Bugs
This is an initial release, all of the templates are new and there may be configuration differences to work out.

I'm expecting issues with the Virpil templates, as don't have the logical buttons available to me.

## Usage
Please ensure you have **backup of your config**, this should not modify if but I also take no responsibility if you lose all your binds!

- Run joystick-diagram.exe
- Select your Joystick Gremlin profile XML
- Hit Export
- If it finds a match, it'll export the bindings for this device, and any modes you have configured
- If you have web browser enabled, they'll automatically open in your browser
- Files will be stored in /diagrams when export has been completed. You can open these in a web browser, and print to PDF/printer from there

# Templates/Supported Devices
[Please read](templates/readme.md)

# Support / Beer fund
I plan to expand this out and continue on this journey. I'd appreciate any donations for time saved and to help me continue to support this program.

[Donate via Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WLLDYGQM5Z39W&source=url)


