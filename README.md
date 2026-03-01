# 🍚 Rice Crop Disease Detection using YOLO

<p align="center">
  <b>Deep Learning Model for Detecting Diseases in Rice Leaves Using YOLO</b><br>
  Built with Python • YOLOv3 • CNN • Image Annotation
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Deep_Learning-CNN-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Object_Detection-YOLOv3-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-In_Progress-yellow?style=for-the-badge">
</p>

---

## 🚀 Project Overview

Rice Crop Disease Detection using YOLO is a **computer vision application** that identifies diseases in rice leaf images using a YOLO-based Convolutional Neural Network.

The goal is to help farmers accurately detect diseases at early stages, enabling timely treatment and higher crop yields.

---

## 🎯 Objectives

By completing this project, you will:

* Understand object detection using **YOLOv3**
* Learn image annotation techniques using **VoTT**
* Build and train a deep learning model for disease detection
* Apply inference to detect real diseases in leaf images
* Prepare for real-world agricultural automation systems

---

## 🧠 Business Understanding

In many agricultural regions, rice crops are affected by diseases like **Bacterial Blight**, **Leaf Smut**, and **White Tip**, which reduce yield and quality.

Detecting these diseases early improves crop management and increases production, directly impacting food security in many communities.

---

## 📊 Data Understanding

This project uses a custom dataset of rice leaf images with disease labels.
Annotated images are required for training the YOLO model.

* 📁 **Data Folder** – contains images separated into classes
* 🏷 **Annotations** – bounding boxes for diseased regions
* 🧠 **Training Data** – used to train the YOLOv3 model

> The dataset can be annotated using tools like Microsoft VoTT or LabelImg.

---

## 🖼️ Screenshots (Example)

*(Add these images into a local `screenshots` folder and update paths)*

### 📷 Annotated Images

```markdown
![Annotated Leaf](screenshots/annotated_leaf.png)
```

### 🧪 Model Training Output

```markdown
![Training Result](screenshots/training_output.png)
```

### 🧾 Inference Results

```markdown
![Detected Disease](screenshots/inference_results.png)
```

---

## 📦 Folder Structure

```text
SI-GuidedProject-416101-1670232069/
├── 1_Image_Annotation/        # Annotation files and tools
├── 2_Training/                # Training code and model weights
├── 3_Inference/               # Inference and detection scripts
├── Data/                      # Dataset images and labels
├── Utils/                     # Helper functions
├── Demo Link/                 # Demo related files
├── Documentation/             # Project related docs
├── requirements.txt           # Required packages
└── README.md                  # This file
```

---

## 🛠️ Tech Stack

| Component | Technology                                    |
| --------- | --------------------------------------------- |
| Language  | Python                                        |
| Model     | YOLOv3                                        |
| Framework | Deep Learning / CNN                           |
| Tools     | VoTT (annotation), OpenCV                     |
| Libraries | TensorFlow / PyTorch (if used), NumPy, OpenCV |

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/smartinternz02/SI-GuidedProject-416101-1670232069.git
cd SI-GuidedProject-416101-1670232069
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Run Model Training

Go to `2_Training/` and run:

```bash
python train.py
```

### 5. Inference (Detect Diseases)

Go to `3_Inference/` and run:

```bash
python detect.py --image <path_to_test_image>
```

---

## 🧠 Model Development Workflow

1. **Image Annotation**

   * Annotate leaf images using VoTT or LabelImg
   * Save bounding boxes for diseased regions

2. **Prepare Training Data**

   * Create class labels
   * Format data for YOLO training

3. **Train YOLOv3 Model**

   * Run training script using annotated dataset
   * Save trained weights

4. **Inference / Detection**

   * Use trained model to detect diseases on new images

5. **Evaluation**

   * Assess model accuracy and performance

---

## 📌 Status

🔄 Work in Progress – Currently under guided project completion.
Future improvements may include:

* UI for real-time detection
* Deployment as a web/API service
* Integration with mobile app for farmer usage

---

## 🙌 Credits

Guided Project under SmartInternz Program.
Thanks to the course instructors and open-source contributors.

---

## 📚 References

* YOLOv3 — *You Only Look Once* object detection architecture
* Microsoft VoTT — Image annotation tool

[1]: https://github.com/smartinternz02/SI-GuidedProject-416101-1670232069.git "GitHub - smartinternz02/SI-GuidedProject-416101-1670232069: Rice Crop Disease Detection using YoLO"
