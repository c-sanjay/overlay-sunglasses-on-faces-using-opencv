😎 Overlay Sunglasses on Faces using OpenCV

A computer vision application that detects human faces in images and overlays sunglasses with proper scaling and alignment using OpenCV and Python.

📌 Project Summary

This project demonstrates practical implementation of image processing, face detection, and alpha blending techniques. It dynamically positions a transparent sunglasses image on detected faces, ensuring proportional resizing and realistic placement.

The application highlights foundational concepts used in augmented reality filters, similar to those used in social media platforms.

🚀 Key Features
Robust face detection using OpenCV Haar Cascades
Dynamic overlay scaling based on face dimensions
Accurate placement over eye region
Support for transparent PNG overlays (alpha channel blending)
Modular and extensible code structure
🛠️ Tech Stack
Language: Python
Libraries: OpenCV, NumPy
Concepts: Image Processing, Object Detection, Alpha Blending
📂 Repository Structure
overlay-sunglasses-on-faces-using-opencv/
│
├── main.py                 # Core implementation
├── sunglasses.png         # Transparent overlay asset
├── input.jpg              # Sample input image
├── requirements.txt       # Dependencies
└── README.md              # Documentation
⚙️ Installation & Setup
git clone https://github.com/c-sanjay/overlay-sunglasses-on-faces-using-opencv.git
cd overlay-sunglasses-on-faces-using-opencv
pip install -r requirements.txt
▶️ Execution
python main.py

The script will:

Detect faces in the input image
Compute appropriate scaling for the sunglasses
Overlay the image using transparency blending
🧠 Technical Approach
1. Face Detection

Utilizes Haar Cascade classifiers to identify bounding boxes around faces.

2. Region Estimation

Approximates the eye region based on facial geometry.

3. Image Resizing

Scales the sunglasses proportionally to face width.

4. Alpha Blending

Applies overlay using mask separation:

Foreground (sunglasses)
Background (face region)
Transparency mask
📊 Example Workflow
Input Image → Face Detection → Region Mapping → Resize Overlay → Blend → Output Image
📸 Results
Automatically detects faces
Places sunglasses with realistic alignment
Works for multiple face sizes


🔍 Use Cases
Augmented Reality filters
Social media effects
Computer vision learning projects
Real-time camera applications
