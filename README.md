# Real-Time Object Measurement Using OpenCV

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project demonstrates a real-time object measurement system using OpenCV. The application captures video frames from a camera, detects objects, and measures their dimensions in real-time. It leverages computer vision techniques such as edge detection, contour approximation, and camera calibration to measure the height and width of objects within the camera's view.

## Features
- **Real-Time Object Detection**: Detects objects in live video streams using OpenCV.
- **Accurate Measurements**: Measures the height and width of detected objects in real-time.
- **Multiple Object Support**: Detects and measures multiple objects simultaneously.
- **Camera Calibration**: Uses calibration techniques to improve the accuracy of measurements.
- **Edge Detection**: Uses Canny edge detection for accurate object boundary detection.
- **Contour Detection**: Identifies and processes object contours for precise measurement.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy
- **Camera Interface**: Any standard webcam or external camera supported by OpenCV
- **IDE**: PyCharm, Jupyter Notebook, or any Python-compatible environment

## Setup Instructions

### Prerequisites
- Python 3.x
- OpenCV library
- NumPy library

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/anrao0037/Real-Time-Object-Measurement-Using-OpenCV-.git
   ```

2. **Install Required Libraries**:
   - Navigate to the project directory and install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   If no `requirements.txt` file exists, manually install OpenCV and NumPy:
   ```bash
   pip install opencv-python numpy
   ```

3. **Camera Setup**:
   - Ensure that your system's camera is functional or connect an external camera for video feed.

## Usage
1. **Running the Application**:
   - Run the main script `object_measurement.py`:
   ```bash
   python object_measurement.py
   ```
   
   This will launch the real-time object measurement system.

2. **Measuring Objects**:
   - Place an object within the camera’s view. The system will detect the object and display the real-time measurements of its dimensions (height and width) on the screen.

3. **Calibration**:
   - For better accuracy, you can calibrate the camera using a reference object of known dimensions. Modify the `calibration.py` script to adjust parameters for your specific camera setup.

## Contributing
Contributions are welcome! If you would like to contribute, please fork the repository and submit a pull request with your changes. Ensure that your contributions align with the existing code style and project goals.

