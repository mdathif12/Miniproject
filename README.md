## Title of the Project
Real‑Time Hand Gesture Recognition System Using MediaPipe and Deep Learning
​

Small description
This project implements a real‑time hand gesture recognition pipeline using a webcam feed, MediaPipe hand‑landmark detection, and a trained deep‑learning classifier.
​
The system tracks keypoints of the user’s hand, extracts landmark coordinates, and classifies them into predefined gesture classes such as numbers or control commands.
​
OpenCV handles video capture and drawing of gesture overlays, providing immediate visual feedback to the user.
​
The model is trained on a curated hand‑gesture dataset, enabling robust recognition under varying backgrounds and lighting conditions.
​
Such a system can be extended for touchless HCI, sign‑language support, and gesture‑based control of applications or IoT devices.
​
## About
The Real‑Time Hand Gesture Recognition System is a computer‑vision project that detects and classifies human hand gestures from live webcam video to enable touch‑free interaction with digital systems. It uses MediaPipe to extract 3D hand landmarks from each frame, then feeds these coordinates into a trained deep‑learning classifier to recognize predefined gestures such as digits or control commands. OpenCV manages real‑time video capture, drawing of landmark points, and on‑screen gesture labels, so users get immediate visual feedback for each detected gesture. The project follows a full pipeline including data collection, preprocessing of landmark coordinates, model training, evaluation, and deployment in a real‑time application loop. This approach enables robust operation under common variations in background, lighting, and hand position, making it suitable for HCI, sign‑language support, and gesture‑based control of applications or IoT devices.
​
## Features
Real‑time hand landmark detection using MediaPipe Hands for accurate keypoint extraction from webcam video.
​

Deep‑learning based gesture classifier to recognize multiple predefined hand gestures (e.g., numbers or control commands).
​

Live video preview with overlaid landmarks and gesture labels using OpenCV for immediate visual feedback.
​

Robust performance under varying lighting conditions and backgrounds due to landmark‑based feature representation.
​

Modular code structure separating data collection, model training, and real‑time inference for easy extension.
​

Support for customizable gesture sets so new gestures can be added by collecting and retraining on additional samples.
​

Threshold‑based prediction filtering to reduce false positives and improve classification stability in continuous video.
​

Lightweight model that can run on standard laptops without dedicated GPU, enabling easy deployment in labs or classrooms.
​

Potential integration with external applications (e.g., media control, mouse/keyboard emulation, IoT control) via recognized gestures.
​

Open‑source GitHub repository structure with README, sample outputs, and configurable scripts for reproducible experimentation.
​

## Requirements
Python 3.8 or above installed on the system.
​

Required Python libraries: opencv-python, mediapipe, numpy, pandas, and a deep‑learning framework such as tensorflow or torch.
​

A standard webcam (built‑in or USB) for capturing real‑time video input.
​

Operating system: Windows, Linux, or macOS with basic command‑line support.
​

Sufficient CPU (dual‑core or higher) and at least 4 GB RAM for smooth real‑time processing.
​

Git installed to clone the repository from GitHub.
​

Optionally, a GPU with appropriate drivers and CUDA/cuDNN (if using TensorFlow/PyTorch) to accelerate model training and inference.
​

IDE or editor such as VS Code / PyCharm or Jupyter/Colab for editing and running the scripts.
​

A hand‑gesture dataset or the provided data‑collection script to record custom gesture samples for training.
​

Stable lighting and a relatively uncluttered background in the recording area to improve detection quality.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

<img width="1280" height="500" alt="image" src="https://github.com/user-attachments/assets/56781faa-3932-40e6-a5cc-8eccf503d9c1" />

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Task Completion Time Results
<img width="751" height="1039" alt="image" src="https://github.com/user-attachments/assets/0d3da9d2-2a33-49f4-a511-9eea0e8f02ea" />


#### Output2 -Learning Outcomes Results
<img width="940" height="768" alt="image" src="https://github.com/user-attachments/assets/beaf90ad-39a3-4b75-9552-13e2a38f0e6a" />



## Results and Impact

The proposed system achieves accurate real‑time recognition of multiple hand gestures from live webcam video, enabling reliable touch‑free interaction. By combining MediaPipe landmark extraction with a trained deep‑learning classifier, the model reaches high gesture‑level accuracy on the evaluation dataset while remaining lightweight enough for deployment on standard laptops. Real‑time visualization using OpenCV provides immediate on‑screen feedback, which improves user confidence and helps users quickly learn how to perform each gesture correctly. Compared with traditional mouse‑ or keyboard‑based control, the gesture interface offers a more natural and accessible modality, especially for scenarios where hands‑free operation is required. This has direct impact in domains such as assistive technologies, smart‑home control, and classroom demos where contactless interaction is preferred. The modular design of the project also allows students and researchers to extend the system with new gesture classes, improved models, or application integrations, making it a practical starting point for further innovation in human–computer interaction.

## Articles published / References


1. P. Martínez et al., “Hand Gesture Recognition Using MediaPipe Landmarks and Deep Learning Networks,” *Proceedings of VISIGRAPP 2025*, pp. 1–12. [web:183]

2. Google AI Edge, “Gesture Recognition Task Guide – MediaPipe Gesture Recognizer,” 2025. [web:184]

3. A. K. Sharma et al., “Hand Gesture Recognition Using MediaPipe and CNN,” *International Journal of Creative Research Thoughts (IJCRT)*, 2024. [web:185]

4. S. Biswas et al., “MediaPipe with LSTM Architecture for Real-Time Hand Gesture Recognition,” *CVIP Conference*, 2023. [web:188]

5. Amrutha D. et al., “Real Time Static and Dynamic Hand Gesture Recognition using CNN,” *International Journal of Engineering Research & Technology (IJERT)*, 2022. [web:189]

6. J. Xucong Zhang, “Gaze Estimation and Interaction in Real-World Environments,” PhD Thesis, MPI Informatics, 2017. [web:190]

7. Y. Zhang et al., “Real-Time Hand Gesture Monitoring Model Based on MediaPipe’s Hand Landmarks,” *Sensors*, vol. 24, 2024. [web:191]

8. R. K. Singh et al., “Real-Time Hand Gesture Recognition System Using CNN,” *IJCSP*, 2023. [web:192]

9. Google, “MediaPipe Hands: On-device Real-time Hand Tracking,” Developer Documentation, 2023. [web:194]

10. M. S. Khan et al., “Hand Gesture Recognition Using Convolutional Neural Networks,” *International Journal of Intelligent Systems and Applications in Engineering (IJISAE)*, 2024. [web:195]

