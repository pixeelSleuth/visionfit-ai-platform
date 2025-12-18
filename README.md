# 🦾 VisionFit AI
> **Real-Time Fitness & Nutrition Ecosystem using AI and Computer Vision.**

VisionFit AI is a smart fitness assistant designed to bridge the gap between workout performance and dietary management. By leveraging **MediaPipe** for pose estimation and **YOLOv5** for object detection, it provides a 360-degree health tracking experience.

---

## 📸 Project Preview

| AI Personalized Plan | Badges and Achievements |
| :---: | :---: |
| ![Plan](./UIPhotos/AI%20Personalized%20Plan.png) | ![Badges](./UIPhotos/Badges%20and%20Achivements.png) |

| Body Metrics Calculator | Macro Nutrient Calculator |
| :---: | :---: |
| ![Metrics](./UIPhotos/Body%20Metrics%20Calculator.png) | ![Macros](./UIPhotos/Macro%20nutrient%20calculator.png) |



---

## 🔥 Core Capabilities

### 🏋️ Computer Vision Gym Trainer
* **Live AI Tracer:** Real-time skeletal tracking using **MediaPipe**.
* **Posture Correction:** Instant feedback on form for 7 core exercises (Squats, Pushups, etc.).
* **Auto-Feedback:** Visual cues for "Good/Bad Posture" to prevent injury.

### 🥗 Smart Nutrition Assistant
* **Food Recognition:** Powered by a custom **YOLOv5** model to identify meals via live camera.
* **Nutritional Breakdown:** Automatically estimates food composition and calories.
* **Meal Planning:** Goal-oriented suggestions (Weight Loss, Muscle Gain, etc.).

### 📊 Health Data Management
* **Body Metrics:** Built-in BMI and BMR calculators.
* **Structured Storage:** Robust **MySQL integration** to store:
  * User Profiles & Fitness Plans
  * Daily Workout Logs
  * Nutritional History

---

## 🛠 Technical Architecture



**Software Stack:**
* **Language:** Python 3.x
* **Computer Vision:** OpenCV, MediaPipe, YOLOv5
* **Database:** MySQL (Relational DBMS)
* **GUI:** [Insert UI Tech: e.g. Tkinter / PyQt]

---

## 🚀 Installation & Setup

1. **Clone the Repo**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/VisionFit-AI.git](https://github.com/YOUR_USERNAME/VisionFit-AI.git)
   cd VisionFit-AI

Environment Setup

pip install -r requirements.txt
Database Configuration

Ensure MySQL is running.

Update your credentials in the config or main.py file.

Run the SQL scripts found in the /database folder.

Launch
python main.py

## 🎯 Use Cases
Home Workouts: Perfect for users without access to a personal trainer.

Diet Tracking: Simplifies calorie counting through visual recognition.

Progress Tracking: Maintains a long-term digital log of physical growth.