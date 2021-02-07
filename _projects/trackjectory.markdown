---
layout: page
title: TrackJectory
description: Tracking + Trajectory
img: /assets/img/track.png
github: https://github.com/Sai-Venky/Trackjectory
importance: 1
---

Siamese Tracker for single object (online) visual tracking. Provided the template image, SiamRPN++ identify's and track's the template across video frames.
FairMOT for one shot multi-object detection and tracking. (FairMOT: Multi-Object Tracking)
Social GCN for trajectory forecasting. FairMOT is used to predict and track multiple objects across frames. After extracting the tracked objects, those outputs are furnished to Social GCN to forecast the trajectories.