<!-- @format -->

# Keyboard based off RMK and Mad Mod Labs 68 key keyboard

## Thank you

- [RMK](https://rmk.rs/index.html) for the keyboard firmware and inspiration
- [Mad Mod labs](https://www.printables.com/model/307908-mechanical-keyboard-68-key-65/files) for the 3D printable case design
- [Mad Mod Labs Youtube](https://www.youtube.com/watch?v=iOeYkLlq9Ds&t=628s)

## Flashing Firmware to MCU

- [Probe-rs](https://probe.rs)

cargo-flash vs cargo-embed

### hex

```bash
probe-rs download --format hex --chip <YourMCUChip> your_firmware.hex
```

### uf2

Drag and drop tools/Mad_Mod_Labs_68.uf2 into the folder.

1. Hold the BOOTSEL (or BOOT) button: Press and hold the BOOTSEL button on your board. While holding it, plug the USB cable into your Mac. Keep holding the button for a few seconds after connecting, then release .

2. Use the RESET and BOOT buttons: Press and hold the BOOT button. While holding it, press and release the RESET button. Then, release the BOOT button .

3. Double-tap RESET: Quickly press the RESET button twice
