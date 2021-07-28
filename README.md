# BLErry ZMK Configuration

This repository is for RMI-KB keyboards that use ZMK, specifically the BLErry series of boards. Any questions, feel free to ask in the relevant **BLErry** channel in the [RMI-KB discord server](https://discord.gg/hXcpWvg5zB).

## Known Issues

- When you do the tweezer test and you short two pins that are not part of your layout, the top left key will actuate.

    - For example with the default layout (unified backspace), if you test the right half of the split backspace, it will send Esc. This is probably a bug with ZMK.

- If you choose the HHKB bottom row layout, and then tweezer test Right Ctrl, this will make the keyboard unresponsive. Just unplug and plug again.

## Available Boards

Check out the available boards in their respective branches. Current available boards:

- `blerry60`
- `blerry75`