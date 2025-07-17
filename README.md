# Infosys-Springboard


# AI-Driven-Footfall-Analytics

A Computer Vision based solution designed to detect, count, and analyze footfall (number of people) in a retail store using surveillance video streams. This project leverages deep learning models to help businesses optimize their space usage, staffing, and marketing strategies by understanding customer traffic patterns.

## 🧠 Project Objective

To develop an AI-powered system that:
- Accurately detects people in real-time using CCTV footage.
- Counts footfall data efficiently.
- Provides analytics for better retail decision-making.

---

## 🚀 Features

- ✅ Real-time person detection using YOLO/SSD/MobileNet models.
- ✅ Automatic footfall counting logic with region of interest (ROI) tracking.
- ✅ Visual representation using bounding boxes and counters.
- ✅ Graph-based analysis for time-based traffic trends.
- ✅ Lightweight and scalable for real-world retail deployment.

---

## 📂 Project Structure

AI-Driven-Footfall-Analytics/
│
├── models/ # Pre-trained models and config files
├── data/ # Sample video clips for testing
├── utils/ # Utility scripts for tracking, drawing, etc.
├── output/ # Processed videos and analytics reports
├── app.py # Main execution script
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## ⚙️ Tech Stack

- Python
- OpenCV
- NumPy
- Deep Learning (YOLOv5 / SSD / MobileNet)
- Matplotlib / Plotly (for analytics visualization)

---

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/AI-Driven-Footfall-Analytics.git
cd AI-Driven-Footfall-Analytics

2. **Create virtual environment** (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

2. **Install dependencies**
pip install -r requirements.txt

▶️ How to Run
Place your input video in the data/ folder.

Run the application:

python app.py --video data/sample_video.mp4
Output with footfall count will be saved to the output/ directory.

📊 Output
Video with people detected and counted in real-time.

Summary of footfall count.

Optional: Time-based traffic heatmaps or graphs (if enabled).

🧪 Future Enhancements
Multi-camera integration for large store coverage.

Gender/age-based demographics estimation.

Heatmap visualization of movement patterns.

Integration with dashboards for real-time monitoring.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss.

