# Hand-Gesture Controlled Presentation System

This project implements a gesture-controlled presentation system using computer vision and hand tracking. Users can navigate through slides and annotate them using hand gestures captured by a webcam.

## Targeted Audience

This project is targeted especially towards differently abled people around the world:

- **Mobility Impairments**: People with limited use of their hands or arms, such as those with cerebral palsy or spinal cord injuries.
- **Repetitive Strain Injuries (RSI)**: Individuals with conditions like carpal tunnel syndrome, reducing the need for repetitive motions.
- **Amputees**: People who have lost limbs and find it challenging to use standard input devices.
- **Muscle Weakness**: Individuals with conditions like muscular dystrophy, benefiting from easier hand gestures.
- **Parkinson’s Disease**: People with Parkinson's disease who experience tremors or difficulty with fine motor control.

## Features

- Navigate through presentation slides using hand gestures
- Draw annotations on slides in real-time
- Erase annotations
- Display webcam feed alongside the presentation

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- cvzone
- NumPy

## Installation

1. Clone this repository or download the source code.
2. Install the required packages.

## Usage

1. Place your presentation images in a folder named "Presentation" in the same directory as the script.
2. Run the script:
3. Use the following hand gestures to control the presentation:
- Thumb up: Go to previous slide
- Pinky up: Go to next slide
- Index and middle fingers up: Hover mode
- Index finger up: Draw annotations
- Index, middle, and ring fingers up: Erase last annotation
4. Press 'q' to quit the application.

## Customization

You can adjust the following parameters in the script:

- `width` and `height`: Camera resolution
- `gestureThreshold`: Y-coordinate threshold for gesture detection
- `folderPath`: Path to the folder containing presentation images
- `delay`: Delay between gesture recognitions


## Acknowledgments

This project uses the HandTrackingModule from the cvzone library.