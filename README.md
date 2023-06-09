# Posture Monitoring System

This project is a real-time posture monitoring system using computer vision techniques. It uses the webcam of a computer to analyze the user's posture and provide feedback on their sitting position. The system detects and tracks the user's face and shoulders, calculates the relative distance between them, and analyzes various angles and ratios to determine the posture quality.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/posture-monitoring-system.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Run the `slouch.py` script: `python slouch.py`
2. The system will access the webcam and start capturing the video feed.
3. The detected face and shoulder landmarks will be highlighted on the video stream.
4. The system will analyze the posture based on various criteria, such as relative distance, shoulder angle, face angle, and more.
5. If the system detects poor posture, it will provide real-time notifications to the user.

## Features

- Real-time posture monitoring using computer vision techniques
- Detection and tracking of facial landmarks
- Calculation of relative distance between face and shoulders
- Analysis of shoulder angles and face angles
- Real-time notifications for poor posture

## Roadmap

This project has the following planned enhancements:

- Calibrating the system for each user to improve accuracy and personalization
- Environmental calibration to handle variations in lighting, background, and other factors
- Progress tracking over time to provide insights and improvements for the user
- Tracking and analysis of common mistakes made by the user to target specific areas of improvement
- Integration with smartwatches for convenient posture notifications
- Collecting data to establish average sitting postures for different individuals and settings

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.
