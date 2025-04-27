# Dynamic 4D Vision Reconstruction

🚀 **Project Mission:**  
Reconstruct dynamic 4D scenes — 3D geometry evolving over time — from 2D video inputs, using state-of-the-art methods such as NeRF and 3D Gaussian Splatting.

🌍 **Long-Term Goal:**  
Build systems that can perceive, understand, and model the real, moving world — a core step toward real-world intelligence and embodied AI.

---

## 📚 Roadmap

**Phase 1: Static 3D Reconstruction**
- [x] Set up PyTorch + CUDA environment
- [x] Reproduce baseline NeRF models on standard datasets (Lego, Fern)
- [ ] Train 3D Gaussian Splatting model on toy scenes
- [ ] Capture custom real-world static scenes and reconstruct them

**Phase 2: Toward Dynamic (4D) Reconstruction**
- [ ] Understand and replicate dynamic scene splatting techniques
- [ ] Record own moving-object videos
- [ ] Extend models to handle time dimension
- [ ] Render dynamic, real-time moving scenes

**Phase 3: Scaling Up**
- [ ] Multi-view dynamic scene capture
- [ ] Real-time dynamic reconstruction optimization
- [ ] Explore interaction modeling (5D)

---

## 🛠 Tech Stack

- **Core ML:** PyTorch, CUDA
- **Rendering:** Blender, ffmpeg
- **Datasets:** LLFF, Tanks & Temples, Custom captures
- **Core Methods:** NeRF, Gaussian Splatting, Dynamic Scene Flow

---

## 📦 Repo Structure

dynamic-4d-vision-reconstruction/
│
├── README.md          # High-level description of project
├── notebooks/         # Jupyter notebooks for experiments
├── data/              # Pointers or scripts to download datasets
├── experiments/       # Different models, settings you try
├── models/            # Core models (NeRF, GS, etc.)
├── outputs/           # Renders, screenshots, gifs
└── resources/         # Papers, tutorials, links

---

## ✍🏻 About Me

I'm Yash Darji — a builder focused on advancing **Spatial Intelligence** and **Dynamic World Modeling** for the next generation of AI and robotics systems.

🔗 [Twitter/X Profile](https://x.com/YashDarji_)  
🔗 [Pearl Inc. (Coming Soon)]

---

## 📢 Acknowledgements

- [NeRF: Representing Scenes as Neural Radiance Fields](https://arxiv.org/abs/2003.08934)
- [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://arxiv.org/abs/2306.00989)
- Open-source pioneers whose work enables this project.

---
