
## Text Detection and Recognition using EasyOCR and OpenCV

### Overview:
This project aims to perform text detection and recognition using the EasyOCR and OpenCV libraries in Python. Text detection involves locating and identifying regions of text within an image, while text recognition refers to the process of converting these text regions into machine-readable text.

<img width="1440" alt="image" src="https://github.com/DivZyzz/Object-Detection-/assets/136096930/af9e96bf-9eff-43bb-a39f-910072f63046">

### Key Components:
1. **EasyOCR:** EasyOCR is a Python library that provides a simple interface for performing Optical Character Recognition (OCR). It supports various languages and can detect multiple languages within the same image.
   
2. **OpenCV:** OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. It provides various functions and algorithms for image processing, including reading and displaying images, as well as drawing bounding boxes and text on images.

### Workflow:
1. **Image Input:** The project starts by reading an input image containing text using OpenCV's `cv2.imread()` function.

2. **Text Detection:** EasyOCR is then used to detect text regions within the input image. The `readtext()` function from EasyOCR returns the bounding box coordinates and recognized text for each detected text region.

3. **Drawing Bounding Boxes:** OpenCV is employed to draw bounding boxes around the detected text regions. The `cv2.rectangle()` or `cv2.polylines()` functions are used for this purpose.

4. **Text Recognition:** The recognized text from each text region is extracted using EasyOCR.

5. **Display Output:** The final output image with bounding boxes and recognized text is displayed using OpenCV's `cv2.imshow()` or saved to a file.


### Potential Applications:
- Document scanning and digitization.
- Automatic number plate recognition (ANPR) systems.
- Extracting text from images for translation or analysis purposes.

<img width="1440" alt="image" src="https://github.com/DivZyzz/Object-Detection-/assets/136096930/18b8a68b-296c-4b08-9e0d-66ac53ac8246">

<img width="1440" alt="image" src="https://github.com/DivZyzz/Object-Detection-/assets/136096930/de5a4e93-24ef-45f9-b93c-9687353d9f4a">
