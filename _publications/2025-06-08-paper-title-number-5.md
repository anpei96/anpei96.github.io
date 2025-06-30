---
title: "MinCD-PnP: Learning 2D-3D Correspondences with Approximate Blind PnP"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about a famous math equation, $$E=mc^2$$'
date: 2025-06-30
venue: 'ICCV 2025'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Pei An, Jiaqi Yang, Muyao Peng, You Yang, Qiong Liu, Xiaolin Wu, and Liangliang Nan. MinCD-PnP: Learning 2D-3D Correspondences with Approximate Blind PnP. Accepted by ICCV 2025'
---

Image-to-point-cloud (I2P) registration is a fundamental problem in computer vision, focusing on establishing 2D-3D correspondences between an image and a point cloud. The differential perspective-n-point (PnP) has been widely used to supervise I2P registration networks by enforcing the projective constraints on 2D-3D correspondences. However, differential PnP is highly sensitive to noise and outliers in the predicted correspondences. This issue hinders the effectiveness of correspondence learning. Inspired by the robustness of blind PnP against noise and outliers in correspondences, we propose an approximated blind PnP based correspondence learning approach. To mitigate the high computational cost of blind PnP, we simplify blind PnP to an amenable task of minimizing Chamfer distance between learned 2D and 3D keypoints, called MinCD-PnP. To effectively solve MinCD-PnP, we design a lightweight multi-task learning module, named as MinCD-Net, which can be easily integrated into the existing I2P registration architectures. Extensive experiments on 7-Scenes, RGBD-V2, ScanNet, self-collected, and KITTI datasets demonstrate that MinCD-Net outperforms state-of-the-art methods and achieves a higher inlier ratio (IR) and registration recall (RR) in both cross-scene and cross-dataset settings.
