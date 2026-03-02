# EKEEL — Augmentator

<!--
Internal note (not rendered): keep this README aligned across all EKEEL deliverable repositories.
-->

## Overview
**This repository contains a research prototype for knowledge-graph-based augmentation of video lessons in an immersive VR environment. It enables experimental use and reproducible evaluation.**

- **Project:** EKEEL — PRIN 2022 PNRR
- **Deliverable:** **D5.1** — Prototype development
- **Repository:** `ekeel-project/EKEEL_augmentator`
- **Website:** https://ekeel.dibris.unige.it/

## What’s in this repository
- `code/` — Source code for the software component.
- `docs/` — Technical documentation, manuals, and usage notes.


### Requirements
**Accounts / apps**
- Epic Games account
- Meta account
- Meta Quest App

**OS / device**
- Windows (recommended for Unreal + Quest development)
- VR headset: Meta Quest 2 / Meta Quest 3

**Runtime / tooling**
- Unreal Engine 5.3.2
- Unreal plugins:
  - Blueprint FileSDK
  - VaRest

**Hardware**
- VR-capable GPU (e.g., GTX 1080 or better)
- VR-capable CPU (e.g., i7-7700K or better)

### Installation
```bash
git clone https://github.com/ekeel-project/EKEEL_augmentator.git
cd EKEEL_augmentator
```

**Quick start**
- Run (Unreal Editor)
- Install and launch Unreal Engine 5.3.2 (Epic Games Launcher).
- Open the project by selecting the .uproject file inside code/.
- Ensure the required plugins are installed/enabled (Blueprint FileSDK, VaRest).
- Connect the headset (Meta Quest 2/3) and verify it is available for VR preview.
- Run from the editor

## Responsible unit
This component was developed and maintained by the University of Genoa (UniGe).
