# UBK — uncommon3D Bass Knob

A wireless **analog** volume controller for car audio, designed and built by [uncommon3D](https://uncommon3d.etsy.com).

This repository holds the firmware that runs the UBK. If you found your way here from the shop and just want to know what it is and how it works — read on.

---

## What it is

The UBK lets you control your system's volume from a small wireless knob you keep within reach — no phone app, no Bluetooth pairing to your stereo, no menus to dig through. Just reach over and turn.

The important part: it's **fully analog**. The UBK physically turns a real volume control, so your signal is never digitized or processed. Nothing is added to your audio and nothing is taken away — it sounds exactly like it should, just easier to reach.

---

## How it works

The UBK comes in two pieces that talk to each other wirelessly:

```
   ┌─────────────┐    wireless link    ┌─────────────┐    turns a real    ┌──────────────┐
   │    KNOB      │  ───────────────▶  │    BASE      │  ───────────────▶ │ analog volume │
   │ the remote   │                     │  the brain   │                    │   control     │
   │ in your hand │  ◀───────────────  │ in your rig  │                    │ (your audio)  │
   └─────────────┘    stays in sync     └─────────────┘                    └──────────────┘
```

- The **Knob** is the wireless remote — a little screen and two dials, with its own rechargeable battery. It just reads what you want.
- The **Base** is the brain, wired into your system. When you turn the knob, it drives a motor that turns an actual analog volume control to match.
- The two stay paired over a direct, low-latency radio link, so the volume tracks your hand in real time. No Wi-Fi network or app required.
- The Base also keeps an eye on your system (things like supply voltage and temperature) and can ease the volume back to help protect your setup.

---

## What it can do

- 🎚️ **Real analog volume** — zero effect on sound quality
- 📡 **Wireless & instant** — turn the knob, the volume follows
- 🔋 **Rechargeable** — USB-C, with a battery gauge right on the screen; sleeps on its own to last
- 🎨 **Make it yours** — display layouts, brightness, a custom goodbye message, and pick-your-own sleep animations
- 🔒 **Stays yours** — a deliberate pairing window keeps other knobs from connecting to your base
- 🔄 **Gets better over time** — built-in Wi-Fi updates bring new features and fixes to a unit you already own

---

## Get one

The UBK is available in the uncommon3D shop, hand-made and tested:

### 👉 [uncommon3d.etsy.com](https://uncommon3d.etsy.com)

Questions, ideas, or just want to nerd out about a build? Reach out through the shop — there's a real person on the other end.

---

<sub>Firmware © uncommon3D. A small-shop project, actively maintained.</sub>
