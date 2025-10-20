# 🏁 PROJECT OVR//DRV

**OVR-DRV** (pronounced _OVERDRIVE_) is a stylized high-speed racing experience built in **Unreal Engine 5.6**, exploring the intersection of speed, control, and pure mechanical rhythm.

---

## 🚧 Project Overview

| Category      | Description       |
| ------------- | ----------------- |
| Engine        | Unreal Engine 5.6 |
| Language      | C++ & Blueprints  |
| Platform      | PC and consoles   |
| Current Phase | Pre-Production    |

---

## 🧩 Code & Asset Conventions

**Prefix:** `OD_`  
All in-game assets and code use the `OD` prefix to maintain consistent project identity.

**Examples:**

- Classes → `ODBaseVehicle`, `ODDriftComponent`
- Blueprints → `BP_OD_SportsCar`, `WBP_OD_HUD`
- Assets → `M_OD_CarPaint`, `NS_OD_DriftSmoke`

---

## 🗂️ Folder Structure

/Source/OVRDRV/
├── Core/
├── Vehicles/
├── Systems/
├── Tracks/
└── Interfaces/

/Content/OD/
├── Blueprints/
├── Materials/
├── Meshes/
├── Sounds/
├── FX/
└── Data/

### Source

# 🗂️ Git Branching Guide – PROJECT OVR-DRV

---

## 💾 Version Control

The project uses **Git + Git LFS**.  
Recommended `.gitignore`: [Unreal Engine Standard Ignore](https://github.com/github/gitignore/blob/main/UnrealEngine.gitignore)

Main Branches:

- `main` — stable release
- `dev` — active development
- `feature/*` — individual features (e.g. `feature/drift-system`)

## 🌳 Branch Structure

| Branch Name | Purpose                                  |
| ----------- | ---------------------------------------- |
| `main`      | ✅ Production-ready, stable builds only  |
| `dev`       | 🧪 Active development integration branch |
| `feature/*` | 🔧 New features or systems               |
| `hotfix/*`  | 🛠️ Emergency bugfixes (optional)         |

---

| Type         | Example                   |
| ------------ | ------------------------- |
| Features     | `feature/vehicle-spawner` |
| Bugfixes     | `feature/fix-speed-curve` |
| Hotfixes     | `hotfix/input-bug`        |
| Experimental | `feature/test-new-fx`     |

---

## 📘 Documentation

Located in `/Docs/`:

- `GDD/PROJECT_OVRDRV_GDD.md`
- `DevLogs/`
- `Branding/`

---

## 🔧 Setup

1. Clone repository
2. Run `Setup.bat` and `GenerateProjectFiles.bat`
3. Open `OVRDRV.uproject`
4. Build and launch in Unreal Engine 5.6

---

## 🧠 Credits

**Game Design / Development:** [KLAUS 117] / [AYOBAMI OYESIKU]
**Engine:** Unreal Engine 5.6  
**Status:** In Development

---

> _PROJECT OVR-DRV // A study in motion, precision, and control._
