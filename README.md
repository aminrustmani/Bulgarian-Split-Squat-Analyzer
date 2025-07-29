## Bulgarian Split Squat Analyzer – AI-Powered Feedback System

This is a Python-based AI fitness analyzer developed for a Fiverr client. It uses **MediaPipe** and **OpenCV** to analyze **Bulgarian Split Squats** from a video input, providing **real-time feedback**, **rep counting**, and **automated performance scoring**.

---

### 🔍 Features

* 🎥 **Analyzed Video Output**
  Generates a video with visual overlays for feedback and rep analysis.

* 🧠 **Real-Time Pose Detection**
  Uses **MediaPipe** to detect keypoints of the body for tracking squat posture.

* 🔢 **Smart Rep Counter**
  Detects and counts the total number of reps, distinguishing between good and bad ones.

* 📐 **Angle-Based Feedback System**
  Evaluates each rep based on:

  * Squat depth
  * Back lean
  * Knee collapse inward

* 📝 **Feedback Text Report**
  Outputs a `.txt` file summarizing:

  * Total reps performed
  * Form evaluation and rep score (1–10 scale)
  * Detailed per-rep feedback and suggestions

* 🔘 **Download Button Integration**
  Easily download the analyzed video and the generated feedback text file.

---

### 📁 Project Structure

```
📦 Bulgarian-Split-Squat-Analyzer/
├── input_video.mp4             # Your input workout video
├── squat_analyzer.py           # Main analysis script
├── analyzed_output.mp4         # Output video with overlay (generated)
├── feedback_report.txt         # Generated textual feedback (generated)
```

---

### 🛠️ Technologies Used

* Python
* MediaPipe
* OpenCV
* NumPy
* Real-Time Pose Estimation
* Angle-Based Heuristics

---

### 💡 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/bulgarian-squat-analyzer.git
   cd bulgarian-squat-analyzer
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Add your video file as `input_video.mp4`.

4. Run the analyzer:

   ```bash
   python squat_analyzer.py
   ```

5. Check the output video and feedback report.

---

### 🤝 Contribution

Pull requests and suggestions are welcome. For major changes, please open an issue first to discuss what you'd like to change.


