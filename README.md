# automatic-number-plate-recognition-python
This repository contains an efficient license plate recognition algorithm that utilizes the YOLOv3 model for accurate license plate detection. The algorithm is designed to process images and extract license plate information, including the alphanumeric characters present on the plates.

The YOLOv3 model is a state-of-the-art object detection algorithm known for its fast and accurate performance. To use this algorithm, please follow the steps below:

1- Download the YOLOv3 model weights file from the following Google Drive link: [[insert Google Drive link here]](https://drive.google.com/file/d/1IyIi_OQeMpl0QM34IbgoL0Zxbkt4IBBJ/view?usp=sharing). This model contains pre-trained weights that enable accurate object detection, including license plates.

2- After downloading the YOLOv3 model weights file, add it to the same repository where the code is located. This ensures that the algorithm can access the necessary model weights during runtime.

3- The main code file, license_plate_recognition.ipynb contains the algorithm implementation. You can use this file to perform license plate recognition on images . The algorithm utilizes the YOLOv3 model for license plate detection and then applies advanced optical character recognition (OCR) techniques to extract the alphanumeric characters from the detected plates.

4- The repository also includes example images and videos in the adnantest directory. Feel free to test the algorithm on these provided samples or replace them with your own images/videos for custom testing.

5- Make sure to install the required dependencies listed in the requirements.txt file. You can use pip to install them by running the following command: pip install -r requirements.txt.

6- Once you have added the YOLOv3 model weights and installed the dependencies, you can run the license_plate_recognition.py script to start the license plate recognition algorithm.

We hope this algorithm proves useful for your license plate recognition tasks. If you encounter any issues or have suggestions for improvement, please feel free to open an issue on this GitHub repository.

Happy license plate recognition!
