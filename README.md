# Awesome-Youtube-Virtual-Production

# Top YouTube Virtual Production Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Rendering, Virtual Cinematography & In-Camera VFX*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **YouTube Virtual Production**. These tools help creators and studios build virtual sets, drive cameras in real time, composite live footage, and deliver broadcast-quality content without a full LED volume budget — using game engines, AI scene generation, and open-source tracking protocols.

**Examples** include Unreal Engine, Aximmetry, Zero Density, disguise, Vizrt, Pixotope, Brainstorm 3D, Mo-Sys, Ross Video, and Stype (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom camera tracking, and transparent virtual set creation — ideal for indie filmmakers, YouTube creators, and developers building accessible virtual production tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Unreal Engine](https://www.unrealengine.com/)**  
  Industry-standard real-time 3D engine for virtual production with in-camera VFX, LED volume support, and nDisplay multi-display rendering. Royalty-free for most creators.

- **[Aximmetry](https://aximmetry.com/)**  
  Virtual studio and broadcast graphics platform with real-time camera tracking, chroma keying, and Unreal Engine integration for YouTube and livestream production.

- **[Zero Density](https://zerodensity.tv/)**  
  Real-time virtual production platform with Reality Engine for photorealistic graphics, virtual sets, and AR/VR broadcast.

- **[disguise](https://www.disguise.one/)**  
  Media server and virtual production platform for LED volume workflows, projection mapping, and show control.

- **[Vizrt](https://www.vizrt.com/)**  
  Broadcast graphics and virtual studio platform with real-time 3D rendering, AR, and live production tools.

- **[Pixotope](https://pixotope.com/)**  
  Virtual production software with real-time tracking, camera robotics, and LED volume support for broadcast and film.

- **[Brainstorm 3D](https://www.brainstorm3d.com/)**  
  Virtual studio and real-time graphics platform with InfinitySet for virtual production and AR/VR.

- **[Mo-Sys](https://www.mo-sys.com/)**  
  Camera tracking specialist with StarTracker, bKeeper, and OpenTrackIO open-source tracking protocol for virtual production.

- **[Ross Video](https://www.rossvideo.com/)**  
  Broadcast production solutions with virtual studio and augmented reality capabilities.

- **[Stype](https://stype.tv/)**  
  Camera tracking and virtual production systems for broadcast and film.

## Open-Source GitHub Projects

- **[AI Virtual Director Studio](https://github.com/femnn/ai-virtual-director-studio)**  
  Local-first AI previs and virtual cinematography tool. Build 3D scenes on desktop, assign independent cameras to multiple phones, and record live camera monitor directly to MP4. Features AI scene building via whitelisted JSON commands, character posing, FaceCap face capture, and scene animation. Runs on macOS and Windows.

- **[awplanet](https://github.com/awplanets/awplanet)**  
  AI-native 3D direction and scene creation studio built with React, Three.js, Vite, and Electron. Combines visual scene editor, playable character controls, skeletal posing, cinematic camera tools, storyboard timeline, terrain sculpting, and phone-based virtual production. Three director modes: third-person play, FPV camera piloting, and phone virtual production. Source-available under PolyForm Noncommercial License.

- **[Polychase](https://github.com/theartful/polychase)**  
  Free and open-source motion tracking addon for Blender, inspired by KeenTools GeoTracker. Tracks camera movement or object motion in video footage using optical flow analysis and PnP, with 3D pin mode, trajectory refinement, variable camera parameters, and real-time preview. GPL-3.0-or-later licensed.

- **[Phi Engine](https://github.com/float64co/Phi)**  
  Game engine inspired by UE5 and Blender with live scene editing and playback in the same binary. Game logic and tool UI written in Python running on embedded MicroPython. Features deferred (G-buffer) pipeline with TAA, Bullet physics, glTF 2.0 mesh format, and Claude integration inside the editor for scene introspection. Open-source.

- **[Glass Engine](https://glass-engine-doc.readthedocs.io/)**  
  Python-native 3D real-time rendering engine, free and open-source. Embed interactive 3D viewports directly in Python UI frameworks (PySide6/PyQt5). Features scene graph, instanced rendering, forward and deferred rendering pipelines, physical-based bloom, depth of field, OIT transparency, and cascading shadow maps. Ideal for custom virtual production tooling.

- **[OpenHUTB Engine](https://github.com/OpenHUTB/engine)**  
  Simulation engine fork prioritizing proven AAA technologies (PhysX, DDGI, full ray tracing, TressFX) over UE5’s virtualized systems. Targets film, virtual production, and high-end PC experiences with strict frame-time budgets and high native resolution. Designed for cinematic fidelity rather than mass-market hardware compatibility.

- **[OpenTrackIO](https://www.mo-sys.com/news/smpte/)**  
  Open-source C++ library for virtual production camera tracking, launched by Mo-Sys at SMPTE 2024. Sets new standard with wider media workflow compatibility, improved position/rotation precision, unified lens data formats, sub-frame synchronization, and human-readable formatting. Already adopted by Epic Games, Mo-Sys, and Stage Precision.

- **[FreeD4j](https://github.com/spannercodes/FreeD4j)**  
  Java library for parsing and receiving Free-D camera data, the previous industry standard for virtual production camera tracking.

- **[rust-FreeD](https://github.com/ssav7912/rust-FreeD)**  
  Rust library of types for use with the Free-D protocol, enabling modern language integration for camera tracking data.

- **[LabCamera](https://github.com/meshula/LabCamera)**  
  Physically based camera model for virtual production and computer graphics. Provides accurate lens simulation for virtual cinematography.

- **[smartphoneremote_ue5](https://github.com/renamedquery/smartphoneremote_ue5)**  
  Adaptation of Smartphone Remote app for Android phones for Unreal Engine 5, allowing phone as camera controller for rotation and location.

- **[chroma_key](https://github.com/anphiriel/chroma_key)**  
  Chroma key compositor demo with partial alpha blending near edges and green cast removal. Python/OpenCV/Tkinter application with dynamic key color picking, tolerance control, edge softness feathering, and video export. MIT licensed.

- **[gl-chromakey](https://github.com/bhj/gl-chromakey)**  
  Real-time GPU-based chroma keying for video, image, and canvas elements in the browser.

### Additional Strong Open-Source Options

- **[AI Film Studio (Red Clover Studio)](https://github.com/ShawnTheWriter/red-clover-studio)** — Free, local-first AI film and microdrama studio with script parsing, storyboard generation, keyframe-to-video, and DaVinci Resolve round-trip. Built for one filmmaker’s production with 600+ automated checks.
- **BBC Osmia VP** — BBC R&D’s low-cost virtual production system using open-source and AI techniques. Creates virtual sets from phone-captured stills, live camera tracking, and in-studio rendering. Planned open-source release.
- **Chroma Key Libraries** — 59+ public repos on GitHub topic `green-screen` covering real-time browser keying, Python compositing, and video background removal.
- **Camera Tracking Tools** — FreeD parsers, LabCamera physical model, and OpenTrackIO for standards-based tracking.

**Frameworks for building custom systems**: Combine **AI Virtual Director Studio** or **awplanet** for AI-driven scene creation and phone-based camera control, **Polychase** for Blender motion tracking, **OpenTrackIO** for standardized camera tracking data, **chroma_key** for real-time compositing, and **Glass Engine** for custom Python-based rendering to build a complete self-hosted YouTube virtual production stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Virtual production tools must comply with software licensing terms, broadcast standards, and content rights requirements.
- Self-hosted open-source solutions require proper hardware setup, GPU resources, and ongoing maintenance.

---

**Made for YouTube creators, indie filmmakers, virtual production artists, and developers building accessible real-time production tools.**  
Let’s make YouTube virtual production more open, affordable, and creator-friendly.
