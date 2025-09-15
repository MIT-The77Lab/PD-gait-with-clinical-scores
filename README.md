# Human Pose-Based Parkinson's Disease Dataset

This repository provides access to **Human Pose-Based PD Dataset**, a comprehensive collection of OpenPose skeleton data from Parkinson's Disease patients and healthy controls for motor assessment and classification research.

---

## 📌 Overview

**Skeleton-Based PD Dataset** consists of skeleton keypoint data extracted from video recordings, annotated for:
- 107 `Parkinson's Disease patients`
- 38 `Healthy Controls`
- Multiple recording sessions per patient

This dataset addresses the challenge of **automated PD detection** using human pose-based analysis, captured under various recording conditions and durations.

---

## 📥 Download

You can download the dataset via the following link:

🔗 [Download Dataset (Google Drive)](your-drive-link-here)

---

## 📊 Dataset Structure

```
skeleton_dataset/
├── PD/                          # Parkinson's Disease patients (107)
│   ├── H.S.A/
│   │   ├── H.S.A 6 (6m) - TS (Video 1795).MP4.npy
│   │   └── ...
│   └── [other patients]/
└── HC/                          # Healthy Controls (38)
    ├── [patient folders]/
    └── ...
```

**Data Format**: OpenPose COCO format (17 keypoints)  
**File Type**: NumPy arrays (.npy)  
**Shape**: `(frames, 17_keypoints, 3_coordinates)`

---


## 🩺 Clinical Data

Clinical assessment scores and patient metadata are available upon request for research purposes.

📧 **Contact**: hikrebs@mit.edu

---
