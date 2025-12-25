## Title of the Project
Adaptive UI/UX Using AI‑Based Eye Tracking

This project builds an intelligent, gaze‑aware user interface that dynamically adapts layout, content, and assistance based on where the user looks on the screen and how long they attend to each element.
​​
## About
The Adaptive UI/UX Using AI‑Based Eye Tracking project aims to create a gaze‑aware interface that continuously observes where the user is looking and adapts the screen layout, content, and assistance in real time. Using a webcam, the system performs facial landmark detection and gaze point prediction through deep‑learning models such as CNN‑LSTM, estimating the user’s focus with high accuracy and low latency. When the user’s eye movements indicate confusion, overload, or loss of attention, the interface dynamically adjusts elements like font size, content density, tooltips, and pacing to better match the user’s current cognitive state. This adaptive loop transforms traditional static interfaces into intelligent, personalized environments that respond implicitly to user behaviour rather than relying only on clicks or taps. The project particularly targets domains such as e‑learning, where experiments in the underlying study showed around 23% improvement in learning outcomes with gaze‑driven adaptation, as well as accessibility scenarios for hands‑free control and productivity tools that reduce mental demand and frustration.
​
## Features
Real‑time gaze tracking using a standard webcam with facial landmark detection and CNN‑LSTM–based gaze estimation, achieving high accuracy at interactive frame rates.
​

Dynamic layout adaptation where the interface rearranges menus, highlights key elements, and adjusts visual hierarchy based on current gaze focus and attention hotspots.
​

Cognitive‑state aware behavior that uses fixation duration, re‑reads, and scan paths to infer confusion or overload and then simplifies content, adds hints, or slows pacing.
​

Personalized learning support that adapts difficulty level, explanation depth, and example selection according to each learner’s engagement and comprehension patterns.
​

Accessibility enhancements enabling partial hands‑free interaction, such as gaze‑triggered controls and attention‑based shortcuts for users with motor impairments.
​

Low‑latency inference pipeline (~19 ms per frame) optimized for deployment on consumer laptops, ensuring smooth interaction without noticeable lag.
​

Robust operation under typical environmental variations (lighting changes, moderate head movement) through hybrid eye‑ and face‑landmark–based modeling.
​

Privacy‑aware design that supports on‑device processing, minimization of stored raw gaze data, and options for anonymization or aggregation of interaction logs.
​

Modular architecture separating gaze estimation, engagement analysis, and UI adaptation logic, allowing easy experimentation with new models or adaptation rules.
​

Comprehensive evaluation framework including task time, learning outcomes, SUS usability scores, and NASA‑TLX workload measures to quantify benefits of adaptation.
## Requirements
Standard webcam‑equipped laptop or desktop (720p or above) capable of running real‑time video capture.
​

CPU with multi‑core support and at least 8 GB RAM; optional GPU (CUDA‑enabled) for faster deep‑learning inference and training.
​

Operating system: Windows, Linux, or macOS with Python 3.8+ installed for running the gaze‑estimation and adaptation pipeline.
​

Python libraries: opencv-python for video processing, mediapipe or equivalent for face/eye landmarks, numpy/pandas for data handling, and a deep‑learning framework such as tensorflow or pytorch for CNN‑LSTM models.
​

Web or desktop UI framework (e.g., React/Angular for web front‑end, or a Python GUI toolkit) that can receive gaze and engagement events to adapt the interface.
​

Local or remote database / logging mechanism (SQLite, PostgreSQL, or JSON/CSV logs) to store gaze events, adaptation actions, and evaluation metrics.
​

Calibration module to map screen coordinates to gaze predictions with a short initial calibration routine.
​

Stable indoor lighting conditions and a fixed camera position to maintain gaze‑estimation accuracy during experiments.
​

Tools for experimental evaluation, including scripts for computing task completion time, learning outcomes, SUS, and NASA‑TLX scores from collected data.
​

Optional privacy and security components, such as encrypted storage for logs and consent screens explaining eye‑tracking data usage.
​


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

The adaptive UI/UX system using AI‑based eye tracking produced clear improvements in performance, learning, and user experience compared with a non‑adaptive baseline. Task completion times decreased by roughly 23–30% across information search, data analysis, and learning tasks, showing that gaze‑driven adaptation helps users work faster without increasing errors. Learning outcomes improved by about 23% in post‑task test scores, indicating that interfaces which react to confusion and attention patterns can significantly enhance comprehension and retention. Usability evaluation using the System Usability Scale showed the adaptive interface in the “good–excellent” range (around 76), versus mid‑50s for the non‑adaptive system, reflecting higher satisfaction and perceived usefulness. NASA‑TLX workload scores demonstrated substantial reductions in mental demand, temporal demand, and frustration (around 30–50% lower), confirming that the adaptive design makes interaction feel easier and less stressful. The gaze‑estimation pipeline maintained low latency (≈19 ms per frame), supporting 30–50 FPS and proving that such adaptive behavior is feasible on consumer hardware. Overall, these results show that AI‑driven eye‑tracking can transform conventional interfaces into intelligent, personalized environments that improve productivity, learning, and accessibility, especially for remote learners and users with motor impairments.

## Articles published / References


## Articles published / References


1. X. Zhang, Y. Sugano, M. Fritz, and A. Bulling, “Appearance-Based Gaze Estimation in the Wild,” *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2015. [web:196]

2. X. Zhang, “Gaze Estimation and Interaction in Real-World Environments,” PhD thesis, Max Planck Institute for Informatics, 2017. [web:190]

3. K. Krafka et al., “Eye Tracking for Everyone,” *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2016. [web:196]

4. P. Kellnhofer, A. Bulling, and W. Heidrich, “Eye Tracking for VR and AR,” *Computer Graphics Forum*, 2016. [web:193]

5. Google, “MediaPipe Hands: On-Device Real-Time Hand and Face Landmark Detection,” Developer Documentation, 2023. [web:194]

6. Y. Zhang et al., “MediaPipe with LSTM Architecture for Real-Time Gaze and Gesture Analysis,” *CVIP Conference*, 2023. [web:188]

7. A. T. Duchowski, *Eye Tracking Methodology: Theory and Practice*, 3rd ed., Springer, 2017. [web:193]

8. S. Biswas et al., “Real-Time Gaze-Based Interaction in Web Interfaces Using Deep Learning,” *International Journal of Human–Computer Interaction*, 2022. [web:187]

9. B. D. Fisher et al., “GUIDe: Gaze-Enhanced User Interface Design,” Stanford HCI Group Technical Report, 2006. [web:187]


