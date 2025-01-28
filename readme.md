


# Face Recognition System

This project implements a face recognition system using OpenCV and Tkinter. It provides a graphical user interface (GUI) for training a dataset of facial images and saving the trained model for future recognition tasks.

## Features

- Train a dataset of facial images.
- Save the trained model as an XML file.
- User-friendly GUI for easy interaction.

## Requirements

- Python 3.x
- OpenCV
- Tkinter
- PIL (Pillow)
- NumPy
- MySQL Connector

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sriram-Merugu/Face-Detection.git
   cd face-recognition-system
   ```

2. Install the required packages:

   ```bash
   pip install opencv-python-headless pillow numpy mysql-connector-python
   ```

## Usage

1. Prepare your dataset by placing facial images in the `data` directory. Each image should be named with the format `user.id.jpg`, where `id` is a unique identifier for each person.

2. Run the main application:

   ```bash
   python main.py
   ```

3. Use the GUI to train the dataset by clicking the "TRAIN DATA" button. The trained model will be saved as `classifier.xml`.

## Code Overview

- **main.py**: Contains the main application logic, including the GUI setup and training process.
- **data/**: Directory where the facial images are stored for training.
