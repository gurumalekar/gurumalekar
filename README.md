# Gururaj Malekar

**Machine Learning Engineer | Computer Vision | Deep Learning | Industrial & Medical Imaging**

📍 Pune, India  
🏢 Machine Learning Engineer @ Pixonate Labs

I build end-to-end computer vision systems spanning **model development, image processing, industrial cameras, embedded control, GPU inference, and production deployment**.

My work sits at the intersection of:

- Industrial Computer Vision
- Deep Learning
- Medical Imaging & Computational Pathology
- Embedded Vision Systems
- High-Resolution Image Processing
- Production ML

I enjoy problems where the solution involves more than training a model: camera behaviour, optics, motion, hardware synchronization, inference performance, failure analysis, and real-world deployment all matter.

---

## Technical Stack

| Area | Technologies |
|---|---|
| **Computer Vision** | OpenCV, YOLO, Object Detection, Instance Segmentation, Image Registration, Phase Correlation, OCR, Image Processing |
| **Deep Learning** | PyTorch, TensorFlow/Keras, Scikit-learn, CNNs, Vision Transformers, Anomaly Detection |
| **Medical Imaging** | Whole Slide Imaging, CellViT, HoVer-Net, UNet++, SMP, Nuclei Detection & Segmentation |
| **Inference & Deployment** | ONNX, ONNX Runtime, CUDA, Docker, AWS SageMaker |
| **Industrial Vision** | Industrial Cameras, PLC Integration, Modbus TCP/IP, Hardware Triggering, Automated Inspection |
| **Embedded Systems** | Raspberry Pi Pico 2, MicroPython, Servo Control, Sensors, Serial Communication |
| **Backend & Systems** | FastAPI, asyncio, REST APIs, WebSockets, Linux, Git |
| **Data** | NumPy, Pandas, ClickHouse, SQL, pyvips, BigTIFF |

---

# Selected Work

## PCB Micro Scanner & Automated Vision Gantry

One of my most systems-heavy computer vision projects.

Built an automated microscopic PCB scanning platform combining:

- **12 MP industrial camera acquisition**
- **Raspberry Pi Pico 2**
- Closed-loop servo-controlled X/Y motion
- Inductive limit sensors
- Custom MicroPython firmware
- Asynchronous Python hardware control
- Computer vision-based image registration
- Gigapixel-style image stitching

### Vision

Implemented **sub-pixel image registration using FFT-based phase correlation** to estimate translations between overlapping image tiles.

To prevent cumulative drift across large scans, the system uses global tile-position optimization rather than relying solely on sequential pairwise alignment.

Additional processing includes:

- Median Absolute Deviation based outlier rejection
- Center-weighted overlap blending
- Memory-efficient image composition
- Pyramidal BigTIFF generation using `pyvips`

### Motion & Embedded Control

Developed Pico 2 firmware for:

- Servo motion control
- Trapezoidal acceleration/deceleration
- Limit-switch monitoring
- Position tracking
- Hardware safety constraints
- PC ↔ MCU serial communication

The system also supports **continuous-motion acquisition**, where the controller emits positional capture events while the gantry is moving and the host application asynchronously triggers the industrial camera.

### Application Stack

`Python` · `OpenCV` · `NumPy` · `pyvips` · `FastAPI` · `asyncio` · `MicroPython` · `React` · `Tauri`

---

## Whole-Slide Histopathology Analysis

Worked on deep-learning pipelines for high-resolution histopathology images involving:

- Nuclei detection
- Instance segmentation
- Cell classification
- Patch-based Whole Slide Image processing
- Morphological analysis
- Quantitative model validation

Models and frameworks explored include:

`YOLO` · `UNet++` · `CellViT` · `HoVer-Net` · `segmentation-models-pytorch`

### Open-source work

### [YOLO + UNet++ Nuclei Segmentation](https://github.com/gurumalekar/yolo-nuke-seg)

Two-stage pipeline combining object localisation with segmentation for high-resolution pathology images.

---

## Industrial Computer Vision

Developed and deployed vision systems for manufacturing inspection involving:

- Defect detection
- Object detection
- Classification
- Anomaly detection
- Image preprocessing
- Classical computer vision
- Production threshold tuning
- OK / NG inspection logic

Worked with real production samples to analyse:

- False positives
- False negatives
- Lighting variation
- Surface variation
- Previously unseen defect conditions

Integrated vision decisions with industrial machinery using **PLC communication over Modbus TCP/IP**.

---

## Automated Sickle Cell Screening

Developed a microscopy analysis pipeline combining:

1. Cell detection
2. Cell-level classification
3. Sample-level decision logic

The system produces:

- Disease
- Trait
- OK

outcomes from microscopic blood-smear images.

**Stack:** `YOLO` · `PyTorch` · `OpenCV`

---

## OCR & Industrial Imaging

Worked on OCR pipelines for challenging real-world imagery, including:

- Seven-segment displays
- Character detection
- Image normalization
- ROI extraction
- Rotation handling
- Detection post-processing
- OCR confidence analysis

I am particularly interested in OCR systems where **correct structure and character count** matter as much as raw recognition accuracy.

---

## Cybersecurity ML Pipeline

Built an inference workflow integrating:

- Graph-based ML models
- AWS SageMaker
- ClickHouse
- Scheduled inference
- Prediction persistence
- Model evaluation

Worked on machine-learning approaches for **Domain Generation Algorithm (DGA) detection**.

---

# Research

## A Cytology Dataset for Early Oral Squamous Cell Carcinoma Detection

Contributed to work involving a multicenter oral cytology dataset containing expert-annotated PAP and MGG-stained slides.

The project explores AI-assisted cellular analysis for early oral cancer detection.

**Preprint:**  
[arXiv:2506.09661](https://arxiv.org/abs/2506.09661)

---

# What I Like Working On

I am especially interested in:

- Production Computer Vision
- Industrial Machine Vision
- Medical Imaging
- Vision Transformers
- Image Registration
- Edge AI
- 3D Vision
- Multi-camera Systems
- Robotics Perception
- GPU Inference
- Computer Vision + Embedded Systems

I prefer projects where I can understand and improve the **entire system**, from photons entering the camera to the final production decision.

---

# Currently Learning

Deepening my understanding of:

- Linear Algebra for ML
- Probability & Statistics
- SVD / PCA
- 3D Geometry
- Structure from Motion
- SLAM
- NeRF
- Gaussian Splatting
- Vision-Language Models
- Efficient model inference

---

<div align="center">

[**LinkedIn**](https://linkedin.com/in/gururajmalekar/) ·
[**GitHub**](https://github.com/gurumalekar) ·
[**Email**](mailto:gurumalekar@gmail.com)

</div>