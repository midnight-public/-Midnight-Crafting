# 🌙 Midnight Crafting

A fresh crafting system for FiveM servers running **qb-core**. Place benches around the map, let players level up their crafting skill and unlock better recipes along the way. ✨

## ✨ Features
- 🎨 Modern night-themed UI with categories, search and a live progress bar
- 📈 XP and levels with a configurable curve, plus recipes locked by level
- ⏱️ Per-recipe craft time, XP reward and success chance
- 🛠️ In-game admin panel (`/admincrafting`) to create recipes, place benches and manage player XP
- 🔒 Benches can be restricted by job or recipe category, with optional map blips 📍
- 🛡️ Server-side validation of distance, job, level, materials and timing
- 🌍 English and Bulgarian included

## 📦 Requirements
- qb-core
- qb-inventory
- qb-target
- oxmysql

## 🚀 Quick start
1. Drop `midnight_crafting` into your `resources` folder
2. Add `ensure midnight_crafting` to your `server.cfg`
3. Start the server (tables and starter recipes are created automatically)
4. Type `/admincrafting` in game to add your first bench 🎉

Made with 💜 by **Midnight Scripts**
