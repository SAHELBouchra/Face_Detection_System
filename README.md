# Face_Recognition_System

This project demonstrates a simple **face recognition system** using Python. It detects and recognizes a known face (e.g., *Lionel Messi*) from a webcam feed in real time and compares it against unknown faces.

## ⚙️ Requirements

Make sure you have **Python 3.8+** installed.

Then install the following dependencies:

```bash
pip install opencv-python
pip install numpy
pip install face_recognition
```

> ⚠️ **Note:**  
> The `face_recognition` library requires `dlib`.  
> On some systems, you may need to install CMake and Visual Studio Build Tools (on Windows) or `cmake`, `boost`, and `python3-dev` (on Linux/macOS) before installing.

Example (Ubuntu):
```bash
sudo apt install cmake g++ python3-dev
pip install face_recognition
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Face_Detection.git
   cd Face_Detection
   ```

2. Place your known and unknown images in the appropriate folders:
   - `messi.jpg`

3. Open and run the notebook:
   ```bash
   jupyter notebook Face_detection.ipynb
   ```

4. Allow camera access when prompted. The notebook will:
   - Load the known face (Messi)
   - Capture live video from your webcam
   - Detect and label any recognized faces in real-time

---

## 🧩 Libraries Used

| Library | Purpose |
|----------|----------|
| **OpenCV (cv2)** | Access webcam and handle video frames |
| **NumPy** | Array manipulation and image processing |
| **face_recognition** | Facial encoding, comparison, and recognition |

---

## 🖼️ Example Output

- **Known Face (Messi):** Detected and labeled correctly.
<img width="300" height="380" alt="Known" src="https://github.com/user-attachments/assets/ca2bb52b-f4cc-4b80-8866-e2b42b4467b6" />

- **Unknown Face:** Shown as "Unknown" in the video feed.
<img width="300" height="380" alt="unknown" src="https://github.com/user-attachments/assets/917b1546-a343-466a-b630-b0905705948d" />



---

## 💡 Future Improvements
- Add multiple known faces.  
- Use Haar cascades or deep learning models for emotion detection.  
- Deploy as a standalone app using Streamlit or Flask.
