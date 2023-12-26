# Face Mask Detection

This is a code snippet that demonstrates face mask detection using pre-trained models. It uses Haarcascade for face detection and a deep learning model for mask classification.

## Prerequisites

- Python 3.x
- OpenCV
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Instructions

1. Clone the repository or download the code files.

2. Ensure that the required packages are installed. You can install the dependencies using the following command:

   ```
   pip install --upgrade pip
   pip install -r requirements (нужная версия ОС)
   pip install opencv-python tensorflow keras numpy matplotlib
   ```

3. Run the code using a Python interpreter.

   ```
   python your_code_file.py
   ```

4. The code will first download the pre-trained models if they are not already present in the `models` directory.

5. It will then perform face detection and mask classification on the provided images or live video from the webcam.

   - To test the code on images, update the `test_image_file` variables with the path to your test images and run the `display_face_detection_result` function.

   - To test the code on live video, run the code without any modifications. Press 'q' to exit the video feed.

Note: Make sure that your computer has a webcam connected if you want to test the live video functionality.

Please refer to the code comments for more details on the implementation.
