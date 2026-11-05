<div align="center">

# ☀️ BIPVT-VR-Sim

### Interaktive Virtual-Reality-Simulation gebäudeintegrierter Photovoltaik-Thermie-Systeme (BIPVT)

[![Unity](https://img.shields.io/badge/Unity-URP-000000?logo=unity&logoColor=white)](https://unity.com/)
[![OpenXR](https://img.shields.io/badge/OpenXR-compatible-5C2D91)](https://www.khronos.org/openxr/)
[![Meta Quest](https://img.shields.io/badge/Meta%20Quest-Link%20%2F%20Air%20Link-0467DF?logo=meta&logoColor=white)](https://www.meta.com/quest/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D6?logo=windows&logoColor=white)](#-systemanforderungen)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Deutsch** · [English](README.en.md)

</div>

---

## 📖 Überblick

**BIPVT-VR-Sim** ist eine immersive VR-Anwendung, mit der sich der Aufbau und die Funktionsweise eines **gebäudeintegrierten Photovoltaik-Thermie-Systems (Building-Integrated Photovoltaic-Thermal, BIPVT)** im Maßstab 1:1 erleben lässt.

Ein BIPVT-System kombiniert zwei Funktionen in einem Bauteil der Gebäudehülle:

- ⚡ **Photovoltaik:** Erzeugung von elektrischem Strom aus Sonnenlicht
- 🔥 **Solarthermie:** Nutzung der Abwärme der Module über einen Wärmeträger (Absorber und Rohrsammler)

Die Simulation macht diese oft unsichtbaren Schichten **begreifbar**. Nutzerinnen und Nutzer können die Komponenten greifen, ein- und ausblenden und schrittweise erkunden. Sie eignet sich damit für **Lehre, Wissenstransfer, Messen und Planungsgespräche**.

---

## ✨ Features

| | Funktion | Beschreibung |
|---|---|---|
| 🥽 | **Volle VR-Immersion** | Begehbares 3D-Modell eines Gebäudes mit integriertem PVT-System |
| 🧩 | **Komponenten-Explorer** | PV-Module, PVT-Absorber und Rohrsammler einzeln sichtbar bzw. unsichtbar schalten |
| ✋ | **Natürliche Interaktion** | Bauteile mit den Controllern greifen, drehen und zurücksetzen (XR Interaction Toolkit) |
| 🔦 | **Visuelles Feedback** | Hervorhebung beim Zeigen und Auswählen, haptisches Feedback der Controller |
| 🚶 | **Fortbewegung** | Teleportation und kontinuierliche Bewegung, je nach Vorliebe |
| 📋 | **In-Game-Menü** | Steuerung der Ansichten und Materialien direkt in der VR |
| 🎒 | **Inventar** | Sammeln und Ablegen von Bauteilen zum Nachvollziehen des Aufbaus |

---

## 🎯 Anwendungsfälle

- **Hochschullehre:** Aufbau und Funktion von BIPV/BIPVT anschaulich vermitteln
- **Forschung und Wissenstransfer:** Ergebnisse aus Forschungsprojekten erlebbar machen
- **Planung und Beratung:** Bauherren, Architektinnen und Fachplanern das System im Gebäudekontext zeigen
- **Messen und Veranstaltungen:** Interaktiver Showcase für Solartechnik in der Gebäudehülle

---

## 💻 Systemanforderungen

| Komponente | Minimum | Empfohlen |
|---|---|---|
| Betriebssystem | Windows 10 (64-bit) | Windows 11 (64-bit) |
| Grafikkarte | NVIDIA GTX 1060 / AMD RX 580 | NVIDIA RTX 3060 oder besser |
| Arbeitsspeicher | 8 GB | 16 GB |
| VR-Headset | OpenXR-kompatibles PC-VR-Headset | Meta Quest 2 / 3 / Pro über Link oder Air Link |
| Runtime | Meta Quest Link **oder** SteamVR (als aktive OpenXR-Runtime) | |

---

## 🚀 Installation und Start

1. **Repository herunterladen**
   ```bash
   git clone https://github.com/ShervinRahnama/BIPVT-VR-Sim.git
   ```
   oder über **Code → Download ZIP** und anschließend entpacken.

2. **VR-Headset verbinden**
   - Meta Quest: Meta-Quest-Link-App starten und das Headset per Kabel oder Air Link verbinden.
   - Andere Headsets: SteamVR starten und als OpenXR-Runtime festlegen.

3. **Anwendung starten**
   ```
   VR-Game/BPVT-System.exe
   ```

> 💡 **Hinweis:** Der Ordner `BPVT-System_Data` muss im selben Verzeichnis wie die `.exe` liegen.

---

## 🎮 Steuerung

| Aktion | Controller |
|---|---|
| Teleportieren | Thumbstick nach vorne drücken, zielen, loslassen |
| Bewegen / Drehen | Linker / rechter Thumbstick |
| Objekt greifen | Grip-Taste |
| Auswählen / UI bedienen | Trigger |
| Menü öffnen | Menü-Taste (linker Controller) |

---

## 🗂️ Projektstruktur

```
BIPVT-VR-Sim/
├── VR-Game/
│   ├── BPVT-System.exe          # Startdatei der Anwendung
│   └── BPVT-System_Data/        # Spieldaten, Assets und Bibliotheken
├── LICENSE
└── README.md
```

---

## 🛠️ Technologie-Stack

- **Engine:** Unity mit Universal Render Pipeline (URP)
- **XR:** OpenXR, XR Interaction Toolkit, XR Management
- **Headset-Support:** Meta Quest (OpenXR Meta Quest Support)
- **Weitere Pakete:** Input System, ProBuilder, TextMeshPro, Animation Rigging
- **Sprache:** C#

---

## 🗺️ Roadmap

- [ ] Echtzeit-Visualisierung von Strom- und Wärmeertrag
- [ ] Variable Sonnenstände (Tages- und Jahresverlauf)
- [ ] Animation des Wärmeträgerflusses im Rohrsammler
- [ ] Standalone-Build für Meta Quest (Android)
- [ ] Mehrsprachigkeit (DE / EN)

---

## 🤝 Mitwirken

Feedback, Ideen und Bug-Reports sind willkommen! Bitte ein [Issue](https://github.com/ShervinRahnama/BIPVT-VR-Sim/issues) erstellen.

---

## 📄 Lizenz

Dieses Projekt steht unter der **MIT-Lizenz**. Details siehe [LICENSE](LICENSE).

---

## 👤 Autor

**Shervin Rahnama**
[![GitHub](https://img.shields.io/badge/GitHub-ShervinRahnama-181717?logo=github)](https://github.com/ShervinRahnama)

<div align="center">

⭐ Wenn dir das Projekt gefällt, freue ich mich über einen Stern!

</div>
