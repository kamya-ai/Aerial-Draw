# 🖌️ Air Sketch with OpenCV

## 📝 Description
This project is an interactive air sketch application developed using Python and OpenCV. It allows users to create artistic sketches by moving a pointer in the air. By tracking the path of the pointer, the application generates a sketch-like image that represents the movement.


## 🎥 Demo
https://github.com/kamya-ai/Aerial-Draw/assets/139073975/e9647790-ff23-41e8-802f-c3437b003087



## ⭐️ Features
- Real-time pointer tracking: The application utilizes computer vision techniques provided by the OpenCV library to track the movement of a pointer in real-time.
- Sketch generation: 🎨 By analyzing the path of the pointer, the application generates a sketch-like image that captures the movement dynamics.
- Image saving: The generated sketch image can be saved as an output file for further use or sharing.

## 📋 Requirements
- Python 3.x
- OpenCV library
- Numpy library

## 🔧 Installation
1. Ensure that Python is installed on your system. You can download it from the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Install OpenCV by running the following command:
   ```
   pip install opencv-python
   ```
3. Install Numpy by running the following command:
   ```
   pip install numpy
   ```
4. Download or clone the project files from the GitHub repository: [https://github.com/kamya-ai/Aerial-Draw.git](https://github.com/kamya-ai/Aerial-Draw.git)

## ▶️ Usage
1. Open a terminal or command prompt and navigate to the project directory.
2. Run the following command to start the application:
   ```
   python run.py
   ```
3. A new window will open, displaying the camera feed. Make sure your camera is properly connected and functioning.
4. Hold a pointer (e.g., a pen, stylus, or finger) in front of the camera.
5. Move the pointer in the air to create sketches.
6. Press the following keys to interact with the application:
   - `Esc`: Quit the application.
7. When you are satisfied with your sketch, press `Esc` to exit the application. The generated sketch will be saved as `output.jpg` in the project directory.

## 🔍 Troubleshooting
- If you encounter any issues with the camera feed or pointer tracking, make sure your camera is properly connected and functional. You can also try adjusting the lighting conditions in the environment.
- If you face any errors related to missing libraries, ensure that you have correctly installed OpenCV and Numpy by following the installation instructions.
