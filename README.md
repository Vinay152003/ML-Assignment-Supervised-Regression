# ML Assignment - Supervised Regression

## 🎯 Problem Statement
Develop a deep learning model to predict the **(x, y) coordinates** of a single white pixel (value 255) in a **50x50 grayscale image**, where all other pixels are zero. This is a supervised regression task with a synthetic dataset.

---

## 🧠 Approach

- Generated synthetic image data where only one pixel is white (255) and all others are black (0).
- Used a Convolutional Neural Network (CNN) for spatial feature extraction.
- Predicted continuous (x, y) coordinates using a dense regression head.
- Evaluated using MSE and MAE metrics.
- Visualized loss curves and sample predictions.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `ML_Assignment_Supervised_Regression.ipynb` | Full training code, graphs, and results |
| `requirements.txt` | Python dependencies to reproduce results |
| `Graphs-Loss and MAE Curves.png & Prediction vs Ground Truth Visualization.png` | Output visualization of predictions vs ground truth |
| `README.md` | Project overview and instructions |

---

## 📊 Results

- Achieved a Mean Absolute Error (MAE) of ~0.42 on validation data.
- Model accurately predicted the pixel's location with low error.

---

## ⚙️ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ML-Assignment-Supervised-Regression.git
   cd ML-Assignment-Supervised-Regression
