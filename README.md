# Hi, I'm Rongxuan Zhou 👋

Robotics engineer and researcher working across the full stack: **learning-based manipulation policies, real-time control, and production robotic systems**. I build and deploy policies end-to-end on Franka, UR, and humanoid hardware.

M.S. Robotics @ Northeastern University (CRAFT Lab, advised by Prof. Yang Ye) · Boston, MA
🌐 [Portfolio](https://rongxuan-zhou.github.io/) · 💼 [LinkedIn](https://www.linkedin.com/in/rongxuan-zhou-aa4a8b32a/) · 📧 zhou.rongx@northeastern.edu

---

## 🔬 What I work on

**World models & manipulation policies.** Modality-robust JEPA world models that stay reliable when a sensor disappears at deployment, diagnostics for how latent models compress actions, and training-free safety layers for diffusion policies.

**Real-robot systems.** Teleoperation rigs (Meta Quest 3 / WebXR → 1 kHz Cartesian-impedance control), open-source demonstration datasets, and closed-loop deployment with sampling-based planning on Franka FR3 and UR5e.

**Production robotics.** Before graduate school I shipped industrial systems: a machine-vision inspection line running at 85K+ units/day for TI semiconductor parts, EtherCAT real-time control stacks, and sim-to-real transfer validated on production vehicles.

---

## 📄 Selected work

| Project | What it is |
|---|---|
| **ForceLeWM** | JEPA world model with gated force fusion that survives a missing force sensor at test time · *RA-L 2026, under review* |
| **Action-Compression Anisotropy** | Jacobian-based protocol that finds a world model's action blind spots, plus a training-free fix · *arXiv 2026* |
| **TACS** | Control-barrier-function guidance inside a diffusion policy's denoising loop, 20× fewer constraint violations, no retraining · *RA-L 2026, under review* |
| **PRISM** | Prior-guided sampling for world-model planning; I built the teleoperation stack and the open-sourced PushT dataset · *[arXiv](https://arxiv.org/pdf/2606.07974) · [site](https://yuhaiw.github.io/PRISM_web/)* |
| **TOIF** | Terrain-aware hierarchical humanoid navigation with proprioceptive feedback · *Humanoids 2026, under review* |

Full list with abstracts and demo videos on my [portfolio](https://rongxuan-zhou.github.io/).

---

## 🧰 Repositories worth a look

- **[mujoco-mcp-server](https://github.com/Rongxuan-Zhou/mujoco-mcp-server)** — 65-tool MCP server letting LLM agents drive MuJoCo from natural language: trajectory optimization (iLQR, MPPI), IK, domain randomization, and RL envs across 50+ Menagerie robots.
- **[AOI-sys-for-TI](https://github.com/Rongxuan-Zhou/AOI-sys-for-TI)** — Production automated optical inspection system for semiconductor parts: C++17/OpenCV vision pipeline, IEC 61131-3 PLC control, and SCARA material handling.
- **[multi-robot-assembly-cell](https://github.com/Rongxuan-Zhou/multi-robot-assembly-cell)** — Multi-robot assembly cell for harmonic-reducer production: EtherCAT real-time control, CODESYS soft PLC, 3-robot turntable workstation.
- **[FAST_LIO_Loop_Closure_Test_On_NUANCE](https://github.com/Rongxuan-Zhou/FAST_LIO_Loop_Closure_Test_On_NUANCE)** — LiDAR-inertial SLAM benchmarking on Northeastern's autonomous vehicle platform.
- Datasets on 🤗 [Hugging Face](https://huggingface.co/Rongxuan-Zhou) — real-robot teleoperation demonstrations for world-model training.

---

## 🛠️ Tools

`Python` `PyTorch` `C/C++` `CUDA` `ROS 2` `MuJoCo` `Isaac Lab` `MoveIt` `Docker` `Linux`
`Diffusion Policy` `JEPA World Models` `Imitation Learning` `RL` `MPPI / MPC` `Control Barrier Functions`
`Franka FR3` `UR5e` `Unitree` `EtherCAT` `STM32` `Jetson` `SolidWorks` `ANSYS`
