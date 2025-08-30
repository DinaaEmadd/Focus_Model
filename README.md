# 🎯 Focus Detection System using MediaPipe & OpenCV

This project is a **computer vision pipeline** for analyzing **human focus and attention** from videos.  
It leverages **MediaPipe Face Mesh**, **Eye Aspect Ratio (EAR)**, **Head Pose Estimation**, and **Gaze Tracking** to determine whether a person is focused or distracted while watching/working.

The system can be applied in:
- 📚 **E-learning platforms** → monitor students' attention  
- 🚗 **Driver monitoring systems** → detect drowsiness and distraction  
- 💻 **Productivity tools** → measure focus during work  

---

## 🛠 Key Features

- ✅ **Face Detection & Face Mesh** via MediaPipe  
- ✅ **Head Pose Estimation** (Pitch, Yaw, Roll) using `cv2.solvePnP`  
- ✅ **Eye Aspect Ratio (EAR)** → Detects blinks & closed eyes  
- ✅ **Iris Tracking & Gaze Direction** (Left, Right, Center)  
- ✅ **Focus Scoring System (0–100)** for every frame  
- ✅ **CSV Export** with timestamped focus scores  
- ✅ **Video Output** with bounding boxes, head pose, and focus labels  
- ✅ **Overall Focus Metric** → average score over full video  

---

## 📂 Project Structure

