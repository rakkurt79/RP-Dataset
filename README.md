# RP-Dataset: Red Pine Seedling Dataset

**RP-Dataset** is an image-based dataset created for **object detection** tasks.  
The dataset is specifically designed for research and experimental purposes in the field of **precision forestry** and **post-fire forest restoration**.

---

## 🌲 Dataset Overview

Post-fire forest restoration is vital for ecosystem re-establishment, biodiversity conservation, and climate change adaptation. Accurate monitoring of seedling density—especially for dominant species like **Red Pine (*Pinus brutia*)**—is essential. 

Traditional field studies are labor-intensive and prone to error in challenging terrains. **RP-Dataset** provides the first comprehensive drone imagery dataset specifically curated to detect **0-1-year-old red pine seedlings**, enabling the development of next-generation AI models for adaptive forest management.

## 📁 Dataset Details

- **Image format:** `JPG / PNG`
- **Annotation format:** `YOLO / TXT` (Compatible with Faster R-CNN and Transformer-based models)
- **Image resolution:** `640×640`
- **Number of images:** `1,603`
- **Total Annotations:** `4,600` seedlings
- **Key Challenges:** Small object detection, weed occlusion, and varied spatial distributions.

### 📌 Classes
| ID | Class Name | Description |
|----|------------|-------------|
| 0  | rp         | 0-1 year old Red Pine (*Pinus brutia*) seedling |

---

## 🚀 Benchmarks & Validation

To ensure dataset robustness, the following architectures were comparatively applied and validated:
* **YOLO Series** (v5, v8, etc.)
* **Faster R-CNN**
* **Transformer-based models**

Experimental results demonstrate that the **RP-Dataset** is a high-quality resource for developing robust AI models in challenging forest environments.

---

## 🔗 Download Link

The dataset is hosted on Google Drive:

👉 **[RP-Dataset (Google Drive)](https://drive.google.com/XXXXXXXXXXXXXXXX)** > **Note:** The link will be available after the formal review process is completed.

---

### 📝 Citation
Please cite the original study:
*.....................*
