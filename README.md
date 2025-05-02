# Seed Classification

This project is designed to classify seed images (rice, wheat, pulses, etc. and their varieties) using RESNET18 model with PyTorch and torchvision libraries.

---

## 🧠 Project Overview

The notebook includes:
- Dataset loading and preprocessing with transformations
- RESNET18 model definition using transfer learning (`torchvision.models`)
- Training and validation logic
- Accuracy and loss visualization
- Seed Variety Prediction

---

## ⚙️ Software Requirements

To run the notebook successfully, ensure the following packages are installed:

| Package        | Version (or higher) |
|----------------|---------------------|
| Python         | 3.7+                |
| PyTorch        | 1.9+                |
| torchvision    | 0.10+               |
| NumPy          | 1.19+               |
| OpenCV         | 4.x                 |
| Pillow         | 8.x                 |
| matplotlib     | 3.x                 |
| Google Colab   | *(recommended for path compatibility)* |

For installing packages:

```bash
pip install torch torchvision numpy opencv-python Pillow matplotlib
```

---

## 🖥️ Hardware Requirements

- **GPU (recommended):** CUDA-compatible GPU for faster training or you can also use Google Colab.
- **Disk Space:** Enough to store and process the image dataset.

---

## 📁 Dataset Structure

```
Cv seed dataset/
├── Class1/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── Class2/
│   ├── image1.jpg
│   └── ...
└── ...
```
---

## ▶️ How to Execute the Code

### Option 1: Google Colab (Recommended)
1. Upload the notebook to [Google Colab](https://colab.research.google.com).
2. Mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Make sure the dataset is at the correct path: `/content/drive/MyDrive/Cv seed dataset`.
4. Run the notebook cells in order.

### Option 2: Local Execution
1. Clone or unzip this repository.
2. Download the dataset locally on your system.
3. Modify the `base_path` in the notebook to the actual dataset location on your local system.
3. Run the notebook using Jupyter or any other IDE:
   ```bash
   jupyter notebook "Code_Seed Classification.ipynb"
   ```

---

## 📊 Output

- Model training logs
- Accuracy and loss curves
- Printed results of model performance
- Seed Variety Prediction

## Dataset [Seed Dataset](https://drive.google.com/drive/folders/1v11axFHP1xx3fRLh3WJ36VBO46a2yieO?usp=sharing)
