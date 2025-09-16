# 🖼️ Image Separator

**Image Separator** is a Python-based tool that helps you **automatically classify and separate images** based on their contents using face detection. It's designed to organize images from a large dataset into separate folders like **People**, **Dataset**, and **Output**, making it easier for users to work with image-based projects.

---

## 📁 Folder Structure

Before running the script, make sure to create the following directories in the root of your project:

/Image_Separator
│

├── Dataset/ # Place all input images here

├── People/ # Images with human faces will be moved here, crop them so that they can be used to make encodings.

├── Output/ # Processed or categorized images (optional usage)

└── image_separator.py # Main script


---

## 🚀 Features

- 🔍 Detects and filters images containing human faces  
- 🗂️ Moves images with faces to the `People/` folder  
- 🧹 Keeps your datasets clean and organized

---

## ⚙️ How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/raghavpatidarr/Image_Separator.git
   cd Image_Separator
2. **Install dependencies:**
   ```
   pip install opencv-python
   ```
3. **Add your images:**
   ```
   Place all images you want to process in the Dataset/ folder.
   ```
4. **Run the script:**
   ```
   python image_separator.py
   ```
5. **Check results:**
   ```
   Images with detected faces will be moved to the Output folder.
   ```
🧠 How It Works
The script uses OpenCV's Haar Cascade Classifier to detect faces in each image inside the Dataset/ folder.
If a face is found, the image is automatically moved to the People/ directory for further use.

📌 Requirements
Python 3.x
OpenCV (opencv-python)

👤 Author : Raghav Patidar
- **LinkedIn**: [Raghav Patidar](www.linkedin.com/in/raghav-patidar-9954a52b8)
