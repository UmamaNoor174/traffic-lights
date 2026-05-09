
**Interactive Traffic Signal Detector** 🚦🖱️**
A smart Computer Vision tool that identifies traffic light signals (Red, Yellow, Green) through manual pixel-point interaction. This project demonstrates color-space transformation (BGR to HSV) and event-driven programming using Python.

📌 **Project Overview**
This application allows users to load any traffic signal image and detect the current signal by simply clicking on the light. It uses the HSV (Hue, Saturation, Value) color model, which is more robust for color detection compared to standard RGB. This logic is fundamental for developing autonomous vehicle systems and smart city traffic monitoring.

✨ **Key Features**
1. File Picker GUI: Uses Tkinter to provide a user-friendly window for selecting image files.

2. HSV Color Analysis: Accurately distinguishes between Red, Yellow, and Green signals based on specific Hue ranges.

3. Mouse Event Handling: Features a custom callback function that processes coordinates upon a left-click.

4. On-Screen Feedback: Dynamically displays the detected signal status (e.g., "Red for STOP") directly on the image.

5. Responsive Resizing: Automatically adjusts image dimensions (400x400) for consistent visualization.

🛠️ **Technical Stack**
1. Language: Python 3.11

2. Core Libraries:

3. OpenCV: For image processing, color conversion, and GUI events.

4. Tkinter: For the native file selection dialog.

5. NumPy: For handling image arrays and pixel values.

6. Environment: Developed as part of Artificial Intelligence research.

**Setup and Installation**
1. Clone the Repository:
Bash
git clone https://github.com/UmamaNoor174/traffic-signal-detector.git
cd traffic-signal-detector

2. Install Dependencies:
Ensure you have the required libraries installed:
Bash
pip install opencv-python numpy

3. Run the Application:
Bash
python traffic_lights.py

🎮 **How to Use**
1. Select Image: Upon running, a file browser will open. Select an image containing a traffic light.

2. Interactive Detection: Click on the lit part of the traffic signal (Red, Yellow, or Green).

3. View Result: The console and the image window will instantly display the detected signal meaning:

    Red: STOP

    Yellow: READY

    Green: GO

4. Exit: Press any key to close the application.

🎓 **Academic Context**
This project is an extension of the computer vision research conducted in the Department of Information Technology. The color detection algorithms used here provide a foundation for complex AI-Based Student Behaviour Monitoring Systems, where identifying specific environmental cues is essential.

👤 **Developer**
Umama Noor
