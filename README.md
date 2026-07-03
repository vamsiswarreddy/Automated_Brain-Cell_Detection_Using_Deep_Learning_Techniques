# 🧠 Automated Brain Cell Detection Using Deep Learning Techniques

<p align="center">
<img src="images/system_architecture.jpeg" width="800">
</p>

---

![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-yellow)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red)
![Deep Learning](https://img.shields.io/badge/Deep-Learning-green)
![Final Year Project](https://img.shields.io/badge/Project-B.Tech-success)

---

# 📌 Project Overview

Brain cell detection plays an important role in neuroscience research and medical image analysis. Manual identification of brain cells from microscopy images is time-consuming, error-prone, and difficult when cells overlap or appear in dense clusters.

This project presents an automated deep learning-based framework for brain cell detection using multiple state-of-the-art detection and segmentation models. The work primarily focuses on YOLOv8 for object detection while studying BDA, MEDIAR, SAM, Mask R-CNN, and DETR for comparative analysis.

---

# 🎯 Objectives

- Automate brain cell detection from microscopy images.
- Reduce manual effort and improve detection accuracy.
- Compare multiple deep learning models for detection and segmentation.
- Evaluate model performance using qualitative and comparative analysis.
- Build a scalable framework for future biomedical image analysis.

---

# 🏗️ System Architecture

<p align="center">
<img src="images/system_architecture.jpeg" width="800">
</p>

The proposed framework consists of:

- Brain microscopy image acquisition
- Image preprocessing
- Deep learning model inference
- Cell detection and segmentation
- Comparative analysis
- Output visualization

---

# 📂 Project Structure

```text
Automated_Brain_Cell_Detection_Using_Deep_Learning_Techniques/
│
├── dataset/
├── images/
├── notebooks/
├── report/
├── results/
├── LICENSE
├── .gitignore
└── README.md
```

---

# 📁 Repository Contents

| Folder | Description |
|---------|-------------|
| 📂 dataset | Sample brain microscopy dataset images used for demonstration. |
| 📂 images | System architecture, workflow diagrams, dataset samples, and output figures. |
| 📂 notebooks | Google Colab notebook implementing the complete project. |
| 📂 report | Final project report, presentation, and synopsis. |
| 📂 results | Experimental outputs generated after notebook execution. |

---

# 🖼️ Sample Brain Microscopy Dataset

<p align="center">
<img src="images/dataset_samples.jpeg" width="750">
</p>

The dataset consists of high-resolution brain microscopy images containing dense cellular structures used for evaluating detection and segmentation models.

---

# 🤖 Deep Learning Models Used

## Segmentation Models

- Segment Anything Model (SAM)
- CA-Net
- Mask R-CNN

## Detection Models

- YOLOv8
- DETR
- SAHI
- FreeSOLO

## Cell Detection Models

- BDA
- MEDIAR

---

# 🛠️ Technologies Used

- Python
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- Ultralytics YOLOv8
- PyTorch
- Computer Vision
- Deep Learning

---

# 🚀 Google Colab Implementation

The complete implementation is provided as a Google Colab notebook.

The notebook includes:

- Dataset loading
- Image preprocessing
- Brain cell detection
- BDA contour detection
- Comparative visualization
- Output generation

Notebook Location:

```
notebooks/
```

---

# 📊 Experimental Results

The proposed framework generates multiple outputs for qualitative comparison.

## YOLOv8 Detection Output

<p align="center">
<img src="images/yolov8_detection_output.jpeg" width="750">
</p>

---

## BDA Contour Detection Output

<p align="center">
<img src="images/bda_contour_output.jpeg" width="750">
</p>

---

## MEDIAR Segmentation Output

<p align="center">
<img src="images/mediar_output.jpeg" width="750">
</p>

---

## Comparative Output Visualization

<p align="center">
<img src="images/output_visualization.jpeg" width="750">
</p>

The comparative visualization demonstrates the effectiveness of different deep learning techniques for automated brain cell detection and segmentation.

---

# 📈 Expected Outcomes

- Accurate brain cell localization
- Automated detection workflow
- Reduced manual annotation effort
- Comparative evaluation of multiple deep learning models
- Support for future biomedical image analysis applications

---

# 📚 References

1. Kirillov et al., *Segment Anything*, 2023.
2. Gu et al., *CA-Net: Comprehensive Attention CNN for Medical Image Segmentation*, 2020.
3. He et al., *Mask R-CNN*, ICCV, 2017.
4. Redmon et al., *You Only Look Once (YOLO)*, CVPR, 2016.
5. Carion et al., *DETR: End-to-End Object Detection with Transformers*, ECCV, 2020.
6. Lee et al., *MEDIAR: Multi-Modality Microscopy Image Segmentation*, 2022.
7. Upschulte et al., *Contour Proposal Networks for Biomedical Instance Segmentation*, 2022.
8. Ultralytics Documentation.
9. OpenCV Documentation.

---

# 🔮 Future Scope

- Improve detection accuracy using larger annotated datasets.
- Fine-tune transformer-based detection models.
- Develop a real-time brain cell detection system.
- Deploy the framework as a web application.
- Extend the framework for additional biomedical image analysis tasks.

---

# 👨‍💻 Author

**Kunam Reddy Veera Vamsiswar Reddy**

**B.Tech – Computer Science & Engineering (Artificial Intelligence)**

Manipal Institute of Technology Bengaluru

Academic Year: **2025–2026**

---

## 🎓 Acknowledgement

This work was carried out under the guidance of **Dr. Manaswita Saikia** as part of the Bachelor of Technology Final Year Project at **Manipal Institute of Technology Bengaluru**.

---

## ⭐ If you found this repository useful, please consider giving it a Star.
