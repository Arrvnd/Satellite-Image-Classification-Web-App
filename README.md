# 🛰️ Satellite Image Preprocessing & Classification Dataset Builder
### 📘 Project Overview

This project focuses on preprocessing satellite imagery for machine learning tasks such as land classification or cloud detection.
The notebook processes raw satellite images from multiple folders (e.g., cloudy, desert, etc.), resizes them to a uniform shape, converts them into numerical arrays, and compiles them into a structured Pandas DataFrame ready for model training.

## link - https://huggingface.co/spaces/Arrvind/satellite_image_classifier

### 🧩 Key Features

Loads and processes satellite images from multiple categories.

Converts all images to RGB and resizes them to 224×224 pixels.

Flattens image data into numerical arrays.

Combines all images into a single labeled dataset for machine learning models.

Easily extendable to include new categories or apply additional transformations.

### 🛠️ Technologies Used

Python 3.x

OpenCV (cv2)

NumPy

Pandas

Pillow (PIL)

Matplotlib (for visualization)

### 🔮 Future Enhancements

Automate dataset splitting (train/test/validation)

Add image augmentation

Integrate CNN model training (TensorFlow/PyTorch)

Implement feature extraction using pre-trained models (e.g., VGG16, ResNet)

### 📊 Output

After successful execution, a DataFrame will be created where:

Each row represents one image.

Each column represents a pixel value.

A final column (type) indicates the image label (e.g., cloudy, desert).
