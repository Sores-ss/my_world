### 🌍 Language  
🇬🇧 English • [🇫🇷 Français](./README.md)

# 🗺️ MY_WORLD – Isometric Terrain Editor (CSFML)

## 🎯 Project Description

**My_World** is an isometric map editor developed in **C** using **CSFML** (the official C binding for SFML).  
There is no “win” condition — the goal is to **dynamically shape a map**: raise or lower terrain, change tile textures, zoom, rotate... The player can freely explore a pseudo-3D environment.

Two main modes are available:
- **Terraform**: changes the height of tiles
- **Layers**: applies different textures to tiles

---

## 🎮 Controls & Gameplay

### 🕹️ Common Controls:

- **Mouse Wheel** or **Z / D** keys: zoom in / out
- **Left / Right Arrows**: rotate the map
- **F5**: toggle sound on/off
- **Left Click**: click on a button

### 🛠️ Terraform Mode:

- **Left Click**: raise a tile
- **Right Click**: lower a tile
- **+ / -**: increase or decrease map size
- **R**: reset the terrain

### 🎨 Layers Mode:

- **Left Click**: select a texture via a button or apply it to a tile

> 💡 **Personal note**:  
> This is one of my **first advanced graphical projects**.  
> It helped me understand the basics of isometric rendering, complex event handling, and how to build an interactive map editor.  
> Planned improvements include:  
> - better UI/UX,  
> - map saving system,  
> - image export feature,  
> - and improved texture handling.

---

## 🛠️ Installation & Compilation

### 📦 Requirements

```bash
sudo apt-get install libcsfml-dev
```
▶️ Run the application
```bash
make
./my_world
```
## 👨‍💻 Authors

- [Arthur Vignes](https://github.com/4rthurV)  
- Eros Delianne Le Boucher  

1st-year students at **EPITECH Lille** (Class of 2029)  
This project was developed as part of the **B-MUL-200** module *(advanced C graphics with CSFML)*.

> 📌 This repository is **personal**, **unofficial**, and shared for **educational purposes only**.

