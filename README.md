# 🎮 GTA Image Library

A simple image library for GTA V modding resources. This project provides fast and direct links to images for vehicles, peds, weapons, and manufacturers, all optimized in `.webp` format.

## 🔍 What’s Included

- 🐗 Ped Images
- 🚗 Vehicle Images
- 🏢 Manufacturer Logos
- 🔫 Weapon Icons

Example Preview:

| Ped | Vehicle | Manufacturer | Weapon |
|-----|---------|--------------|--------|
| ![Boar](https://raw.githubusercontent.com/Jordgubbee/gta-images/main/images/peds/a_c_boar.webp) | ![T20](https://raw.githubusercontent.com/Jordgubbee/gta-images/main/images/vehicles/t20.webp) | ![Ubermacht](https://raw.githubusercontent.com/Jordgubbee/gta-images/main/images/manufacturers/ubermacht.webp) | ![Ceramic Pistol](https://raw.githubusercontent.com/Jordgubbee/gta-images/main/images/weapons/weapon_ceramicpistol.webp) |

---

## 🧩 How to Use

### 🔗 Dynamic URL Example (Recommended)
```lua
local model = vehicle.model:lower()
local url = string.format("https://raw.githubusercontent.com/Jordgubbee/gta-images/main/images/vehicles/%s.webp", model)
```

### 📦 For Peds
```lua
local ped = "a_c_boar"
local url = string.format("https://raw.githubusercontent.com/Jordgubbee/gta-images/main/images/peds/%s.webp", ped)
```

---

## 📁 Structure

```
images/
├── vehicles/
├── peds/
├── manufacturers/
└── weapons/
```

---

## 📤 Contribute

Found a missing model or want to add more images? Open a pull request or fork the repo.

## 📜 License

Free to use in any GTA V development. No attribution required.
