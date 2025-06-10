# color-classification-lightgbm
A program that identifies color of each pixel of the image, printing the color of each pixel.


Color Classification using LightGBM
-This project uses a trained LightGBM classifier to identify and classify colors pixel-by-pixel in an input image. The model is trained on labeled RGB values from a curated dataset of color names.

Files Included
-Color classification using LightGBM.ipynb – Jupyter notebook containing the full training and inference pipeline.

-color_names.csv – Dataset of color names with RGB values.

-fluorescent_green__50940.webp – Sample image used for pixel-level color classification.

Features
-Trains a LightGBMClassifier on labeled RGB color data.

-Uses OpenCV to read and convert image from BGR to RGB format.

-Predicts and prints the color of each pixel in a test image using the trained model.

-Encodes color names using LabelEncoder.

How to Run
-Clone the repo or download the .ipynb file and necessary assets.

-Install required packages (in Colab or locally):

bash
Copy
Edit
pip install lightgbm opencv-python-headless scikit-learn pandas
-Run the notebook:

-Upload the color_names.csv and the image file.

-Execute all cells in the notebook.

Example Output:
csharp
Copy
Edit
color of pixel in 0 0 is Light Green
color of pixel in 0 1 is Light Green
...
Each pixel is classified into a predefined color name based on its RGB value.

Dependencies
-Python 3.7+

-pandas

-scikit-learn

-lightgbm

-opencv-python / opencv-python-headless (for Colab)

Future Improvements
-Optimize performance for large images (current version is pixel-by-pixel and slow).

-Use vectorized prediction instead of nested loops.

-Visualize classified color masks.

-Add GUI or interactive color map.

Author
Batyr – https://github.com/batyrq
