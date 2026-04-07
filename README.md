# VSC — Visual Style Compiler

![VSC Logo](./assets/logo.png)  
**Subtitle:** Visual Style Compiler with **VSC Studio** (UI)  
**Engine:** **VSC Engine** (compiler logic)

---

![GitHub stars](https://img.shields.io/github/stars/yourusername/vsc?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/vsc?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/vsc)
![License](https://img.shields.io/github/license/yourusername/vsc)
![Release](https://img.shields.io/github/v/release/yourusername/vsc)

---

## 🌟 Overview

**VSC** (Visual Style Compiler) is a deterministic AI visual style system that allows creators to define a **Visual DNA**, then compile model-specific prompts that produce consistent, high-quality outputs.  

- **VSC Studio** — Interactive UI for creating and managing style profiles.  
- **VSC Engine** — Compiler logic that generates precise prompts for multiple AI models.  

Think of it as a “Photoshop for AI prompts,” but deterministic, programmable, and style-consistent.

---

## 🎥 Demo

![VSC Demo GIF](./assets/demo.gif)  
*Watch VSC Studio compile prompts from a Cinematic Cyberpunk style profile.*

---

## 🎨 Dark/Light Mode Previews

| Dark Mode | Light Mode |
|-----------|------------|
| ![Dark Mode Screenshot](./assets/screenshot-dark.png) | ![Light Mode Screenshot](./assets/screenshot-light.png) |

---

## ⚡ Features

### Profile Management
- Create, duplicate, delete, import/export style profiles
- Lock style fields for deterministic outputs
- Switch between profiles seamlessly

### Style Compilation
- Define `medium`, `aesthetic`, `palette`, `composition`, `camera`, `lighting`, `texture`, `exclusions`, `quality`
- Compile prompts for:
  - **DALL·E 3**
  - **Midjourney**
  - **Stable Diffusion**
- Maintain visual consistency across all scenes

### Scene Payload
- Separate variable content (subject, action, environment) from style DNA
- Mix static and dynamic elements for high-quality outputs

### Output & Interaction
- Preview positive and negative prompts in real-time
- Copy prompts to clipboard in one click
- Optional negative prompts for Stable Diffusion

---

## 🚀 Installation

**Option 1: Clone & Open**
```bash
git clone https://github.com/yourusername/vsc.git
cd vsc
open index.html

Option 2: Local Web Server

git clone https://github.com/yourusername/vsc.git
cd vsc
python3 -m http.server 8080
# Visit http://localhost:8080

No build required — VSC Studio runs fully in the browser.

⸻

📝 Usage
	1.	Open VSC Studio in your browser
	2.	Select or create a Visual DNA profile
	3.	Lock fields you want deterministic
	4.	Fill the scene payload (subject, action, environment)
	5.	Choose target model: DALL·E, Midjourney, or Stable Diffusion
	6.	Click Generate Prompt (powered by VSC Engine)
	7.	Copy prompt or export profile as JSON

⸻

🏗 Architecture

VSC
├── VSC Studio (UI)
│   ├── Profile Management
│   ├── Style DNA Editor
│   ├── Scene Payload Editor
│   └── Output Display
└── VSC Engine (Compiler)
    ├── DALL·E Compiler
    ├── Midjourney Compiler
    └── Stable Diffusion Compiler

	•	Profiles: Style DNA + lock states
	•	Scene Payload: Variable content separate from style
	•	Compiler: Generates model-specific prompts

⸻

💡 Example

Profile: Cinematic Cyberpunk
Scene: A lone astronaut walking through a neon-lit alley
Model: Midjourney

Output Prompt:

A lone astronaut, walking through, a neon-lit alley, 3D render, cyberpunk, neo-noir, high contrast neon pink and cyan, dramatic diagonal, wide angle lens, volumetric fog, glossy wet surfaces, cinematic lighting, 8k, ultra detailed --no daylight, natural landscapes


⸻

🔧 Tech Stack
	•	Frontend/UI: HTML, CSS, Vanilla JS (VSC Studio)
	•	Compiler Logic: JavaScript (VSC Engine)
	•	Storage: localStorage with fallback memory
	•	AI Models: DALL·E 3, Midjourney, Stable Diffusion

⸻

📋 Roadmap
	•	API support for remote compilation
	•	Additional AI model integrations
	•	Advanced conditional locks
	•	Export prompts as ready-to-send files

⸻

📄 License

MIT License — Open for personal and commercial use.

⸻

📬 Contact

Created by Lukas Benneberg.
	•	GitHub: github.com/benneberg￼

---
