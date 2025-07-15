# Red-Color-Recognition

✅ README.md for Red Color Tracking with OpenCV Project

# 🎯 Red Object Recognition and Tracking with OpenCV

This project records a video using your webcam, then processes that video to detect and highlight *red-colored objects*. It saves both the raw video and an animated GIF of the detection results.

---

## 📦 Features

- ✅ Record video using your webcam
- 🟥 Detect red objects using HSV color filtering
- 📦 Draw bounding boxes around red objects
- 📹 Save the recorded video as .mp4
- 🖼️ Save the detection result as an animated .gif
- 🐍 Built using Python, OpenCV, and ImageIO

---

## 📁 Folder Structure

red_recognition/
├── red_recognition.py         # Main script
├── output/
│   ├── recorded_video.mp4     # Raw webcam video
│   └── tracked_output.gif     # GIF showing red object detection

---

## 🧰 Requirements

- Python 3.10+
- Anaconda (recommended)
- OpenCV
- imageio
- numpy

---

## ⚙️ Setup Instructions (Anaconda)

bash
# 1. Navigate to the project folder
cd ~/Desktop/red_recognition

# 2. Create and activate a conda environment
conda create -n redtrack-env python=3.10 -y
conda activate redtrack-env

# 3. Install dependencies
pip install opencv-python imageio numpy


⸻

▶️ How to Run

# Make sure you're in the folder and conda environment
cd ~/Desktop/red_recognition
conda activate redtrack-env

# Run the Python script
python red_recognition.py

🎥 During Recording:
	•	A window will open showing the webcam feed.
	•	Move a red object in front of the camera.
	•	Press q to stop recording.

✅ After Processing:
	•	You’ll find recorded_video.mp4 and tracked_output.gif inside the output/ folder.

⸻

🧠 How It Works
	•	Captures a video from the webcam.
	•	Converts each frame to HSV color space.
	•	Filters out pixels in the red color range.
	•	Finds contours (shapes) in the red areas.
	•	Draws a bounding box around detected red objects.
	•	Saves annotated frames as a GIF.

⸻

📌 Future Ideas
	•	Detect other colors (green, blue, etc.)
	•	Add live tracking without saving video
	•	Save tracked video as .mp4
	•	Build a simple GUI for easier use

⸻

📄 License

This project is open-source and free to use under the MIT License.

---

### ✅ How to Use It on GitHub

1. Save this content into a file called `README.md` inside your project folder.
2. Push your project to GitHub:

bash
git init
git add .
git commit -m "Initial commit with red recognition script"
git remote add origin https://github.com/yourusername/red_recognition.git
git push -u origin main

	3.	When you open your repo on GitHub, the README will display automatically.

⸻
