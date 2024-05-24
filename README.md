# Virtual Mouse

Virtual Mouse is a Python-based project that enables controlling your computer's cursor and performing mouse actions using hand gestures captured through your webcam. This project utilizes computer vision techniques to detect hand gestures and translate them into corresponding mouse movements and clicks.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **Gesture Recognition:** Detects hand gestures such as open palm, fist, index finger, mid finger, and V gesture.
- **Mouse Control:** Translates hand gestures into cursor movements and mouse clicks.
- **Multi-Hand Support:** Supports detection and control for multiple hands simultaneously.
- **Dynamic Cursor Speed:** Adjusts cursor speed based on hand movement intensity.
- **Intuitive Interface:** Easy-to-understand gestures for mouse actions, enhancing user experience.

## Installation

To use Virtual Mouse, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/An1rud/Virtual-mouse.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the `virtualmouse.py` script.
   ```bash
   python virtualmouse.py
   ```

2. Position your hand in front of your webcam.
3. Perform gestures according to the defined controls:
   - Open Palm: Move the cursor.
   - Fist: Click and hold.
   - Index Finger: Left-click.
   - Mid Finger: Right-click.
   - V Gesture: Double-click.


Feel free to customize this template as per your project's specific details and requirements. If you have any questions or need further assistance, don't hesitate to ask!
