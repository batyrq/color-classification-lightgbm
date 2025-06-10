#  Color Classification using K-Nearest Neighbors (KNN)

This project identifies the color of **each pixel** in an image using a trained **K-Nearest Neighbors (KNN)** classifier. The model is trained on labeled RGB values from a curated dataset of color names and predicts the closest color name for every pixel in a test image.

---

##  Files Included

- `Color classification using KNN.ipynb` – Jupyter notebook containing the full training and inference pipeline.
- `color_names.csv` – Dataset of named colors with RGB values.
- `fluorescent_green__50940.webp` – Sample image used for pixel-level color classification.

---

##  Features

- Trains a `KNeighborsClassifier` on labeled RGB color data.
- Uses OpenCV to load and convert images from BGR to RGB format.
- Predicts and prints the color of each pixel in the image.
- Encodes color labels using `LabelEncoder` for model training.
- Simple and interpretable KNN approach (better than logistic regression for this task).

---

##  How to Run

1. **Clone the repo** or download the `.ipynb` file and necessary assets (`.csv`, `.webp`).
2. **Install required packages** (if running locally or in Colab):

   ```bash
   pip install scikit-learn opencv-python-headless pandas

## Author

**Batyr**  
[GitHub Profile](https://github.com/batyrq)
