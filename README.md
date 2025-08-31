# Car-license-plate-detection

![0a720df9-e4ef-4e44-8c13-b39b9be8444d___3e7fd381-0ae5-4421-8a70-279ee0ec1c61_Nissan-Terrano-6_jpg rf c2f78cb12de23cda1b1782f23ee505b0](https://github.com/user-attachments/assets/11ce55d1-3ffc-4297-b0d6-de9efe10e2aa)

![1f0a7fe8-ac9b-4b54-9d55-e11f34f9f98b___9f6521b2ddb7b8e40ffd510966ffcca3-jpg_jpeg rf b78119b0e27903388dcc97863f9a3a3f](https://github.com/user-attachments/assets/aa19385e-057e-4d02-aad3-318ea3c98804)


A computer vision project that detects and localizes car license plates from images and video streams using YOLOv8 (by Ultralytics). The project is implemented in Python with OpenCV and developed in Visual Studio Code (VS Code).

📌 Features

🔍 Real-time License Plate Detection using YOLOv8.

🎥 Works with images, video files, and live webcam streams.

⚡ High accuracy & speed with Ultralytics YOLOv8 models.

🖼 Bounding boxes with confidence scores drawn on detected plates.

🛠 Easily extendable for OCR (Optical Character Recognition) to extract plate numbers.

🏗️ Tech Stack

Python

YOLOv8 (Ultralytics)

OpenCV

NumPy

VS Code


Car-License-Plate-Detection/
│-- data/                # Dataset (images/videos for training/testing)
│-- runs/                # YOLOv8 training & detection results
│-- models/              # Pre-trained YOLOv8 models (if any)
│-- detect.py            # Script for detection
│-- train.py             # Script for training (if applied)
│-- requirements.txt     # Dependencies
│-- README.md            # Project documentation


⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/Car-License-Plate-Detection.git
cd Car-License-Plate-Detection


2️⃣ Create a virtual environment & install dependencies

pip install -r requirements.txt


3️⃣ Install Ultralytics (YOLOv8)

pip install ultralytics


4️⃣ Verify installation

yolo help

🚀 Usage
🔹 Run Detection on Image
yolo predict model=yolov8n.pt source="car.jpg"

🔹 Run Detection on Video
yolo predict model=yolov8n.pt source="traffic.mp4"

🔹 Run Detection on Webcam
yolo predict model=yolov8n.pt source=0


(Replace yolov8n.pt with your custom-trained model if available.)

📊 Training (Optional)

If you trained your own dataset for license plates:

yolo train model=yolov8n.pt data=plate.yaml epochs=50 imgsz=640

📸 Results

Example of license plate detection:

🔮 Future Improvements

✅ Add OCR (EasyOCR/Tesseract) to extract license numbers.

✅ Improve accuracy with a custom-trained YOLOv8 model on regional datasets.

✅ Deploy as a web app (Flask/Streamlit).

🏅 Author

👤 Sumit Gupta

🎓 B.Tech (IT), Bhagwan Parshuram Institute of Technology

🔬 Experience in Computer Vision, Machine Learning, and Web Development

🌐 GitHub
 | LinkedIn

👉 This project demonstrates how AI + Computer Vision can be applied to smart traffic systems, surveillance, and law enforcement automation.
