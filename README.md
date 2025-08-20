# Node-RED Dashboard Virtual Keyboard (Spanish ISO)

A lightweight **on-screen virtual keyboard** for [Node-RED Dashboard 2 (`@flowfuse/node-red-dashboard`)](https://github.com/flowfuse/node-red-dashboard), built entirely in a **single `ui_template` node**.  
Optimized for **Raspberry Pi OS Bookworm in kiosk mode**, with no external dependencies.

---

## ✨ Features
- **Spanish ISO layout** (includes ñ, ç, `´`, `` ` ``, and symbols).  
- **Dead keys for accents** → first press `´` or `` ` ``, then type a vowel.
- **Docked or floating mode** → docked at the bottom, or drag to reposition.  
- **Kiosk-ready** → designed for touchscreens and no extra dependencies.  
- **Closes automatically** when pressing Enter, clicking outside, or using the × button.  
- Works seamlessly with inputs from **Node-RED Dashboard 2** (`.v-field__input` / `#input-v-*`).  

---

## 🛠 Requirements
- Raspberry Pi OS **Bookworm** (2023+)
- **Node-RED 3+**  
- **@flowfuse/node-red-dashboard** installed
- Browser running in **kiosk mode** (e.g. Chromium with `--kiosk`)

---
