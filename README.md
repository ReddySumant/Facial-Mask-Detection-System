# Facial Mask Detection System

## Project Overview
The Facial Mask Detection Model is a deep learning solution developed to enhance public safety during the COVID-19 pandemic. The model accurately detects the presence of facial masks on individuals, providing a reliable tool for monitoring mask compliance in various settings.

## Key Features
* Highly accurate facial mask detection using Deep Learning (MobileNet)
* Efficient data preparation and feature extraction with TensorFlow and Scikit-learn
* Seamless integration with Python (OpenCV) for image processing
* Real-time detection capability for immediate feedback
* Customizable to suit different environments and scenarios
## Installation
1. Clone the repository:
```http
git clone https://github.com/ReddySumant/Facial-Mask-Detection-System.git
```
2. Install the required dependencies:
```http
pip install -r requirements.txt
```
3. Download the pre-trained MobileNet model "mask_detector.model" file.

4. Launch the application:
```http
python detect_mask_video.py
```
## Usage
1. Open the application and ensure your camera is properly connected.

2. Stand in front of the camera, ensuring your face is clearly visible.

3. The model will analyze the video feed in real-time and display the results on the screen.

4. If a facial mask is detected, the corresponding bounding box will be highlighted in green. Otherwise, it will be highlighted in red.

5. To exit the application, press Q on your keyboard.

## Dataset and Training
The model was trained on a diverse dataset consisting of images with and without facial masks. The dataset was carefully curated and labeled for accurate training and validation. Training was performed using TensorFlow, leveraging the powerful MobileNet architecture.

## Contributing
We welcome contributions to further improve the Facial Mask Detection Model. If you encounter any issues or have suggestions for enhancements, please submit an issue or create a pull request. I appreciate your valuable input.

## Acknowledgements
I would like to thank the open-source community for their invaluable contributions and the developers of TensorFlow, Scikit-learn, and OpenCV for their powerful libraries.

## Contact
For any inquiries or further information, please contact me at reddysumant25@gmail.com

Thank you for using the Facial Mask Detection Model. Stay safe!




