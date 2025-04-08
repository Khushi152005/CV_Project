Computer Vision Algorithms
This project contains implementations of various computer vision algorithms using OpenCV and Python. Each notebook demonstrates a different feature detection or image matching technique.
car1.png
car2.png
mou1.jpg
mou2.jpg
chess.jpg
corner.jpg

SIFT.ipynb
Harris.ipynb
Shi_Tomasi.ipynb

Notebooks
SIFT.ipynb:
Implements Scale-Invariant Feature Transform (SIFT) to detect and match keypoints between two images.
➤ Images Used: car1.png, car2.png

Harris.ipynb:
Applies Harris Corner Detection algorithm to identify corners in an image.
➤ Image Used: img1.jpeg

Shi_Tomasi.ipynb:
Utilizes the Shi-Tomasi corner detection (Good Features to Track) to highlight strong corners.
➤ Image Used: img8.jpeg

🛠️ Requirements
Make sure the following libraries are installed:

Python 3.x

OpenCV (with contrib module for SURF)

NumPy

Matplotlib

Jupyter Notebook
pip install opencv-contrib-python matplotlib numpy

▶️ Usage
Open the repository in Jupyter Notebook.

Run any of the .ipynb notebooks to see the algorithm visualizations.

Make sure the required images are present in the same directory.
