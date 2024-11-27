The content in the uploaded file closely matches your request. Here's a creative reimagining of it with enhanced clarity, engagement, and formatting for better presentation:

---

# 🎾 Tennis Player and Ball Detection with YOLOv5 and Streamlit 🚀

Harness the power of machine learning to detect tennis balls and players in real time! This project features an interactive Streamlit app, leveraging a custom-trained YOLOv5 model to process videos effortlessly.

🌐 **[Live Application](https://tennis-tracking-app-using-yolov5-da2ja3dfki3km75pou97iy.streamlit.app/)**  

---

## 🌟 Features

- **Seamless Video Uploads:** Upload `.mp4` videos for detection.
- **Real-Time Feedback:** Monitor progress with a dynamic progress bar.
- **Enhanced Output:** View videos with highlighted tennis balls and players.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone <repository-url>
cd yolov5
```

### 2️⃣ Install Dependencies

Ensure Python is installed. Then, run:

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the Model

Place your trained YOLOv5 model weights (`best.pt`) in the directory:

```
yolov5/runs/exp/weights/best.pt
```

### 4️⃣ Launch the Application

Run the following command to start the Streamlit app:

```bash
streamlit run app.py
```

---

## 🗂️ Project Structure

```plaintext
yolov5/
├── app.py                  # Streamlit application
├── runs/
│   └── exp/
│       └── weights/
│           └── best.pt     # YOLOv5 model weights
├── data/                   # Video input directory
└── requirements.txt        # Dependency file
```

---

## 🛠️ How to Use

1. Launch the Streamlit app (local or live).
2. Upload a video in `.mp4` format.
3. Watch the detection progress bar update in real time.
4. Once processing is complete, download or view the video with highlights.

---

## 🎥 Example Use Case

Upload a tennis match video to:

- Detect player movements across the court.
- Track tennis ball trajectories in real-time.

---

## 📦 Dependencies

- **Streamlit**: Interactive UI
- **PyTorch**: YOLOv5 model inference
- **OpenCV**: Video processing
- **YOLOv5**: Object detection engine

---
