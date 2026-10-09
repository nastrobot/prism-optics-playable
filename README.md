# 🔬 PRISM: Optical Ray-Tracing Physics Lab

A high-precision optical physics laboratory and vector ray-tracing puzzle engine built with **HTML5 Canvas 2D** and the **Web Audio API**.

---

## 📐 Mathematical & Physics Engine
* **Vector Law of Reflection:**
  $$\vec{r} = \vec{d} - 2(\vec{d} \cdot \vec{n})\vec{n}$$
  Where $\vec{d}$ is the incident light vector, $\vec{n}$ is the surface normal, and $\vec{r}$ is the reflected photon vector.
* **Line-Segment Intersections:** Real-time 2D parametric vector intersection checks across dynamic mirrors, opaque barriers, and circular apertures.
* **Multi-Bounce Raymarching:** Supports recursive light paths with multi-specular bounces calculated at locked 60 FPS.
* **Photonic Bloom & Absorption:** Photonic sensor charging with additive light blending (`lighter` compositing).

---

## 🕹️ Interaction
* **Touch & Rotate:** Drag the dashed circular gizmo around any optical mount to smoothly adjust the reflection angle ($\theta$).
* **Level Progression:** Multiple optical physics experiments featuring obstacle deflection, multi-sensor resonance, and precision alignment.
* **Zero Asset Overhead:** Self-contained sub-second load time with procedural Web Audio resonance harmonics.
