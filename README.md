# Overview
This project is aimed at creating a Driver Monitoring System (DMS) capable of detecting faces of drivers and determining their gaze direction to enhance safety while driving.
It utilizes YOLOv8 for face detection and ResNet50, MobileNet V2, MobileNet V3 Small, SqueezeNet for eye gaze detection.

## Features
- Face detection using YOLOv8
- Eye gaze detection using ResNet50, MobileNet V2, MobileNet V3 Small, SqueezeNet
- Real-time monitoring of driver's face and eye movements
  
# Installation

### Prerequisites

- Python 3.x
- pip package manager

### Libraries Used

- **numpy**: NumPy can be installed using pip:

    ```bash
    pip install numpy
    ```

- **matplotlib**: Matplotlib can be installed using pip:

    ```bash
    pip install matplotlib
    ```

- **Pillow (PIL)**: Pillow can be installed using pip:

    ```bash
    pip install pillow
    ```

- **torch**: PyTorch installation depends on your system configuration. Please refer to the official [PyTorch website](https://pytorch.org/get-started/locally/) for installation instructions.

- **torchvision**: torchvision is typically installed along with PyTorch. If not, you can install it using pip:

    ```bash
    pip install torchvision
    ```

- **opencv-python (cv2)**: OpenCV can be installed using pip:

    ```bash
    pip install opencv-python
    ```

