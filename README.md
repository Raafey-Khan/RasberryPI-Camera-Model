# Raspberry Pi Camera Model
![maxresdefault](https://github.com/Raafey-Khan/Rasberry_Pi0w2/assets/113880768/5d352c49-606b-44a0-bb80-efce1918cd25)

Raspberry Pi Camera Model is a project that utilizes computer vision techniques to detect motion and provide real-time video surveillance using a Raspberry Pi and a Raspberry Pi camera module. This project enables you to set up a reliable surveillance system using Python, OpenCV, and the Raspberry Pi camera.

# Features
Motion Detection: The project uses OpenCV to detect motion in the camera's field of view.
Real-Time Video Feed: The application provides a live video feed from the Raspberry Pi camera module.
Object Highlighting: Moving objects are highlighted with bounding boxes for easy identification.
Alert Sound: An alert sound is played when significant motion is detected.

# Prerequisites
Before setting up the Raspberry Pi Camera Model project, make sure you have the following:

Raspberry Pi: Any model of Raspberry Pi will work. (e.g., Raspberry Pi 3 Model B+)
Raspberry Pi Camera Module: Ensure you have a compatible camera module connected to the Raspberry Pi.
32 GB SD Card: A minimum of 32 GB SD card is recommended for storing captured images or videos.
Python: Make sure Python is installed on your Raspberry Pi. The project requires Python 3.x.
OpenCV: Install the OpenCV library on your Raspberry Pi using the following command:
shell
Copy code
pip install opencv-python
# Getting Started
Connect the Raspberry Pi Camera Module to the Raspberry Pi board following the manufacturer's instructions.
Clone this repository to your Raspberry Pi:
shell
Copy code
git clone https://github.com/Raafey-Khan/RasberryPI-Camera-Model.git
Navigate to the project directory:
shell
Copy code
cd Raspberry-Pi-Camera-Model
Run the Python script:
shell
Copy code
python main.py
The application will start and display the live video feed from the Raspberry Pi camera module.
Any detected motion will be highlighted with bounding boxes, and an alert sound will be played.
# Configuration
Threshold: You can adjust the motion detection sensitivity by modifying the threshold value in the Python script.
python
Copy code
_, thresh = cv2.threshold(blur, 20, 255, cv2.THRESH_BINARY)
Sound: You can customize the alert sound by replacing the alert.wav file with your desired sound file.
# License
This project is licensed under the MIT License.

# Acknowledgements
OpenCV - Open Source Computer Vision Library
Raspberry Pi - Single-board computer for embedded projects
# Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request.

# Contact
For any inquiries or feedback, please contact [loyaalboy@gmail.com].




