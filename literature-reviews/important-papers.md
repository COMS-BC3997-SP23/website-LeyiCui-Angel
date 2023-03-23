---
layout: default
title: Important Papers
parent: Literature Reviews
---

# Important papers
{: .no_toc }

## Table of conferences
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## [Machine Art: Exploring Abstract Human Animation Through Machine Learning Methods](https://dl.acm.org/doi/10.1145/3537972.3537993)
- Visual media and performance art have a symbiotic relationship. They support one another and engage the audience by providing an experience or telling a story. This comparative study explores the accuracy, efficiency, and cost factors of using machine learning based motion capture methods in performance art. There is extensive research in the field of machine learning methods for human pose estimation, but the outputs of such work are rarely used as inputs for performance art. In this paper we present a practice-based research project that involves producing animations that match a performer's movements using machine learning based motion capture methods. We use human poses derived from low-cost video capture as an input into high-resolution abstract forms that accompany and synchronise with dance performances. A single-camera approach is examined and compared to existing methods. We find that compared with existing motion capture methods the machine learning based methods require less setup time, and less equipment is required resulting in considerably lower cost. This research suggests that machine learning has considerable potential to improve the quality of human pose estimation in performance art, visual effects and motion capture, and make it more accessible for arts companies with limited resources.
- VIBE (Video Inference for Human Body Pose and Shape Estimation)
- Mentioned that no special lighting or environment required for using VIBE.
- Different capture space affect the accuracy.
- The output of the pose detection is stored in a .pkl file which has data for each keypoint of the subject for each frame. This file is not readily useful for animation purposes as it only stores data - it would need to be converted to a .fbx file to import into 3D applications for animation purposes.
- 

## [VIBE: Video Inference for Human Body Pose and Shape Estimation](https://arxiv.org/abs/1912.05656)
- Human motion is fundamental to understanding behavior. Despite progress on single-image 3D pose and shape estimation, existing video-based state-of-the-art methods fail to produce accurate and natural motion sequences due to a lack of ground-truth 3D motion data for training. To address this problem, we propose Video Inference for Body Pose and Shape Estimation (VIBE), which makes use of an existing large-scale motion capture dataset (AMASS) together with unpaired, in-the-wild, 2D keypoint annotations. Our key novelty is an adversarial learning framework that leverages AMASS to discriminate between real human motions and those produced by our temporal pose and shape regression networks. We define a temporal network architecture and show that adversarial training, at the sequence level, produces kinematically plausible motion sequences without in-the-wild ground-truth 3D labels. We perform extensive experimentation to analyze the importance of motion and demonstrate the effectiveness of VIBE on challenging 3D pose estimation datasets, achieving state-of-the-art performance. Code and pretrained models are available at this https URL.
- [Github page](https://github.com/mkocabas/VIBE)
- VIBE model operates without any calibration.
- The lack of this step dramatically speeds up the setup process, and video acquisition is not limited to users familiar with the camera calibration process.
- 