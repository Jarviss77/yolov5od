# yolov5od

## Overview

Welcome to the **yolov5od** repository! This project is a mini project for our 5th semester, aimed at creating an intelligent robot that integrates Natural Language Processing (NLP), Computer Vision, and Object Detection technologies. The robot is designed to identify and move towards objects in its surroundings based on voice commands.

## Project Description

**yolov5od** leverages state-of-the-art technologies to build a robot with the following capabilities:
- **Natural Language Processing (NLP)**: Enables the robot to understand and interpret voice commands.
- **Computer Vision**: Allows the robot to perceive its environment and detect objects using advanced vision techniques.
- **Object Detection**: Employs YOLOv5 (You Only Look Once version 5) for real-time object detection to identify and locate objects in the robot’s path.

The robot uses **NVIDIA's Jetson Nano** as the hardware platform, providing the computational power required for real-time processing of NLP and computer vision tasks.

The ultimate goal of this project is to create a robot that can interact with its environment in a meaningful way by combining these cutting-edge technologies. It will be able to:
- Receive and process voice commands.
- Detect and recognize objects in its surroundings.
- Move towards the detected objects based on the voice commands received.

## Features

- **Voice Command Processing**: Interprets spoken commands to guide the robot.
- **Real-time Object Detection**: Utilizes YOLOv5 for fast and accurate object detection.
- **Autonomous Navigation**: Moves towards identified objects in response to voice commands.
- **NVIDIA Jetson Nano**: The hardware platform providing the necessary computational resources for real-time processing.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/captainflatbelly/yolov5od.git
   cd yolov5od

## Getting Started

1. **Install Dependencies**:
   Install the required packages and libraries. You can use `pip` to install dependencies listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt

2. **Configure Your Environment**:
   Set up any necessary environment variables or configuration files. Refer to the `config/` directory for example configuration files.

3. **Set Up the NVIDIA Jetson Nano**:
   - Ensure that the Jetson Nano is properly set up with the necessary software and drivers.
   - Install dependencies specific to the Jetson Nano if any are required. Refer to the [Jetson Nano documentation](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit) for setup instructions.


## Contributing

We welcome contributions to this project! If you have ideas for improvements or find any issues, please open an issue or submit a pull request. 

## Acknowledgments

- **YOLOv5**: For real-time object detection.
- **NLP Libraries**: For natural language processing capabilities.
- **NVIDIA Jetson Nano**: For providing the computational power needed for the project.
- **Community Support**: For providing valuable resources and support.

---

Thank you for checking out **yolov5od**. We hope you find this project as exciting as we do!
