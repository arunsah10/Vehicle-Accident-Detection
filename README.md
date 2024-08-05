
# Accident Detection System

## Overview

The Accident Detection System is an advanced application designed to enhance safety by detecting accidents in real-time using YOLOv8, a state-of-the-art object detection model. This system processes video feeds to identify accidents involving vehicles, leveraging computer vision techniques to provide accurate and timely alerts.

## Project Structure

- **Vehicle Dataset**: Contains the dataset and a Jupyter notebook file for training.
- **train_Results**: Contains the results of the training process.
- **best.pt**: The trained YOLOv8 model.
- **cr.mp4**: A sample video for testing the application.
- **img.py**: Script for converting videos into images for training.
- **main.py**: Script for running the model in a local environment.
- **app.py**: Flask application code for running the web app.

## Dependencies

To run this project, you need to install the following Python packages:

- Flask
- OpenCV
- Ultralytics (for YOLOv8)

You can install these dependencies using pip:

```bash
pip install flask opencv-python ultralytics
```

## Running the Web Application

1. **Start the Flask Application**:
   To run the web application, execute the following command:

   ```bash
   python app.py
   ```

2. **Access the Web Application**:
   Open your web browser and navigate to `http://127.0.0.1:5000`. You will see the web interface where you can upload videos or capture from a camera.

3. **Uploading and Capturing Videos**:
   - **Upload a Video**: Use the file upload option to upload a video for accident detection.
   - **Capture from Camera**: Use the camera option to stream live video for real-time detection.
   - **Stop Detection**: Click the "Stop" button to terminate the video processing.

## Application

The Accident Detection System offers several key features and applications:

- **Video to Image Conversion**: Converts video feeds into individual images for detailed analysis.
- **Training with YOLOv8**: Uses YOLOv8, a highly accurate object detection model, to detect vehicle accidents.
- **Custom Video Analysis**: Allows users to upload their own videos for accident detection.
- **Surveillance Camera Integration**: Interfaces with surveillance cameras for real-time monitoring and accident detection.

### Applications

- **Traffic Management**: Helps authorities manage traffic flow and respond quickly to accidents.
- **Safety Monitoring**: Enhances safety in high-risk areas by providing real-time alerts and analysis.
- **Data Collection**: Collects data for further analysis to improve road safety measures.

## Author

Arun Kumar Sah

## Copyright

&copy; 2024 Arun Kumar Sah. All rights reserved.

## GitHub Repository

For more information and to access the source code, visit our GitHub repository: [GitHub Repository](https://github.com/arunsah10/Vehicle-Accident-Detection)

