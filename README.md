## Track2Map
Track2Map is a system designed to improve real-time situational awareness in public spaces by augmenting CCTV with modern AI. At a high level, it detects people in video streams, tracks them over time, projects their positions onto a 2D site map for a unified view, and (in future work) flags anomalous behavior for rapid response.
 
> This repository contains a short, non-technical overview and the public presentation only.  
> **No code, models, parameters, or implementation details are shared here.**
 
## What it does (at a glance)
- **Real-time people awareness:** Detects and tracks individuals per camera feed.
- **Unified 2D mapping:** Projects detections to a site map for clear spatial context.
- **Cross-camera continuity:** Maintains consistent identities as people move through space.
- **Alerting (planned):** Summarizes scene state and flags anomalies for operators.
 
## Why it matters
Traditional cameras capture everything but rarely *help in real time*. Track2Map focuses on real-time understanding and operator-friendly visualization, aiming to shorten response times and reduce cognitive load.
 
## Conceptual pipeline (high level)
1. **Per-camera tracking** of people in live video streams.  
2. **Mapping to a 2D layout** (homography) for location-aware visualization.  
3. **Cross-camera matching** to preserve identities across overlapping views.  
4. **Operator view** with a live map and (future) **anomaly alerts**.
  
## Team
- **Arbel Askayo** & **Nir Manor**  
- Academic advisor: **Prof. Ilan Shimshoni**
 
## Contact & collaboration
For academic inquiries, demos, or collaboration requests, please open an issue or reach out privately.  
Please note that **source code and implementation details are not available**.
 
## Legal
Copyright © 2025 Arbel Askayo and Nir Manor.  
All rights reserved. This repository and its contents may not be copied, modified, or redistributed without written permission.
