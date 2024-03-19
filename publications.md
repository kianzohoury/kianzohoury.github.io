---
layout: default
title: Publications
permalink: /publications/
---

Zohoury, Kian, Cornelius, Jackson, Petrich, Jan, Cole, Vernon J, and Reutzel, Edward W. 
<b>“3D Convolutional Neural Networks for Robust In-Situ Defect Segmentation in 
Powder Bed Fusion Additive Manufacturing.”</b> Journal of Computing and Information 
Science in Engineering (2024). American Society of Mechanical Engineers. 
(Under Review)

Abstract: <i> Defect detection is critical in additive manufacturing (AM), as it reduces the 
proliferation of structurally-unsound components. While X-ray computed tomography 
(XCT) is costly and only available post-build, in-situ sensors enable machine 
learning to draw real-time inferences that help steer repairs and process 
optimization. However, annotating their signatures for supervised learning is 
challenging due to lack of human interpretability. Automated labeling and 
homographical registration techniques aim to solve this issue, but fail at 
establishing one-to-one mappings between in-situ build plate coordinates and 
their truth labels originating from the XCT ex-situ coordinate frame. Therefore, 
models that fail to compensate for noisy data pairs result in reduced performance 
in defect segmentation. In this paper, we propose a 3D convolutional neural network 
(3D CNN) encoder-decoder architecture to segment layer-wise defects in 2D, at the 
native in-situ sensor resolution. By considering a volume of adjoining build layers, 
3D CNNs can learn spatiotemporal features associated with multi-layer defects 
and mitigate registration errors, which manifest as coordinate offsets that 
weaken data pair correlations. Compared against 2D variants, 3D in-situ networks 
demonstrated robust defect segmentation and reduced the gap between ex-situ 
networks that ingest perfectly-registered data. Moreover, this approach addresses
natural class imbalances in AM processes, where defects (i.e. porosities) account 
for less than 0.1% of total volume. </i>