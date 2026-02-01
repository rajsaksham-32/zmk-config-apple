# zmk-config-apple ⌨️

This repository contains my personal ZMK configuration for a custom mechanical keyboard that I built from scratch.

What started as a small interest in keyboards turned into a complete hardware + firmware project involving PCB design, microcontroller setup, and configuring ZMK to run the final keyboard.

This repo holds the full firmware configuration that powers my build.

---

## Build Photos

| Front View | Back View |
|-----------|----------|
| ![Corne Keyboard Front](images/corne-front.jpeg) | ![Corne Keyboard Back](images/corne-back.jpeg) |

---

## What this project is

- A custom keyboard firmware setup using **ZMK**
- Built for my own hand-made keyboard (PCB + controller + layout)
- Includes the complete keymap, layers, and configuration required to build firmware

---

## Why I made this

Most people only modify keymaps, but I wanted to understand the full engineering behind a keyboard:

- How the electrical matrix works  
- How a PCB is designed for key scanning  
- How a microcontroller reads inputs  
- How firmware like ZMK turns hardware into a working keyboard  

This project was a great way to combine embedded systems and software together into something real and usable.

---

## Hardware overview

This keyboard build includes:

- A custom-designed PCB  
- A BLE-capable microcontroller  
- ZMK firmware running on Zephyr RTOS  
- A compact Corne-style layout  

---

## Repository structure

```
config/              -> Keymap + ZMK behavior configuration  
boards/shields/      -> Custom keyboard shield definitions  
.github/workflows/   -> GitHub Actions firmware build pipeline  
build.yaml           -> Build instructions for automated builds  
```
---
## Credits

Huge thanks to the ZMK community for providing such an amazing open-source firmware platform.
ZMK Firmware: https://zmk.dev/
---
# Author

Made by Saksham Raj
If you find this project interesting, feel free to star the repository ⭐
