---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF]({{ base_path }}/files/CV_YinLiang_Chen.pdf)

Education
======
* **B.S. in Electrical Engineering**, National Taiwan University — Sep. 2023 – Present (Taipei, Taiwan)  
  GPA: 4.17/4.3 (3-year average) | Department Rank: 32/255 (Top 12.5%)  
  Relevant coursework: Robot Perception and Learning, Computer Vision, Machine Learning, Probability and Statistics, Linear Algebra, Data Structures, Algorithms
* **Exchange Student**, University of Washington — Sep. 2026 – Dec. 2026 (Seattle, WA, USA)
* **Class of Science**, Taipei Municipal Chien Kuo High School — Sep. 2020 – Jun. 2023 (Taipei, Taiwan)

Research Experience
======
* **Healthcare Robotic Dog: Scene Graph and Spatial Memory** — Oct. 2026 – Present  
  Information Processing Lab, Department of ECE, University of Washington (Prof. Jenq-Neng Hwang)
  * Developed a scene-graph module organizing rooms, objects, and spatial relationships to support navigation and language-guided reasoning.
  * Fine-tuned vision-language-action (VLA) models for a Unitree D1 robotic arm mounted on a quadruped platform, targeting language-guided manipulation and assistive object retrieval.

* **Low-Overlap Camera Pose Estimation with Generated Bridge Frames** — Feb. 2026 – Present  
  Vision and Learning Lab, Department of EE, NTU (Prof. Yu-Chiang Frank Wang)
  * Investigated whether generated intermediate frames could improve relative camera pose estimation under extremely low-overlap conditions using VGGT and DUSt3R.
  * Developed MEt3R-guided masking to suppress geometrically inconsistent regions in generated frames; explored consistency-based token masking and self-supervised consistency methods.
  * Improved pose accuracy: MRE 30.8° → 28.1° on 16-frame VGGT sequences; DUSt3R on Interpose medoid inputs achieved 12.3° MRE and 89.5% R@15°.

Projects
======
* **Shared Medical Transportation Platform** — Oct. 2026 – Present  
  Collaborated with Prof. Li-Ning Peng, engineers, and medical professionals; contributed to platform design for reservations, multi-passenger routing, driver assignment, live tracking, and operational workflows.

* **Multiplier-Free 32-Point DFrFT Accelerator with 8-bit Complex-Order Key** — Feb. 2026 – Jun. 2026  
  Eigendecomposition-based DFrFT with CSD shift-and-add PEs, compressed ROM wrappers, dual-port RFs, and CORDIC rotations. RTL-to-layout in UMC 0.18 µm: 85 MHz, 0.0374 mW, 2.208 mm².

* **AI Smart Recycling Bin with IOTA Wallet Reward System** — May 2026 – Jun. 2026  
  Raspberry Pi 5 + VLM image recognition; LINE LIFF, IOTA wallet, AWS Lambda, and DynamoDB for rewards and transaction history.

* **Life-RAFT: Lightweight Inference and Fusion Engine via RAFT** — May 2026 – Jun. 2026  
  Lightweight 4K frame-generation using 1080p current frame and neighboring 4K references; RAFT optical flow, backwarping, and fusion with flow-consistency / epipolar guidance. Up to ~3% BD-rate reduction vs. MediaTek reference.

* **VGGT-Based BEV Visualization in Intelligent Vehicles** — May 2026 – Jun. 2026  
  Training-free VGGT pipeline reconstructing 3D scenes from six surround-view cameras; coordinate transforms, point-cloud aggregation, and BEV projection. Top-three final project in Intelligent Vehicles.

* **Contact-Guided Policy Learning for Humanoid Dexterous Manipulation** — Oct. 2025 – Dec. 2025  
  Contact-guided RL with PPO; object-centric 3D contact maps from Trellis2 and modified ContactGen CVAE; contact-based rewards for stable grasps.

* **Aim Lab Simulation on FPGA** — Nov. 2025 – Jan. 2026  
  IMU-equipped toy gun with I2C to FPGA; motion/trigger processing as mouse-like input; Aim Lab-style shooting simulation.

* **RISC-V CPU Design** — Nov. 2025 – Jan. 2026  
  Single-cycle and five-stage pipelined RISC-V processors in Chisel with data and control hazard handling.

* **Gate-level Design of QGELU and Sobel Filter** — Oct. 2025 – Nov. 2025  
  Gate-level QGELU activation and Sobel edge detection; top 5 in QGELU benchmarks and top 20 in image-processing benchmarks.

* **Personal Local AI Assistance** — Jul. 2025 – Sep. 2025  
  LLM assistant with conversational interaction, real-time web search, and voice-commanded screen analysis.

* **Real-Time Transcription and Translation** — Jul. 2025 – Aug. 2025  
  Real-time audio transcription (BlackHole 16ch + LLMs), multilingual translation, and picture-in-picture live subtitles.

* **Cell Segmentation** — Feb. 2025 – Aug. 2025  
  Fine-tuned encoder–decoder models for cell segmentation with preprocessing and mask postprocessing.

* **V2V (Vehicle to Vehicle Communication)** — May 2025  
  Semantic communication for voice-based commands in lane-change, emergency, and cooperative-driving scenarios; LLM intent parsing and event logging.

* **THz Frequency Spectrum Analysis** — Jan. 2021 – Jan. 2022  
  Compared THz spectral responses across circuit-board types for material identification.

Leadership & Activities
======
* **Student Affairs Director — Country Youth Life Study Club** — Sep. 2023 – Jun. 2024  
  Recruited and mentored incoming students, organized social events and trips, and helped foster an inclusive and supportive student community.

* **NTUEE Night — Performance & Technical Team** — Jan. 2025 – May 2026  
  Coordinated hip-hop dance performances, designed costumes for Light Dance, and contributed to the software backend team. Combined creative collaboration with technical development to support student-led performances.

* **NTU iOS Club — Member** — Sep. 2025 – Jan. 2026  
  Explored SwiftUI development and exchanged technical ideas with fellow students, expanding my interests in software development beyond academic coursework.

Honors & Competitions
======
* **MediaTek Frame Generation Final Project Competition** — May–Jun. 2026  
  2nd place (presentation) and 3rd place (performance) with Life-RAFT.
* **MakeNTU Logitech Challenge** — May 2026  
  3rd place; AI tactical assistant for League of Legends with speech recognition, LLM parsing, and Logitech Creative Console display.
* **Asian Pacific Math Olympiad Camp** — Jan. 2021 – Jan. 2023  
  Mathematics training organized by the Office of Taiwan Mathematical Olympiad.

Skills
======
* **Languages:** Mandarin (native), English (proficient), Japanese (basic)
* **Programming:** Python, C, C++, SystemVerilog, Go, MATLAB
* **Hardware Design:** Chisel, FPGA development, RTL-to-layout implementation
