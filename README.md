# chest-scanner
# Webcam Image Classifier

This repository contains a simple Python application that uses OpenCV for webcam feed capture and TensorFlow/Keras for image classification. The application captures video from a webcam, processes each frame for object recognition, and displays the prediction results in real-time.

## Features

- Real-time webcam feed capture.
- Image resizing and preprocessing for model input.
- Object classification and confidence score prediction.

## Requirements

- Python 3.x
- TensorFlow/Keras
- OpenCV (`opencv-python` package)
- Pre-trained Keras model saved as `keras_Model.h5`
- Class labels saved in `labels.txt`

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

> Note: Ensure you have `keras_Model.h5` and `labels.txt` files in the repository directory.

## Usage

1. Run the script:

    ```bash
    python webcam_classifier.py
    ```

2. A new window will open displaying the webcam feed. As objects are shown to the camera, the application will classify and print the predictions along with confidence scores to the console.

3. Press the `ESC` key to exit the application.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See `LICENSE` for more details.
