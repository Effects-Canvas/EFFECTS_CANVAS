# EFFECTS CANVAS™
**The High-Performance VST Host for Creative Sound Design**
EFFECTS CANVAS is an intuitive audio plugin host designed specifically for guitarists, vocalists, bassists, and sound engineers. It provides a seamless environment to build, manage, and perform with your custom signal chains—as if you were painting on a canvas.

---

## Key Features
- **Visual Workflow:** Build complex effect chains with a modern, intuitive interface.
- **Low-Latency Engine:** Optimized for live performance using high-performance C++/JUCE processing.
- **VST3 Support:** Full compatibility with your favorite third-party audio plugins.
- **NAM Support:** Load and use `.nam` (Neural Amp Modeler) preset files to emulate real-world amplifiers and gear with neural network accuracy.
- **IR Support:** Load impulse response (`.wav`) files for cabinet simulation, reverb, and custom acoustic spaces.

---

## NAM (Neural Amp Modeler)
EFFECTS CANVAS supports `.nam` preset files, allowing you to load high-quality neural amp models directly into your signal chain.

- Powered by the **NeuralAudio** library (MIT License, © Mike Oliphant).
- Internally based on **Neural Amp Modeler Core** (© Steven Atkinson).

NAM is an open-source project licensed under the [MIT License](https://opensource.org/licenses/MIT). For more information, visit the [Neural Amp Modeler GitHub page](https://github.com/sdatkinson/neural-amp-modeler).

---

## IR (Impulse Response)
EFFECTS CANVAS supports standard impulse response files, allowing you to load cabinet simulations, room reverbs, and other convolution-based effects directly into your signal chain.

- Compatible with standard `.wav` IR files from popular IR libraries.
- Ideal for pairing with NAM amp models to complete your guitar or bass tone.

---

## Tested Latency Chart

### macOS — MacBook Pro M4 Pro / 24GB RAM / MOTU M2
| Buffer size | Latency (ms) |
| ----------: | -----------: |
| 16  | 3.126  |
| 32  | 3.792  |
| 64  | 5.126  |
| 128 | 7.792  |
| 256 | 13.126 |
| 512 | 23.792 |

### Windows — Intel i7 8700 / 16GB RAM / MOTU M2 ASIO
| Buffer size | Latency (ms) |
| ----------: | -----------: |
| 16  | 2.916  |
| 32  | 3.563  |
| 64  | 4.895  |
| 128 | 7.563  |
| 256 | 12.916 |
| 512 | 23.563 |

> These values were measured using RTL Utility and may vary depending on the user's system configuration.

---

## System Requirements
|                  | macOS                                                            | Windows         |
|------------------|------------------------------------------------------------------|-----------------|
| **OS**           | macOS 11.0 (Big Sur) or later                                    | Windows 7 or later |
| **Architecture** | Native support for Apple Silicon (M1/M2/M3/M4) and Intel x86_64  | x86 / x64       |

---

## Installation
1. Go to the [Releases](https://github.com/Effects-Canvas/EFFECTS_CANVAS) page.
2. Download the latest `.dmg` (macOS) or `.exe` installer (Windows).
3. **macOS:** Open the `.dmg` file and drag EFFECTS CANVAS into your Applications folder.
4. **Windows:** Run the `.exe` installer and follow the on-screen instructions.

---

## Acknowledgements
EFFECTS CANVAS is built with the help of the following open-source projects:

- **[NeuralAudio](https://github.com/mikeoliphant/NeuralAudio)** by Mike Oliphant — MIT License
- **[Neural Amp Modeler Core](https://github.com/sdatkinson/NeuralAmpModelerCore)** by Steven Atkinson — MIT License
- **JUCE** — Audio application framework

We gratefully acknowledge the work of these developers and the wider open-source audio community.

---

## Support & Contact
For bug reports, feature requests, or business inquiries:
- **Email:** [contact@effectscanvas.com](mailto:contact@effectscanvas.com)
- **Website:** [www.effectscanvas.com](https://www.effectscanvas.com)

---

## ⚖️ License
Copyright © 2026 EFFECTS CANVAS. All rights reserved.
This software is provided for personal use only. The source code is proprietary. Redistribution, reverse engineering, or modification of the binary is strictly prohibited without prior written permission.
