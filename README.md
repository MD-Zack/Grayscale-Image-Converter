# Grayscale Image Converter 🖼️➡️⚫️

A beginner-friendly Python application that converts color images to grayscale using the OpenCV library.  
This tool allows you to load an image, preview it in grayscale, and save it in various common formats such as JPEG and PNG.

---

## Features ✨

- Load any RGB/color image from your local disk  
- Convert the image to grayscale for easier processing and analysis  
- Preview the grayscale image before saving  
- Save the image in common formats (`jpeg`, `png`, etc.)  
- User-friendly error handling and messages

---

## Requirements 🛠️

- Python 3.x  
- OpenCV (`opencv-python` package)

You can install OpenCV with pip:

pip install opencv-python

How to Use ▶️
Run the script from your terminal or command prompt:

bash
Copy
Edit
python grayscale_converter.py
Use the interactive menu:

Press 1 to select and convert an image to grayscale


Press 2 to save the last converted grayscale image in your desired format

Press 3 to exit the program

Follow the prompts to enter image paths and format

Example Output 📸

<img width="315" height="58" alt="image" src="https://github.com/user-attachments/assets/36673fea-e12c-42be-9726-04f3b9f231a6" />

Before:
<img width="982" height="343" alt="image" src="https://github.com/user-attachments/assets/123c4427-89be-4f55-8b2e-06d4a8212de2" />

After:
<img width="983" height="347" alt="image" src="https://github.com/user-attachments/assets/821f737b-6744-4da3-a021-93a3cfcefa76" />


Code Overview 💡
Uses cv2.imread() to load images

Converts images to grayscale via cv2.cvtColor() with the COLOR_BGR2GRAY flag

Displays images with cv2.imshow()

Saves images using cv2.imwrite()

Future Improvements 🚀
Add batch image conversion

Implement a GUI for easier use

Add other image processing filters (blur, edge detection, etc.)

Author ✍️
Created by [MD-Zack]

```bash




