## dinosaursrawr.dat.airforce
## 1.20.1 Forge

---

# RawrCraft Mod Pack — Mod Guide

A quick overview of everything in the pack, plus installation instructions for both official and cracked Minecraft.

---

## 📦 Installation Guide — Official Minecraft (Mojang/Microsoft Account)

### Requirements
- Minecraft Java Edition (purchased from [minecraft.net](https://minecraft.net))
- Java 17 or newer — download from [adoptium.net](https://adoptium.net)

### Steps

**1. Install Forge**
- Go to [files.minecraftforge.net](https://files.minecraftforge.net) and download the **1.20.1** installer (Recommended build).
- Run the `.jar` file: double-click it or run `java -jar forge-installer.jar`
- Select **"Install client"** and hit OK.
- Forge will appear as a new profile in your Minecraft Launcher.

**2. Install the mods**
- Open your `.minecraft` folder:
  - Windows: press `Win + R`, type `%appdata%\.minecraft`
  - Mac: `~/Library/Application Support/minecraft`
  - Linux: `~/.minecraft`
- If it doesn't exist, create a folder called `mods` inside it.
- Copy all the `.jar` files from the RawrCraft zip into the `mods` folder.

**3. Launch**
- Open the official Minecraft Launcher.
- Select the **Forge 1.20.1** profile from the dropdown and hit Play.
- First launch will take a while — Forge is loading all the mods.

> 💡 **Tip:** Give Minecraft more RAM. In the launcher, go to your Forge profile → More Options → JVM Arguments and change `-Xmx2G` to `-Xmx4G` or more. This pack needs it.

---

## 🏴‍☠️ Installation Guide — Cracked Minecraft

> This guide assumes you have a cracked launcher already. Popular options include **Prism Launcher** (with offline mode), **SKLauncher**, or **TLauncher**.

### Requirements
- A cracked launcher that supports Forge profiles
- Java 17 or newer — download from [adoptium.net](https://adoptium.net)

### Steps

**1. Install Forge via your launcher**

Most cracked launchers let you install Forge directly:
- In **Prism Launcher**: Add Instance → select version `1.20.1` → check "Install Forge" → pick the recommended build.
- In **SKLauncher / TLauncher**: Create a new profile, select version `1.20.1-Forge`, and let it download.

If your launcher doesn't support this, download the Forge installer from [files.minecraftforge.net](https://files.minecraftforge.net), run it, and point your launcher at the installed version manually.

**2. Install the mods**
- Find your launcher's game directory. This varies by launcher — look in Settings for a "Game Directory" or "Instance Folder" path.
- Inside it, open (or create) the `mods` folder.
- Copy all the `.jar` files from the RawrCraft zip into that `mods` folder.

**3. Launch**
- Select your Forge 1.20.1 profile and launch.
- Same as above — first launch will be slow while mods load.

> ⚠️ **Multiplayer note:** To join the RawrCraft server you will need a username set in your launcher. Any username works for an offline server, but ask the server admin if they have online-mode enabled — cracked accounts cannot join online-mode servers.

---

## 📖 Mod Guide

No major spoilers — just enough to know what to expect.

---

## 🌍 World & Biomes

**Biomes O' Plenty** — Adds a huge variety of new biomes across the Overworld, from lavender fields to bayous and beyond. The world feels much more alive and varied.

**Geophilic** — Subtle improvements to vanilla biomes. Makes existing biomes feel more natural and interesting without completely replacing them.

**TerraBlender** — Behind-the-scenes library that blends modded biomes into the world smoothly. Required for Biomes O' Plenty to work.

**Lithostitched** — Another world gen helper that stitches modded and vanilla structures together more naturally.

---

## 🏰 New Dimensions

**The Aether** — A heavenly dimension floating above the clouds, filled with unique mobs, dungeons, and loot. A classic.

**Twilight Forest** — A magical, ever-twilight dimension with a progression of bosses and themed areas to explore. One of the most content-rich mod dimensions out there.

**Dimensional Doors** — Adds mysterious doors that lead to pocket dimensions, rifts in space, and strange liminal corridors. A bit unsettling in the best way.

**Tropicraft** — A tropical paradise dimension with beaches, coral reefs, and creatures that feel like a proper vacation.

---

## 🔥 Nether & End

**Better End** — Completely overhauls the End dimension with new biomes, structures, plants, and creatures. Makes the End worth exploring.

**Luminous Nether** — Reworks the Nether with new biomes and atmospheric lighting. Much more visually striking.

**Gardens of the Dead** — Adds two new eerie Nether biomes filled with unique flora and fungi.

**BCLib & WunderLib** — Libraries used by Better End and Gardens of the Dead to function.

---

## ⚙️ Tech & Crafting

**Create** — A mechanical engineering mod built around rotating contraptions, conveyor belts, and automation. Deep and satisfying to learn.

**Tinkers' Construct** — A complete overhaul of tool and weapon crafting. Build custom tools from materials you choose, each with unique properties.

**Mantle** — Required library for Tinkers' Construct.

**Apotheosis** — Dramatically expands the enchanting system, mob difficulty, and loot. Makes the late game much more interesting.

**Apothic Attributes & Placebo** — Libraries that power Apotheosis's attribute and loot systems.

---

## 🍳 Food & Farming

**Farmer's Delight** — Adds cooking, new crops, and a full culinary system. Makes food actually worth caring about.

**Ender's Delight** — A Farmer's Delight addon themed around the End. New ingredients and recipes from the void.

**My Nether's Delight** — Farmer's Delight addon for the Nether. Turns Nether ingredients into proper food.

---

## 🛋️ Building & Decoration

**Refurbished Furniture** — A wide collection of decorative furniture pieces. Chairs, tables, shelves, lamps — makes builds feel lived in.

**Vanilla Backport** — Brings features from newer Minecraft versions back to 1.20.1. Mostly blocks and items you'd expect to already be in the game.

---

## 🗺️ Exploration & Navigation

**Xaero's Minimap** — A clean, customisable minimap in the corner of your screen.

**Xaero's World Map** — Full-screen world map that fills in as you explore. Works hand-in-hand with the minimap.

**WATut** — A lightweight waypoint and tutorial system to help orient new players.

---

## 🔊 Audio & Immersion

**Ambient Sounds** — Fills the world with layered environmental sounds depending on where you are. Forests sound like forests.

**Presence Footsteps** — More detailed and material-accurate footstep sounds. Grass, stone, wood — each sounds different.

**Sound Physics Remastered** — Adds reverb and echo based on your surroundings. Caves echo, open fields sound open.

**Simple Voice Chat** — Proximity-based voice chat. Talk to players near you in-game, voices fade with distance.

---

## 🎨 Visual & Performance

**Embeddium** — A rendering optimisation mod (Sodium port for Forge). Significantly improves frame rates.

**Oculus** — Shader support for Forge. Load your favourite shader packs for improved visuals.

**Sodium Options API** — Extends the video settings menu, used by Embeddium.

**Entity Culling** — Stops rendering entities you can't see, improving performance in busy areas.

**ImmediatelyFast** — Speeds up immediate mode rendering for better performance.

**Dynamic FPS** — Reduces resource usage when the game window is in the background.

**Model Fix** — Fixes minor visual glitches in certain block and item models.

**FerriteCore** — Reduces memory usage across the board. Helps keep RAM in check with a large modpack.

**ModernFix** — A broad collection of performance and loading time improvements.

**All The Leaks** — Patches various memory leaks to keep the game stable over long sessions.

---

## 🧰 Libraries & Dependencies

These mods don't add content on their own but are required for other mods to function.

- **Architectury** — Cross-platform mod library
- **Cloth Config** — Configuration screen framework
- **CoroUtil** — Utility library
- **CreativeCore** — Core library for Ambient Sounds and others
- **Framework** — General mod framework
- **GeckoLib** — Animation library used by several mods
- **GlitchCore** — Core library for various mods
- **Kotlin for Forge** — Kotlin language runtime for mods written in Kotlin
- **Platform** — Mod utility library

---

## 🤝 Social & Cosmetics

**Essential** — Adds cosmetics, a friends list, and some social features directly in the game client.

**Athena** — Cosmetics library used by Essential.

**Playmate** — Multiplayer-focused features and enhancements.

---

## 🛠️ Utility

**JEI (Just Enough Items)** — Shows crafting recipes and uses for every item in the game. Essential for modded play.

**Apotheosis** *(also listed above)* — Beyond enchanting, also adds useful quality-of-life improvements to spawners and other systems.

**Clumps** — Groups XP orbs together into single entities. Reduces lag and makes XP collection cleaner.

**Better Compatibility Checker** — Shows mod compatibility information in the mod list. Handy for debugging.
