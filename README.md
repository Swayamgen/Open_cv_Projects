# Face Detection and Image Capture

This Python script utilizes OpenCV's Haar Cascade Classifier to perform real-time face detection using a webcam. The program draws rectangles around detected faces and allows the user to capture images by pressing a key. These images are then saved to a specified directory on your local machine.

## Overview

This project is a Python script that:

- Uses a webcam to capture video in real-time.
- Detects faces in the video feed using a pre-trained Haar Cascade Classifier.
- Draws rectangles around detected faces.
- Allows the user to capture images by pressing the 'c' key.
- Saves the captured images to a user-defined directory.
- Exits the program when the 'q' key is pressed.

## Prerequisites

To run this script, you will need:

- Python 3.x installed on your system.
- OpenCV library (cv2).

To install OpenCV, run the following command:

```bash
pip install opencv-python
``` 
## Code Overview

The script performs the following tasks:

1. **Load the pre-trained Haar Cascade model** for face detection. This model is used to detect frontal faces in real-time video streams.
2. **Capture video from the webcam** and process each frame to detect faces.
3. **Draw rectangles around detected faces** in the video feed.
4. **Save captured images** when the user presses the 'c' key. The images are stored in a specified directory on the local machine.
5. **Exit the program** when the 'q' key is pressed.

## How to Use

1. Clone or download the repository.
2. Install the required dependencies (OpenCV).
3. Modify the `save_directory` variable in the script to specify where images should be saved on your machine.
4. Run the script. You will see a live webcam feed with rectangles drawn around detected faces.
5. Press the 'c' key to capture an image and save it to the specified directory.
6. Press the 'q' key to exit the application.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- This project uses the OpenCV library for real-time computer vision tasks.
- The Haar Cascade classifier used in this script was pre-trained by OpenCV contributors.

