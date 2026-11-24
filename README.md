# Yu Shi — Academic Website

Personal academic website of Yu Shi, PhD Candidate in Mechanical Engineering at Zhejiang University and Visiting Scholar at McGill University.

**Research Interests:** Multimodal Robot Learning, Vision-Language-Action (VLA), Imitation Learning, Reinforcement Learning, Geometric Perception, Motion Planning, and Autonomous Robotic Systems.

## Website

**Live Website:** [Academic Homepage](https://18810190556.github.io/Doraemon.github.io/)

- [Selected Research](https://18810190556.github.io/Doraemon.github.io/#research)
- [Research Demonstrations](https://18810190556.github.io/Doraemon.github.io/#demos)
- [Publications](https://18810190556.github.io/Doraemon.github.io/#publications)
- [Academic CV](https://18810190556.github.io/Doraemon.github.io/assets/cv.pdf)
- [Research Summary](https://18810190556.github.io/Doraemon.github.io/assets/research-summary.pdf)

## Research Projects

### Geometry-Aware VLA Policy Learning

Multimodal robot policy learning based on AutoVLA and Qwen2.5-VL-3B, integrating structured geometric representations and language-conditioned trajectory generation. The training framework employs imitation learning from expert demonstrations, with ongoing integration of reinforcement learning for policy refinement and closed-loop performance optimization.

### GeoManeuver-VL

Vision-language-grounded 3D local maneuver planning based on Qwen3-VL-2B, integrating cross-attention grounding, metric BEV representations, conditional flow-based trajectory generation, kinematic integration, terrain support modeling, and iterative sweep-based trajectory refinement.

### Semantic- and Structure-Enhanced Stereo Point–Line SLAM

Semantic-geometric feature association, customized line descriptors, reliability-weighted point–line optimization, and environmental structural constraints for continuous localization in repetitive and weakly textured environments.

### Autonomous Mobile Manipulation with Unitree Go2

A real-world autonomous robotic system integrating quadruped navigation, LiDAR–IMU state estimation, visual target localization, 3D spatial representation, robotic arm motion planning and control, and autonomous task execution in outdoor environments.

## Research Demonstrations

The website includes experimental videos, animated GIFs, network architecture diagrams, and real-world robotic demonstrations covering:

- Geometry-aware VLA trajectory generation and closed-loop execution.
- Vision-language-grounded 3D local maneuver planning.
- 3D terrain representation, occupancy mapping, and trajectory generation.
- Semantic-geometric SLAM in agricultural environments.
- Autonomous quadruped navigation and robotic arm manipulation.

## Website Structure

- `index.html` — Academic homepage, biography, research projects, demonstrations, publications, education, and contact information.
- `projects/` — Individual research project pages.
- `assets/` — Network architecture diagrams, experimental figures, photographs, CV, and research summary.
- `assets/videos/` — MP4 videos and animated GIF demonstrations.
- `style.css` — Shared responsive layout and visual styles.
- `.nojekyll` — Static GitHub Pages configuration.

## Technical Implementation

The website is built with HTML, CSS, and lightweight JavaScript without external frameworks or build dependencies. It is hosted on GitHub Pages and supports both desktop and mobile browsers.

For local preview, open `index.html` directly or run the following command from the repository root:

`python -m http.server 8000`

Then visit `http://localhost:8000`.

Updates committed to the `main` branch are automatically deployed through GitHub Pages.

## Contact

**Yu Shi**

PhD Candidate, Zhejiang University  
Visiting Scholar, McGill University  
Montréal, Québec, Canada

**Email:** yu.shi6@mail.mcgill.ca

## Research Materials and Copyright

This website serves as an academic research portfolio and will be continuously updated with research progress, project descriptions, technical architectures, experimental results, demonstration videos, and research source code.

Research source code and related resources will be progressively released as the projects develop.

For academic citations, research collaborations, or requests to reproduce, redistribute, or use any research materials, figures, videos, or source code, please contact the author in advance. Any use of these materials must include appropriate attribution and comply with the applicable licensing terms.

Unless otherwise explicitly stated, all rights to the original research materials and source code are reserved.

**Copyright © 2026 Yu Shi. All rights reserved.**
