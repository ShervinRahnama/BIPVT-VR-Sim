<div align="center">

# ☀️ BIPVT-VR-Sim

### Interactive Virtual Reality Simulation of Building-Integrated Photovoltaic-Thermal Systems (BIPVT)

[![Unity](https://img.shields.io/badge/Unity-URP-000000?logo=unity&logoColor=white)](https://unity.com/)
[![OpenXR](https://img.shields.io/badge/OpenXR-compatible-5C2D91)](https://www.khronos.org/openxr/)
[![Meta Quest](https://img.shields.io/badge/Meta%20Quest-Link%20%2F%20Air%20Link-0467DF?logo=meta&logoColor=white)](https://www.meta.com/quest/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D6?logo=windows&logoColor=white)](#-system-requirements)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**English** · [Deutsch](README.md)

</div>

---

## 📖 Overview

**BIPVT-VR-Sim** is an immersive VR application that lets you experience the design and operation of a **Building-Integrated Photovoltaic-Thermal (BIPVT) system** at 1:1 scale.

A BIPVT system combines two functions in a single element of the building envelope:

- ⚡ **Photovoltaics:** generating electricity from sunlight
- 🔥 **Solar thermal:** harvesting the modules' waste heat via a heat-transfer fluid (absorber and pipe manifold)

The simulation makes these normally hidden layers **tangible**: users can grab components, show or hide them and explore the system step by step. This makes it suitable for **teaching, knowledge transfer, trade fairs and planning discussions**.

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🥽 | **Full VR immersion** | Walkable 3D model of a building with an integrated PVT system |
| 🧩 | **Component explorer** | Toggle PV modules, PVT absorber and pipe manifold individually |
| ✋ | **Natural interaction** | Grab, rotate and reset components with the controllers (XR Interaction Toolkit) |
| 🔦 | **Visual feedback** | Highlighting on hover and selection, haptic controller feedback |
| 🚶 | **Locomotion** | Teleportation and continuous movement, whichever you prefer |
| 📋 | **In-game menu** | Control views and materials directly in VR |
| 🎒 | **Inventory** | Collect and place components to understand the build-up |

---

## 🎯 Use Cases

- **University teaching:** explain BIPV/BIPVT design and function visually
- **Research and knowledge transfer:** make research results tangible
- **Planning and consulting:** show the system in its building context to clients, architects and engineers
- **Trade fairs and events:** interactive showcase for solar technology in the building envelope

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| Operating system | Windows 10 (64-bit) | Windows 11 (64-bit) |
| Graphics card | NVIDIA GTX 1060 / AMD RX 580 | NVIDIA RTX 3060 or better |
| Memory | 8 GB | 16 GB |
| VR headset | OpenXR-compatible PC VR headset | Meta Quest 2 / 3 / Pro via Link or Air Link |
| Runtime | Meta Quest Link **or** SteamVR (as active OpenXR runtime) | |

---

## 🚀 Installation and Launch

1. **Download the repository**
   ```bash
   git clone https://github.com/ShervinRahnama/BIPVT-VR-Sim.git
   ```
   or use **Code → Download ZIP** and extract it.

2. **Connect your VR headset**
   - Meta Quest: start the Meta Quest Link app and connect via cable or Air Link.
   - Other headsets: start SteamVR and set it as the OpenXR runtime.

3. **Launch the application**
   ```
   VR-Game/BPVT-System.exe
   ```

> 💡 **Note:** The `BPVT-System_Data` folder must be in the same directory as the `.exe`.

---

## 🎮 Controls

| Action | Controller |
|---|---|
| Teleport | Push thumbstick forward, aim, release |
| Move / turn | Left / right thumbstick |
| Grab object | Grip button |
| Select / use UI | Trigger |
| Open menu | Menu button (left controller) |

---

## 🗂️ Project Structure

```
BIPVT-VR-Sim/
├── VR-Game/
│   ├── BPVT-System.exe          # Application executable
│   └── BPVT-System_Data/        # Game data, assets and libraries
├── LICENSE
└── README.md
```

---

## 🛠️ Tech Stack

- **Engine:** Unity with Universal Render Pipeline (URP)
- **XR:** OpenXR, XR Interaction Toolkit, XR Management
- **Headset support:** Meta Quest (OpenXR Meta Quest Support)
- **Other packages:** Input System, ProBuilder, TextMeshPro, Animation Rigging
- **Language:** C#

---

## 🗺️ Roadmap

- [ ] Real-time visualisation of electrical and thermal yield
- [ ] Variable sun positions (daily and annual course)
- [ ] Animated heat-transfer fluid flow in the pipe manifold
- [ ] Standalone build for Meta Quest (Android)
- [ ] Multilingual UI (DE / EN)

---

## 🤝 Contributing

Feedback, ideas and bug reports are welcome! Please open an [issue](https://github.com/ShervinRahnama/BIPVT-VR-Sim/issues).

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 👤 Author

**Shervin Rahnama**
[![GitHub](https://img.shields.io/badge/GitHub-ShervinRahnama-181717?logo=github)](https://github.com/ShervinRahnama)

<div align="center">

⭐ If you like this project, a star is much appreciated!

</div>
