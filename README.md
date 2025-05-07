## **Catch ’Em All** [👉 Click for More](https://www.curseforge.com/members/cesardev/projects)

The **Catch ’Em All** addon is a **Minecraft Bedrock** addon that introduces a powerful *mob catcher* tool to capture and release mobs with ease. Designed with performance, gameplay balance, and language support in mind, it enables players to carry up to **10 mobs** inside a single item — the **Catcher** — and release them wherever needed!

![Catch 'Em All Addon Image](https://i.imgur.com/84SuG7T.png)

<p align="center">
  <img src="https://img.shields.io/discord/1261813234403377153?style=for-the-badge&logo=discord&logoColor=white&labelColor=3182CE&color=66b3ff" alt="Discord">
  <a href="https://github.com/ByCesarDev/catch-em-all">
    <img src="https://img.shields.io/static/v1?label=&message=Github&color=66b3ff&labelColor=3182CE&style=for-the-badge&logo=github&logoColor=white" alt="Github">
  </a>
  <a href="https://ko-fi.com/bycesarkun">
    <img src="https://img.shields.io/static/v1?label=&message=Support&color=66b3ff&labelColor=3182CE&style=for-the-badge&logo=kofi&logoColor=white" alt="Support">
  </a>
  <a href="https://github.com/ByCesarDev/catch-em-all?tab=MIT-1-ov-file">
    <img src="https://img.shields.io/static/v1?label=MIT&message=License&color=66b3ff&labelColor=3182CE&style=for-the-badge" alt="MIT License">
  </a>
</p>

---

## **What Does Catch ’Em All Do?**

With the **Catcher**, you can capture almost any mob (excluding bosses and players), store up to **10 mobs**, and release them later using an intuitive form-based UI. It works in both English and Spanish and includes support for **custom named mobs**, **durability limits**, and **blocked mobs/blocks** to preserve gameplay balance.

---

## **Key Features**

- ✅ Capture mobs by simply clicking on them with the **Catcher**.
- ✅ Release mobs by clicking on a block with the Catcher.
- ✅ Store up to **10 mobs** per catcher, including their health and custom name.
- ✅ Full **form-based UI** for releasing mobs from a list.
- ✅ **Durability-based** system — more powerful mobs cost more to store.
- ✅ **Multilingual support**: English & Spanish with in-game language switch.
- ✅ Prevents abuse via a list of **blocked mobs** and **blocked blocks**.
- ✅ Supports **custom mobs** from other addons. These appear with a **default Dev icon**, while vanilla mobs show a grass icon.

---

## **Practical Examples**

- 🔹 Capture a group of sheep and transport them to a new base without leads or boats.
- 🔹 Store your tamed mobs safely before exploring a dangerous biome.
- 🔹 Use it in mini-games or adventure maps to design custom mob-based puzzles.

---

## **🛠️ Crafting Recipe**

The Catcher is crafted using **2 sticks** and **2 strings**. Simple, survival-friendly, and early-game accessible.

![Catcher Crafting Recipe](https://i.imgur.com/1mIMLgW.png)

---

## **🧩 Addon Versions: Normal vs. Classic**

The addon comes in two versions to ensure compatibility across different setups:

![Normal vs Classic UI Comparison](https://i.imgur.com/TPr5AfT.jpeg)

- **Normal Version:** Adds a customized UI for a smoother, modern experience. ⚠️ May conflict with other addons that modify the *server form UI*.
- **Classic Version:** Keeps the original vanilla UI intact. Fully compatible with all addons, ideal for realms or multiplayer servers with strict UI rules.

---

## **Why Use Catch ’Em All?**

- ✔️ Makes mob transportation quick, easy, and immersive.
- ✔️ Allows storing mobs without needing to use spawn eggs or commands.
- ✔️ Flexible for survival gameplay and map creators.
- ✔️ Minimalistic and lore-friendly item-based mechanic.

---

## **How to Use**

1. Equip the **Catcher** item (`Universal Net`).
2. Right-click a mob to attempt capturing it.
3. Right-click a **non-container block** to release one or more captured mobs.
4. Shift + right-click a block to open the **language selection UI**.

> ⚠️ **Note:** Some mobs like the Ender Dragon, Warden, and players are **blocked** from being captured.

---

## **Compatibility**

- ✅ Compatible with most Minecraft worlds and addons.
- ✅ Works in realms and single-player.
- ✅ Detects and supports **custom mobs** from other addons (if not blocked).

---

## **Technical Details**

- **Max Mobs:** 10 per Catcher  
- **Max Health:** 250 HP per captured mob  
- **Supported Languages:** English, Español  
- **Script file:** `scripts/main.js`  
- Captured mobs are saved using Minecraft’s **structure system**, including name and HP.

---

## ⚙️ **Configuration Settings**

These constants define the behavior and restrictions of the mob catcher system in `scripts/main.js`:


// System language: Use "en" for English or "es" for Spanish.
- ```const LANGUAGE = "es";```

// ID of the custom item catcher. Make sure it matches the registered item.
- ```const CATCHER_ID = "multiversemc:net";```

// Max number of mobs that can be caught per catcher.
- ```const MAX_MOBS = 10;```

// Max health allowed per captured mob.
- ```const MAX_HEALTH = 250;```

// List of entities that are blocked and cannot be captured.
const BLOCKED_MOBS = [ 
  'minecraft:armor_stand',
  'minecraft:ender_dragon',
  'minecraft:warden',
  'minecraft:wither',
  'minecraft:player'
]; 


---

🌐 Language Configuration

To switch between English and Spanish, simply Shift + Right-Click any block while holding the Catcher to open the language settings menu.

This feature is integrated seamlessly and works without interfering with other UI components (unless using the normal version with other UI mods).




---

Addon Packs

You can include this addon in public or private addon packs. Please do not re-upload it to other websites without permission. Always credit the original CurseForge or MCPEDL page when sharing.

<p align="center">
  <strong>Have suggestions or found a bug? Join our <a href="https://discord.com/invite/z5wshN7Xgm" target="_blank">Discord Server</a> to get support and chat with the community!</strong>
</p>
