# AI-League
This repo for AI-League contribution in KSA
# إحياء الحواس باستخدام الذكاء الاصطناعي

## Project Overview
This project integrates advanced AI techniques to analyze EEG signals and sports video footage, providing tailored interactive outputs for spectators with special needs. By combining deep learning models (such as LSTM for EEG analysis and YOLOv7 for video analysis), the system delivers dynamic visual indicators and spatial audio cues to enhance the overall spectator experience.

## Key Features
- **Real-time EEG Analysis:** Classifies emotional states to adjust outputs dynamically.
- **Video Event Detection:** Utilizes YOLOv7 to detect key events (ball, players, etc.) on the field.
- **Deaf Mode:** Displays a continuously moving visual arrow that indicates the direction of events.
- **Blind Mode:** Converts standard audio commentary into spatial audio cues that guide the user.
- **Fusion of Data:** Merges the outputs from EEG and video analysis to provide an integrated interactive experience.

## How It Works
1. EEG signals are processed and classified using an LSTM-based model.
2. Sports videos are analyzed in real-time using YOLOv7 to detect events.
3. For Deaf users, a visual indicator (arrow) is shown on a dynamic chart.
4. For Blind users, a spatial audio effect converts commentary into directional sound.
5. The system continuously merges these inputs to deliver an intuitive, responsive output.

## Getting Started
- **Prerequisites:** Python 3.x, Git, and necessary libraries as listed in the requirements file.
- **Installation:** Clone this repository and install the dependencies with `pip install -r requirements.txt`.
- **Usage:** Run the main script `sensory_sports.py` to see the demo in action.

## Contact
For any inquiries, please contact: [abdelazizeabdullahelsouday@gmail.com]
