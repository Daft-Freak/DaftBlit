# DaftBlit
It's... a handheld console?

## Boards
- [Gamepads](https://github.com/Daft-Freak/py32-i2c-gamepad) (x2)
- `board/extra-buttons`: "Start/Select" buttons
- Display: TODO

## 3D Printed Parts
- `abxy.stl` A/B/X/Y buttons (x4)
- `console28-back.stl` back half of case
- `console28-front.stl` front half of case, should be printed face down
- `console28-dbg-cover` cover for debug port access
- `controller-mod-back.stl`/`controller-mod-front.stl` modifiers for multi-colour printing
- `dpad.stl` dpad, requires supports and a bit tricky to print
- `on-off-flat.stl` power button
- `start-select.stl` start/select buttons, requires supports and is very small (x2)

## Other hardware
- Button pads: 2x the dpad part from a GBA SP set.
- LCD: https://www.aliexpress.com/item/1005009128815676.html (2.8 inch 40 pin 240x320 ST7789)
- Speaker: TODO (can't remember if it's https://shop.pimoroni.com/products/mini-speaker-8-1w or not)
- Battery: TODO
- Screws: TODO (there are four different ones)
- Cables: 1-2 "short" (50mm?) i2c cables and a longer one (100mm?), 5-pin 0.5mm ffc for start/select buttons
- Joystick: the switch joy-con one
- Brains: RP2350 stamp, the XL one if you want the power button to work
- Optional sensor stick for... sensors
