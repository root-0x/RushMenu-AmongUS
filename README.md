<div align="center">

![RushMenu Banner](logo.png)

# 🚀 RushMenu

**A simple yet powerful Among Us cheat menu with an intuitive interface and tons of useful features.**

[![Discord](https://img.shields.io/badge/Discord-RUSH-blue?style=flat&logo=discord)](https://discord.gg/RUSHUD)

</div>

---

## 🎁 Releases

| Mod Version | Among Us - Version | Link |
|-------------|--------------------|----|
| v3.0.1 | 2026.2.17 (17.0.0) | [Download](../../releases/tag/v3.0.1) |

---

## 📥 Installation

1. **Download** the latest version from the [Releases](#-releases) table above
2. **Extract** the downloaded ZIP file
3. **Locate** your Among Us folder (usually `Steam\steamapps\common\Among Us`)
4. **Copy** all extracted files into the game folder:
   - `winhttp.dll`
   - `doorstop_config.ini`
   - Complete `BepInEx` and `dotnet` folders
5. **Verify** that `RushMenu.dll` is in `BepInEx\plugins\`
6. **Launch** the game and press **Delete** key to open the menu

> ⚠️ **Important**: Requires BepInEx 6.0.0-BE-735 minimum

---

## ⚙️ Configuration

After the first launch, edit `BepInEx\config\RushMenu.cfg` to customize:

| Setting | Description | Default Value |
|---------|-------------|---------------|
| **GUI.Keybind** | Key to open/close the menu | `Delete` |
| **GUI.Color** | Menu color (HTML color code) | - |
| **GuestMode.GuestMode** | Generates a new guest account each launch (bypasses account bans) | `false` |
| **GuestMode.FriendName** | Friend name for guest mode (≤10 characters, no #) | - |
| **Spoofing.Level** | Custom player level displayed to others (0-4294967295) | - |
| **Spoofing.Platform** | Custom platform displayed to others | - |
| **Privacy.HideDeviceId** | Hides your unique device ID (potentially bypasses hardware bans) | `true` |
| **Privacy.NoTelemetry** | Disables sending analytics to Innersloth | `true` |

---

## 🎯 Features

### 👱 Player

#### Movement
- **NoClip**: Walk through walls like a ghost
- **Boost Speed**: Doubles your movement speed
- **Teleport to Cursor**: Right-click to teleport
- **Teleport to Player**: Select a target player

#### Kill Actions
- **Kill Player**: Kill a specific player instantly
- **Kill All Crewmates**: Eliminates all crewmates
- **Kill All Impostors**: Eliminates all impostors
- **Kill All**: Eliminates all players

---

### 👁️ ESP (Extra Sensory Perception)

#### Vision
- **See Roles**: See every player's role on their nametag
- **See Ghosts**: See ghosts and their chat even while alive
- **No Shadows**: Removes shadows (see during blackouts + through walls)
- **Reveal Votes**: See votes in real-time (even anonymous ones)
- **Always Chat**: Chat always available (outside meetings/lobby)

#### Camera
- **Zoom Out**: Zoom out using mouse scroll wheel
- **Spectate**: Follow another player's camera
- **Freecam**: Move camera freely without moving your character

#### Tracers
Lines pointing to:
- **Crewmates** (cyan)
- **Impostors** (red)
- **Ghosts** (white)
- **Dead Bodies** (yellow)
- **Color-based**: Uses player's color

#### Minimap
Points on the map for:
- **Crewmates** (cyan)
- **Impostors** (red)
- **Ghosts** (white)
- **Color-based**: Uses player's color

---

### 🎭 Roles

#### General
- **Set Fake Role**: Change your role (all roles available)
  - Shapeshifter and Phantom disabled by default (anti-anticheat)

#### Impostor
- **Kill Anyone**: Kill anyone (protected, impostor, ghost, in vent)
- **No Kill Cooldown**: Kill without cooldown
- **Kill Reach**: Kill at infinite distance

#### Phantom
- **Kill While Vanished**: Kill while invisible

#### Shapeshifter
- **No Ss Animation**: Instant transformation
- **Endless Ss Duration**: Stay transformed indefinitely

#### Crewmate
- **Complete My Tasks**: Complete all your tasks instantly

#### Tracker
- **Endless Tracking**: Track a player indefinitely
- **No Track Delay**: Removes tracking delay
- **No Track Cooldown**: No cooldown between tracks

#### Engineer
- **Endless Vent Time**: Stay in vents indefinitely
- **No Vent Cooldown**: No cooldown between vents

#### Scientist
- **Endless Battery**: Infinite battery on vitals
- **No Vitals Cooldown**: No cooldown on vitals

---

### 🚀 Ship

#### General
- **Unfixable Lights**: Lights off permanently (can be re-enabled)
- **Report Body**: Report any player as a dead body
- **Close Meeting**: Close meeting (for you only)

#### Sabotages
Work even without being impostor, no cooldown, simultaneously, and during meetings:
- **Reactor**: Enable/disable reactor sabotage
- **Oxygen**: Enable/disable oxygen sabotage
- **Lights**: Enable/disable lights sabotage
- **Comms**: Enable/disable communications sabotage
- **Doors**: Locks all doors instantly
- **MushroomMixup**: Mushroom sabotage (Fungle map)

#### Vents
- **UseVents**: Use vents without being impostor/engineer
- **KickVents**: Kicks all players from vents
- **WalkInVents**: Invisibility while staying in a vent and moving

---

### 💤 Passives

**Always active by default (cannot be disabled to avoid issues)**

- **Free Cosmetics**: Access to all cosmetics for free
  - Hats, visors, skins, pets, nameplates, bundles, cosmicubes
- **Avoid Penalties**: Removes disconnect penalties
- **Unlock Extra Features**: Automatically unlocks
  - Free chat, friends list, custom name, online play

---

## 🛠️ Technical Information

- **Author**: Root
- **Version**: 3.0.1
- **Framework**: BepInEx 6.0.0-BE-735 (Unity IL2CPP)
- **Language**: C# (.NET 6.0)
- **Libraries**: HarmonyLib for patching

---

## ⚠️ Disclaimer

This mod is **not affiliated** with Among Us or Innersloth LLC.

Using this mod may **violate Among Us Terms of Service** and result in sanctions, including **temporary or permanent bans**.

The author is **not responsible** for any consequences of using this mod.

**Use at your own risk.**

---

<div align="center">

**Join us on Discord: [discord.gg/RUSHUD](https://discord.gg/RUSHUD)**

Made with 💀 by Root

</div>
