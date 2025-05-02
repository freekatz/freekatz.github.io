---
title: 'CamPoint: Boosting Point Cloud Segmentation with Virtual Camera'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - '**Jianhui Zhang**<sup>*</sup>'
  - Luo Yizhi
  - Zicheng Zhang
  - Xuecheng Nie
  - Bonan Li<sup>†</sup>

# Author notes (optional)
author_notes:

date: '2025-02-27T08:00:00Z'
doi: '#'
# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-27T08:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']  # paper-conference, article-journal, preprint
tags:
- paper-conference
- Computer Vision
# Publication name and optional abbreviated publication name.
publication: In *The IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025*
publication_short: In *CVPR 2025*
abstract: ''
# Summary. An optional shortened abstract.
summary: 
# Display this page in the Featured widget?
featured: true
# TODO
links:
  - icon_pack: fas
    icon: scroll
    name: Website
    url: '/publications/2025-campoint.html'
  - icon_pack: fas
    icon: file-pdf
    name: Paper
    url: 'publications/2025-campoint/CamPoint_CameraReady.pdf'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/MTXAI/CamPoint'
  - icon_pack: ai
    icon: open-data
    name: Dataset
    url: '/#/'
  - icon_pack: fas
    icon: face-smile
    name: Model Card
    url: 'https://huggingface.co/MTXAI/CamPoint'
image:
  caption: Fediverse
  focal_point: Smart
type: post
---

**Abstract**: Local features aggregation and global information perception are the fundamental to point cloud segmentation. However, existing works often fall short in effectively identifying semantic relevant neighbors and face challenges in endowing each point with high-level information. Here, we propose CamPoint, an innovative method that employs virtual cameras to solve the above problems. The core of CamPoint lies in introducing the novel camera visibility feature for points, where each dimension encodes the visibility of that point from a specific camera. Leveraging this feature, we propose the camera perspective slice distance for accurate relevant neighbor searching and design the camera parameter embedding to deliver rich feature representations for global interaction. Specifically, the camera perspective slice distance between two points is defined as a similarity metric derived from their camera visibility features, whereby an increased number of shared cameras observing both points corresponds to a reduced distance between them. To effectively facilitate global semantic perception, we assign each camera an optimizable embedding and then integrate these embeddings into the original spatial features based on visibility attributes, thereby obtaining high-level features enriched with camera priors. Additionally, the state space model characterized by linear computational complexity is employed as the operator to achieve global learning with efficiency. Comprehensive experiments on multiple datasets show that our CamPoint surpasses the current state-of-the-art in multiple datasets, achieving low training cost and fast inference speed. The code will be released upon acceptance.

