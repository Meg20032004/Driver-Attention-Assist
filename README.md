# Driver Attention Assist

Driver Attention Assist is an advanced system designed to enhance road safety by monitoring and analyzing a driver's attention levels in real-time. Using a combination of computer vision, machine learning, and sensor data, this project aims to detect signs of driver fatigue, distraction, and drowsiness, providing timely alerts to prevent potential accidents.

## Features

- **Real-Time Monitoring**: Continuously tracks the driver's face and eye movements using a webcam or an in-car camera.
- **Attention Detection**: Uses advanced algorithms to analyze facial expressions and detect signs of fatigue, drowsiness, and distraction.
- **Alert System**: Provides auditory and visual alerts when decreased attention or drowsiness is detected, helping to keep the driver focused.
- **Data Logging**: Records attention levels and alert instances for further analysis and improvement of the system.
- **User-Friendly Interface**: Simple and intuitive interface for easy setup and monitoring.

## Technologies Used

- **Python**: The core programming language used for developing the system.
- **OpenCV**: For real-time computer vision tasks, including face and eye detection.
- **Dlib**: For facial landmark detection and tracking.
- **TensorFlow/Keras**: For building and training the attention detection model.
- **Flask**: For creating a web-based interface for monitoring and alerts.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/driver-attention-assist.git
   cd driver-attention-assist
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the application:
   ```sh
   python app.py
   ```

## Usage

1. Connect a webcam to your computer or use the in-car camera.
2. Start the application by running the `app.py` script.
3. The system will begin monitoring the driver's attention levels in real-time.
4. If decreased attention or drowsiness is detected, the system will issue alerts to help keep the driver focused.

## Acknowledgements

- OpenCV and Dlib for the computer vision functionalities.
- TensorFlow and Keras for the machine learning components.
- Flask for the web interface.
