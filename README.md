# Automated_Brain-Cell_Detection_Using_Deep_Learning_Techniques
# 🧠 Automated Brain Cell Detection Using Deep Learning Techniques

![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green)
![Google%20Colab](https://img.shields.io/badge/Google-Colab-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red)
![Status](https://img.shields.io/badge/Project-Final%20Year%20Project-success)

---

# 📌 Project Overview

Brain cell detection plays an important role in neuroscience research and medical image analysis. Manual identification of brain cells from microscopy images is time-consuming and prone to human error, especially when dealing with dense cellular structures.

This project proposes an automated brain cell detection framework using deep learning techniques. Multiple state-of-the-art detection and segmentation models are studied and compared to improve cell localization and segmentation. The implementation primarily focuses on YOLOv8 for object detection while also studying BDA, MEDIAR, SAM, Mask R-CNN, and DETR for comparative analysis.

The project has been developed as part of the Bachelor of Technology (B.Tech.) Final Year Project at **Manipal Institute of Technology Bengaluru**.

---

# 🎯 Objectives

- Develop an automated brain cell detection system.
- Detect brain cells from microscopy images using deep learning.
- Study and compare multiple detection and segmentation models.
- Improve detection accuracy while reducing manual effort.
- Build a scalable workflow for future biomedical image analysis.

---

# 🏗️ System Architecture

<p align="center">
<img src="images/system_architecture.jpeg" width="900">
</p>

### Workflow

```
Brain Microscopy Images
          │
          ▼
 Image Preprocessing
          │
          ▼
 Deep Learning Models
 (YOLOv8 / BDA / MEDIAR)
          │
          ▼
 Cell Detection &
 Segmentation
          │
          ▼
 Visualization &
 Performance Analysis
```

---

# 📂 Project Structure

```
Automated_Brain_Cell_Detection_Using_Deep_Learning_Techniques/

│
├── dataset/
│   ├── README.md
│   └── Sample Images
│
├── images/
│   ├── dataset_samples.jpeg
│   ├── system_architecture.jpeg
│   ├── gui_backend_workflow.jpeg
│   ├── yolov8_detection_output.jpeg
│   ├── bda_contour_output.jpeg
│   ├── mediar_output.jpeg
│   └── output_visualization.jpeg
│
├── notebooks/
│   └── Brain_Cell_Detection.ipynb
│
├── report/
│   ├── Final_Report.pdf
│   ├── Midterm_Presentation.pptx
│   └── Synopsis.pdf
│
├── LICENSE
├── README.md
└── .gitignore
```

---

# 🤖 Deep Learning Models Used

| Category | Models |
|-----------|---------|
| Detection | YOLOv8, DETR, SAHI |
| Segmentation | SAM, Mask R-CNN, CA-Net |
| Biomedical Models | MEDIAR, BDA |

---

# 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Google Colab | Model Development |
| OpenCV | Image Processing |
| YOLOv8 | Cell Detection |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| GitHub | Version Control |
| Jupyter Notebook | Experimentation |

---

# 🚀 Google Colab Execution

### Clone Repository

```bash
git clone https://github.com/vamsiswarreddy/Automated_Brain-Cell_Detection_Using_Deep_Learning_Techniques.git
```

### Install Dependencies

```bash
pip install ultralytics
pip install opencv-python
pip install matplotlib
pip install numpy
```

### Open Notebook

```
notebooks/
Brain_Cell_Detection.ipynb
```

Execute the notebook sequentially to perform preprocessing, model loading, detection, and output visualization.

---

# 📊 Expected Results

The proposed framework is expected to:

- Detect brain cells from microscopy images automatically.
- Reduce manual cell counting effort.
- Improve detection consistency.
- Generate accurate bounding boxes around detected cells.
- Support comparison between different deep learning models.
- Provide a scalable workflow for biomedical image analysis.

---

# 🖼️ Sample Outputs

## Dataset Samples

<p align="center">
<img src="images/dataset_samples.jpeg" width="700">
</p>

---

## YOLOv8 Detection Output

<p align="center">
<img src="images/yolov8_detection_output.jpeg" width="700">
</p>

---

## BDA Contour Output

<p align="center">
<img src="images/bda_contour_output.jpeg" width="700">
</p>

---

## MEDIAR Output

<p align="center">
<img src="images/mediar_output.jpeg" width="700">
</p>

---

## Comparative Output Visualization

<p align="center">
<img src="images/output_visualization.jpeg" width="700">
</p>

---

# 📚 References

1. Kirillov et al., *Segment Anything*, 2023.
2. Ultralytics, *YOLOv8 Documentation*.
3. Lee et al., *MEDIAR: Multi-Modality Microscopy Image Segmentation*, 2022.
4. Upschulte et al., *Contour Proposal Networks for Biomedical Instance Segmentation*, 2022.
5. Redmon et al., *You Only Look Once (YOLO)*, 2016.
6. Ren et al., *Mask R-CNN*, 2017.
7. Carion et al., *DETR: End-to-End Object Detection with Transformers*, 2020.
8. OpenCV Documentation.
9. Python Documentation.

---

# 🔮 Future Scope

- Improve detection accuracy using larger datasets.
- Fine-tune transformer-based models.
- Integrate real-time detection.
- Deploy the framework as a web application.
- Extend the framework for additional biomedical image analysis tasks.

---

# 👨‍💻 Author

**Kunam Reddy Veera Vamsiswar Reddy**

**B.Tech – Computer Science & Engineering (Artificial Intelligence)**

Manipal Institute of Technology Bengaluru

Academic Year: **2025–2026**

---

## ⭐ Acknowledgement

This project was carried out under the guidance of **Dr. Manaswita Saikia** as part of the Bachelor of Technology Final Year Project at **Manipal Institute of Technology Bengaluru**.
