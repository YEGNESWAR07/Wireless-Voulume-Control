# Wireless-Voulume-Control
The Wireless Sound Control project is a Python-based implementation of various Digital Audio Effects (DAFX). The project focuses on manipulating audio signals to create unique listening experiences by applying effects such as delay-based effects, spatial effects, time-varying filters, modulators, and karaoke effects. The project also includes features like 3D spatialization, simulated surround sound, dialogue normalization, and dynamic range control.

The project is implemented using Python due to its extensive libraries and tools for audio signal processing. The code provided in the document demonstrates a wireless volume control system using hand gestures, which is achieved through the MediaPipe library for hand tracking and OpenCV for image processing. The volume is controlled based on the distance between two fingers (thumb and index finger) detected by the camera.

# Key Features:
Digital Audio Effects (DAFX):

Delay-based effects (e.g., chorus, flanger, vibrato).

Spatial effects (e.g., reverberation, panning, 3D effects using HRTF).

Time-varying filters (e.g., wah-wah).

Modulators (e.g., tremolo).

Karaoke effect using audio downmixing.

Dialogue Normalization and Dynamic Range Control:

Ensures consistent audio levels across different portions of the audio signal.

Wireless Volume Control:

Uses hand gestures to control the system volume.

# Libraries and Dependencies:

OpenCV: For image processing and video capture.

MediaPipe: For hand tracking and gesture recognition.

NumPy: For mathematical operations and interpolation.

pycaw: For controlling the system volume on Windows.

Other audio processing libraries: Such as librosa, pydub, or scipy for implementing audio effects.
Implemented using MediaPipe for hand tracking and OpenCV for image processing.

# Dependencies:
To run this code, you need to install the following Python libraries:

# bash
pip install opencv-python mediapipe numpy pycaw

## How to Run:
Save the code in a file named wirelessVolumeControl.py.

# Run the script using Python:
pip install opencv-python mediapipe numpy pycaw
# bash command to run the code
python wirelessVolumeControl.py

Use your hand gestures (thumb and index finger) to control the system volume.

Press q to exit the program.

## Notes:
This code is designed for Windows systems due to the use of pycaw.

Ensure that your camera is properly connected and accessible by OpenCV.

The volume control is based on the distance between the thumb and index finger, with a range of 50 to 300 pixels mapped to the system volume range.

# Audio Transcoding and Compression:

Supports .wav files and provides transcoding and compression options.

# Conclusion:
This project provides a comprehensive implementation of various digital audio effects and a wireless volume control system using hand gestures. The code is modular and can be extended to include more audio effects or improve existing ones. The GitHub repository should be well-documented to help users understand and use the project effectively.
