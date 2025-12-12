# Pixii Fuji Film Simulation Profiles (DCP)

This repository contains **custom DCP color profiles for Pixii cameras**, created by applying **Fujifilm film simulation look tables** on top of the **Pixii Standard camera profile**.

The goal is to bring Fuji-style color and tone rendering (Provia, Velvia, Classic Chrome, etc.) directly into the Pixii workflow while preserving Pixii’s native sensor color science.

---

## What these profiles are

- Based on the **Pixii Standard** camera profile
- Fuji film simulations applied via:
  - `LookTable`
  - `ToneCurve`
- Pixii’s original:
  - `ColorMatrix`
  - `HueSatDeltas`
remain untouched

This mirrors how Adobe builds camera-matching profiles and avoids breaking Pixii’s base color accuracy.

---

## Included film simulations

Depending on the version, profiles may include:

- Provia
- Velvia
- Astia
- Classic Chrome
- Pro Neg Std
- Pro Neg Hi
- Eterna
- Reala Ace

> Note: Some simulations (e.g. Classic Neg, Nostalgic Neg, Bleach Bypass) rely heavily on Fuji sensor behavior and may differ slightly on Pixii.

---

## Installation (Pixii)

1. Download or clone this repository
2. Copy the `.dcp` files into your Pixii profiles directory: