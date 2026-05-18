# AI as Catalyst | AEROSONIC SONIFIER

## Unsupervised AI Weather Sonification System

[![FCT Grant](https://img.shields.io/badge/FCT-2024.09158.CEECIND-green.svg)](https://www.fct.pt)
[![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)]()
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2B-0078d7.svg)]()
[![Research](https://img.shields.io/badge/Research-INET--md-blue.svg)](https://www.inetmd.pt)
[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)]()

---

> **AEROSONIC SONIFIER** transforms meteorological and atmospheric data into real-time MIDI music using unsupervised artificial intelligence (Isolation Forest) for climate anomaly detection.

---

## Table of Contents

- [What is AEROSONIC SONIFIER?](#what-is-aerosonic-sonifier)
- [Unsupervised AI](#unsupervised-ai-isolation-forest)
- [Performance Controls](#performance-controls)
- [Weather Presets](#weather-presets)
- [Dreaming AI](#dreaming-ai---13-archetypes)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Research Context](#research-context)
- [System Architecture](#system-architecture)
- [Requirements](#requirements)
- [License](#license)
- [Contact](#contact)

---

## What is AEROSONIC SONIFIER?

A **scientific sonification system** developed as part of the **"AI as Catalyst"** project (FCT Grant 2024.09158.CEECIND) at INET-md, University of Aveiro.

### Weather to Music Mapping

| Weather Data | Musical Transformation |
|:------------|:----------------------|
| **Temperature** | Harmonic root and drone register |
| **Wind speed** | Rhythmic density and filter cutoff |
| **Precipitation** | Granular rain textures and reverb intensity |
| **Atmospheric pressure** | Harmonic tension and dissonance |
| **Relative humidity** | Release times and texture evolution |
| **Weather conditions** | Preset selection and mood |

---

## Unsupervised AI (Isolation Forest)

The system integrates a **climate anomaly detector** based on Isolation Forest, an unsupervised AI technique that operates entirely locally.

### AI Capabilities

| Feature | Description |
|:--------|:------------|
| **Self-learning** | No prior training data required |
| **Pattern discovery** | Automatically identifies "normal weather" baselines |
| **Continuous adaptation** | Auto-retrains every 100 observations |
| **Anomaly detection** | Identifies rare and extreme weather events |

### Musical Effects of Anomalies

| Severity | Anomaly Score | Musical Effect |
|:---------|:-------------|:---------------|
| Mild | 0.3 - 0.5 | Glitches in DataMutator |
| Moderate | 0.5 - 0.7 | Increased rhythm density + filter sweep |
| Severe | > 0.7 | STORM modulation + Intense Glitch + Visual flash |

---

## Performance Controls

Real-time adjustable parameters for expressive control:

| Control | Range | Default | Musical Effect |
|:--------|:-----:|:-------:|:---------------|
| **Tick Speed** | 50-250ms | 166ms | Note velocity and energy |
| **Rhythm Density** | 30-90% | 60% | Quantity of rhythmic notes |
| **Rain Density** | 10-70% | 40% | Density of rain droplets |
| **Drone Smooth** | 0.80-0.99 | 0.95 | Harmonic field smoothness |
| **Swing** | 0-50% | 15% | Shuffle/groove feel |
| **Humanize** | 0-100% | 20% | Microtiming variations |
| **Vibrato** | 0-100% | 30% | Pitch modulation depth |
| **Harmonic Drift** | 0-100% | 25% | Microtonal evolution |

### Intensity Profiles

| Profile | Tick Speed | Rhythm | Rain | Drone Smooth |
|:--------|:----------:|:------:|:----:|:-------------:|
| Ambient | 220ms | 30% | 15% | 0.98 |
| Chillout | 180ms | 50% | 30% | 0.96 |
| Normal | 166ms | 60% | 40% | 0.95 |
| Electronica | 140ms | 65% | 45% | 0.94 |
| Techno | 100ms | 75% | 50% | 0.90 |
| Drum&Bass | 70ms | 85% | 60% | 0.85 |
| Extreme | 50ms | 90% | 70% | 0.80 |

---

##  Weather Presets

Temporary presets (10 seconds) that override real-time weather data:

| Key | Preset | Temp | Wind | Rain | Musical Style |
|:---:|:-------|:----:|:----:|:----:|:---------------|
| A | Severe Storm | 10°C | 55 km/h | 120 mm | Dramatic, Intense |
| B | Flood | 16°C | 20 km/h | 180 mm | Chaotic, Dense |
| C | Extreme Heat | 48°C | 3 km/h | 0 mm | Intense, Dry |
| D | Extreme Cold | -25°C | 5 km/h | 0 mm | Icy, Ethereal |
| E | Gale | 14°C | 65 km/h | 0 mm | Rhythmic, Pulsing |
| F | Tornado | 22°C | 80 km/h | 60 mm | Chaotic, Turbulent |
| G | Extreme Drought | 42°C | 15 km/h | 0 mm | Arid, Static |
| H | Ice Storm | -8°C | 30 km/h | 40 mm | Ethereal, Glassy |

> **Note:** Presets are temporary. After 10 seconds, the system automatically returns to AUTO mode (live weather data from Open-Meteo).

---

## Dreaming AI - 13 Archetypes

The Dreaming AI introduces generative variations with 8% base probability:

| Dream | Temp Offset | Precip × | Wind × | Harmonic Field | Character |
|:------|:-----------:|:--------:|:------:|:---------------|:----------|
| Crystalline | -8°C | 0.0 | 0.2 | DREAM | Pure, Glassy |
| Amethyst | +2°C | 1.5 | 1.3 | STORM | Intense, Purple |
| Obsidian | -2°C | 0.2 | 0.4 | TENSE | Dark, Sharp |
| Inferno | +12°C | 0.0 | 1.6 | CHAOS | Fiery, Wild |
| Gravity | -4°C | 2.0 | 1.8 | STORM | Heavy, Dense |
| Nebula | 0°C | 0.8 | 0.5 | DREAM | Spacious, Cosmic |
| Thunderstorm | -2°C | 3.0 | 2.5 | STORM | Powerful, Electric |
| Aurora | -15°C | 0.1 | 1.2 | DREAM | Luminous, Flowing |
| Volcano | +18°C | 0.0 | 1.0 | CHAOS | Explosive, Erupting |
| Mirage | +6°C | 0.0 | 0.8 | TENSE | Shimmering, Unstable |
| Abyss | -6°C | 0.5 | 0.3 | TENSE | Deep, Dark |
| Whirlwind | 0°C | 0.5 | 3.0 | CHAOS | Spinning, Fast |
| Stardust | -10°C | 0.0 | 0.0 | DREAM | Sparkling, Celestial |

**Dream Characteristics:**
- Duration: 20-60 seconds
- Cooldown: 15 seconds between dreams
- Sound effects: Chimes (Ch.15), Pads (Ch.14), Drones (Ch.13)

---

## Quantum State Simulation

A dramatic implementation of quantum-inspired probabilistic events:

| Parameter | Description |
|:----------|:------------|
| **Amplitude** (0-1) | Probability of measurement/collapse |
| **Phase** (0-2π) | Position in quantum cycle |
| **Energy** (0-1) | Excitation level |
| **Uncertainty** | Heisenberg principle simulation |
| **Collapse Probability** | 15% — triggers musical events |
| **Tunneling** | Smooth transitions between states |

**Particle Types:** ELECTRON, PHOTON, NEUTRINO, HIGGS, TACHYON

---

## Keyboard Shortcuts

| Key | Action | Description |
|:---:|:-------|:------------|
| `A` - `H` | Weather Presets | Load predefined weather conditions |
| `D` | Force Dream | Manually trigger Dreaming AI |
| `P` | MIDI Panic | Emergency all-notes-off (cutoff) |
| `V` | Video Output | Toggle projector/second screen mode |
| `F` | Fullscreen | Toggle fullscreen display |
| `H` | Info Overlay | Toggle heads-up display |
| `M` | Data Mutator | Toggle mutation effects |
| `I` | AI Statistics | Show AI anomaly detection stats |
| `Ctrl` + `Shift` + `R` | Reset AI | Reinitialize Isolation Forest |
| `Ctrl` + `S` | Save Config | Save current parameters |
| `Ctrl` + `Q` | Quit | Exit application |

---

## Research Context

| Field | Information |
|:------|:------------|
| **Project** | AI as Catalyst: Transformative Impacts on Digital Performance, Computer Music, and Cultural Creativity |
| **Funding Agency** | Fundação para a Ciência e a Tecnologia (FCT) |
| **Grant Number** | 2024.09158.CEECIND |
| **Period** | March 2026 — December 2029 |
| **Host Institution** | INET-md \| University of Aveiro |
| **Research Group** | CPIA (Creation, Performance, and Innovation in Art) |
| **Principal Investigator** | Hugo Paquete |

### Partner Institutions

| Institution | Role |
|:------------|:-----|
| University of Aveiro | Coordinating Institution |
| INET-md | Research Unit |
| Absonus Lab | Research Partner |
| Planetário do Porto – CCV | Outreach Partner |

---

## System Architecture

┌─────────────────────────────────────────────────────────────────────────────┐
│ WEATHER DATA LAYER │
│ Open-Meteo API / NOAA / Fallback │
└─────────────────────────────────────────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ UNSUPERVISED AI (Isolation Forest) │
│ Anomaly Detection │ Self-learning │ Continuous Retraining │
└─────────────────────────────────────────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ DREAMING AI (13 Archetypes) │
│ Generative Variations │ CC Modulation │ Sound Effects │
└─────────────────────────────────────────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ QUANTUM STATE SIMULATION │
│ Amplitude │ Phase │ Energy │ Collapse (15%) │
└─────────────────────────────────────────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ HARMONIC FIELD │
│ 5 Drone Voices (Bass, Mid, High, Pad, Texture) │
└─────────────────────────────────────────────────────────────────────────────┘
│
┌─────────────────┼─────────────────┐
▼ ▼ ▼
┌──────────────┐ ┌──────────────┐ ┌──────────────┐
│ RHYTHM │ │ RAIN │ │ DRONES │
│ Euclidean │ │ Granular │ │ Harmonic │
│ Ghost Notes │ │ 4 Layers │ │ Field │
│ Polyrhythms │ │ Pitch Drift │ │ 5 Voices │
└──────────────┘ └──────────────┘ └──────────────┘
│ │ │
└─────────────────┼─────────────────┘
▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ CC BANK (8 Controllers) │
│ Volume │ Filter │ Reverb │ Expression │ Pan │ Resonance │ Attack │ Release
└─────────────────────────────────────────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────────────────────────────────────────┐
│ MIDI OUTPUT + VISUALIZER │
│ Real-time MIDI │ Sandstorm Visualizer │ Video Output │
└─────────────────────────────────────────────────────────────────────────────┘


---

## Requirements

| Component | Minimum | Recommended |
|:----------|:--------|:------------|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **RAM** | 4 GB | 8 GB |
| **Processor** | Intel Core i5 | Intel Core i7 / AMD Ryzen 7 |
| **MIDI Output** | Software synth (e.g., FluidSynth) | Hardware MIDI synthesizer |
| **Internet** | Required for weather data | Broadband connection |
| **Display** | 1366×768 | 1920×1080 or higher |

---

## Technical Specifications

| Component | Specification |
|:----------|:--------------|
| **AI Model** | Isolation Forest (scikit-learn) |
| **Contamination** | 10% (expected anomaly proportion) |
| **Window Size** | 500 observations |
| **Retraining** | Every 100 new observations |
| **Features** | 7 dimensions (temp, wind, rain, pressure, humidity...) |
| **Anomaly Cooldown** | 1.0 second (high sensitivity) |
| **Anomaly Decay** | 8.0 seconds (long-lasting effects) |
| **Drone Release** | 1.2 seconds |
| **Watchdog Timer** | 30 seconds |

---

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License**.


**For commercial licensing inquiries**, please contact: **hugopaquete@ua.pt**

---

## Citation

If you use AEROSONIC SONIFIER in academic research, please cite:

```bibtex
@software{paquete2026aerosonic,
  author = {Paquete, Hugo},
  title = {AEROSONIC SONIFIER: Unsupervised AI Weather Sonification System},
  year = {2026},
  institution = {INET-md, University of Aveiro},
  note = {FCT Grant 2024.09158.CEECIND},
  url = {https://github.com/hugopaquete/AI-as-Catalyst-Aerosonic-Sonifier}
}

*"This work was supported by FCT grant 2024.09158.CEECIND (AI as Catalyst project, University of Aveiro/INET-md)."*

Hugo Paquete, PhD
Principal Investigator

Email	hugopaquete@ua.pt
Website	www.hugopaquete.com
Institution	University of Aveiro | INET-md
Address	Campus Universitário de Santiago, 3810-193 Aveiro, Portugal
Phone	(+351) 234 370 389 (ext. 23700)

Links
FCT — Fundação para a Ciência e a Tecnologia
University of Aveiro
INET-md — Institute of Ethnomusicology
Department of Communication and Art (DeCA)

Acknowledgments
Fundação para a Ciência e a Tecnologia (FCT) for funding through grant 2024.09158.CEECIND
INET-md for institutional support and research infrastructure
University of Aveiro for hosting the research
DeepSeek AI for collaborative development

<div align="center"> <sub> <strong>© 2026 Hugo Paquete</strong> | FCT Grant 2024.09158.CEECIND<br> <strong>AI as Catalyst</strong> — INET-md | University of Aveiro<br> <strong>Version 1.0.0</strong> | May 2026 </sub> </div> ```
