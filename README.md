# Image Processing App

This project is a simple Python-based graphical user interface (GUI) application for applying various image processing techniques using OpenCV and Tkinter.

## Features

The application provides the following image processing functionalities:
1. **Noise Addition**: Adds random noise to the image.
2. **Blurring**: Applies Gaussian blur to smooth the image.
3. **Low Contrast Adjustment**: Reduces the contrast of the image using linear scaling.
4. **Global Thresholding**:
   - Otsu's Binarization
   - Triangle Thresholding
5. **Adaptive Thresholding**:
   - Adaptive Mean Thresholding
   - Adaptive Gaussian Thresholding
6. **Pixel-wise Inversion**: Inverts the image pixel values.
7. **High Contrast Adjustment**: Enhances the image contrast using linear scaling.

## Prerequisites

Ensure you have Python 3 installed and the following libraries:

- `numpy`
- `opencv-python`
- `Pillow` (for Tkinter compatibility)
- `tkinter` (usually included with Python)

You can install the necessary libraries using pip:

```bash
pip install numpy opencv-python pillow 
```
## How to Run

1. Save the script to a file, e.g., `image_processing_app.py`.

2. Open a terminal or command prompt in the script's directory.

3. Run the script:

   ```bash
   python image_processing_app.py
A GUI window will open with two buttons:

```Выбрать изображение: Opens a file dialog to select an image (*.jpg, *.jpeg, or *.png).```
```Стоп: Closes all OpenCV windows.```
After selecting an image, the following processed versions will be displayed in separate OpenCV windows:

- **Original Image**
- **Noisy Image**
- **Blurred Image**
- **Low Contrast Image**
- **Global Threshold (Otsu)**
- **Adaptive Threshold (Mean)**
- **Inverted Image**
- **High Contrast Image**

## Files

No additional files are required apart from the script itself.
