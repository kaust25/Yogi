# YOGI: Yoga Pose Recognition with OpenCV and Mediapipe

YOGI is a Python project that uses computer vision techniques to recognize and classify yoga poses in real-time using a webcam. It utilizes the OpenCV library for capturing and processing video frames and the Mediapipe library for pose estimation. This project demonstrates how computer vision can be applied to enhance yoga practice by providing real-time feedback and guidance on the correctness of yoga poses.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- OpenCV
- Mediapipe
- Numpy
- pyttsx3

You can install these dependencies using pip:

```
pip install opencv-python mediapipe numpy pyttsx3
```

## How it works

1. The project uses the webcam to capture video frames.
2. It applies pose estimation using the Mediapipe library to detect key landmarks on the human body.
3. The detected landmarks are used to calculate angles between joints, which are then used to classify the yoga pose being performed.
4. The recognized pose is displayed on the screen in real-time, and an audio output is provided to announce the name of the pose.

## Supported Yoga Poses

The YOGI project currently supports the following yoga poses:

- Warrior II Pose
- Warrior I Pose
- T Pose
- Tree Pose
- Downward Dog Pose
- Cobra Pose
- Mountain Pose
- Child's Pose
- Bridge Pose
- Triangle Pose
- Plank Pose
- Uttanasana
- Reverse Warrior
- Garland Pose
- Downward facing dog split
- Staff Pose
- Sukasana
- Cobbler's Pose
- Seated forward bend
- Upavistha Konasana
- Happy Baby Pose

## How to use

1. Make sure you have a webcam connected to your computer.
2. Run the `yogi.py` script.
3. A window will open showing the webcam feed and the recognized yoga pose.
4. Try performing different yoga poses in front of the camera, and the system will provide real-time feedback on the recognized pose.

## Customization

You can customize this project by adding more yoga poses or modifying the existing pose recognition logic. The `calculate_angle` function can be updated to detect different angles specific to your desired poses. Additionally, you can modify the labels and audio announcements in the `labels` dictionary to match your custom poses.

## Contributions

Contributions to this project are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request on the project's GitHub repository.

## Acknowledgments

This project was made possible by the following libraries:

- OpenCV: https://opencv.org/
- Mediapipe: https://mediapipe.dev/
- Numpy: https://numpy.org/
- pyttsx3: https://pypi.org/project/pyttsx3/

Special thanks to the developers and contributors of these libraries for their valuable contributions to the open-source community.

## Contact

For any inquiries or feedback, you can reach me at kausthubalaji@gmail.com

Happy yoga practice with YOGI!
