# 🚗 Vehicle Detection, Classification & Counting using YOLOv8

This project implements a computer vision system that automatically detects, classifies, and counts vehicles in traffic images using **YOLOv8**. The system processes static images, identifies **cars**, **trucks**, and **motorcycles**, and saves annotated outputs with bounding boxes and confidence scores.

---

## 📌 Features

- ✅ Vehicle detection using **YOLOv8 (Ultralytics)**
- ✅ Classification into **cars**, **trucks**, and **motorcycles**
- ✅ Confidence score display for each detection
- ✅ Bounding box annotation on images
- ✅ Category-wise vehicle counting
- ✅ Results saved as annotated images

---

## 🛠️ Technology Stack

- **Language:** Python 3.8+
- **Libraries:** OpenCV, NumPy, Matplotlib
- **Model Framework:** YOLOv8 (via `ultralytics` package)
- **Development Environment:** Jupyter Notebook / Python script

---

## 📁 Project Structure

```
traffic-detection-assignment/
├── README.md
├── requirements.txt
├── main.py
├── detector.py
├── utils.py
├── data/
│   └── test_images/             # Input traffic images
├── output/
│   └── processed_images/        # Annotated results
└── docs/
    ├── technical_report.pdf
    └── presentation_slides.pdf
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/traffic-detection-assignment.git
cd traffic-detection-assignment
```

### 2. Install Dependencies

Install all required libraries using:

```bash
pip install -r requirements.txt
```

### 3. Run the Code

You can run the detection script using:

```bash
python main.py
```

Or run it step-by-step inside the provided Jupyter Notebook.

---

## 📂 Input and Output

- **Input:** 10 images located in `/data/test_images/`
- **Output:** Annotated images with bounding boxes saved in `/output/processed_images/`

Each output image includes:
- Bounding boxes with labels (e.g., "Car: 0.87")
- Summary of vehicle counts per image

---

## 📊 Results Summary

- **Detection Accuracy:** ~90%
- **Avg. Inference Time:** < 1 second per image
- **Total Vehicles Detected:**  
  - Cars: 20  
  - Trucks: 5  
  - Motorcycles: 4

---

## ✅ Success Criteria

- [x] Detected at least 75% of clearly visible vehicles
- [x] Correctly classified vehicles into categories
- [x] Clean, readable output and code
- [x] Annotated images and confidence scores generated

---

## 🔮 Future Improvements

- Real-time video stream support (e.g., webcam, CCTV)
- Web-based upload interface using Flask or Streamlit
- Model fine-tuning with custom traffic datasets
- Performance optimization with YOLOv8m/l models

---

## 👩‍💻 Author

**Khushi Jaiswal**  
B.Tech AI Engineering – 6th Semester  
Email: khushi@example.com

---

## 📄 License

This project is for academic and learning purposes only.
