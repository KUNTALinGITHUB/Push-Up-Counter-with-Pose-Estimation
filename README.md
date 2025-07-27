
🏋️‍♂️ Push-Up Counter with Pose Estimation
A real-time push-up counter built using MediaPipe and OpenCV that detects human pose, calculates arm angles, and tracks push-up repetitions. The system overlays pose landmarks and saves the annotated video for review.

📽️ Demo
!Demo added
Real-time pose detection and push-up tracking in action.

🚀 Features
✅ Real-time pose detection using MediaPipe
📐 Arm angle calculation for push-up tracking
🔢 Push-up count and duration overlay
💾 Saves output video with annotations

🛠️ Technologies Used
Python 3.8+
OpenCV for video processing and visualization
MediaPipe for pose estimation
⚙️ How It Works
Pose Detection: Uses MediaPipe’s Pose model to detect 33 body landmarks.
Angle Calculation: Computes the angle between shoulder, elbow, and wrist to determine push-up position.
Push-Up Logic:
Down Position: Arm angle < 100°
Up Position: Arm angle > 150°
Transition from down to up counts as one push-up.
Overlay: Displays push-up count, arm angle, and duration on the video frame.
Video Output: Annotated frames are saved to pushup_output.mp4.

📦 Installation

📁 Usage
Replace the video path in the script:


Run the script:
python video_to_clip_maker.py

Output video will be saved as:

pushup_output.mp4
📂 File Structure
├── push_up_pose_detection_and_countion.py       # Main script
├── pushup_output.mp4       # Saved annotated video
├── pushup_input.mp4        # input video
└── README.md               # Project documentation
🙌 Acknowledgements
Thanks to my mentors and peers for their guidance and support throughout this project!

📬 Contact
Kuntal Pal
LinkedIn : https://www.linkedin.com/in/kuntal%20pal



https://github.com/user-attachments/assets/b95c2692-6a4c-4a17-83b1-15b947c806ca

