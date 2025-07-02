#  Real-Time Object Detection via Webcam

A real-time object detection web application that uses your device's webcam to detect and identify objects using a pre-trained deep learning model.

##  Features

-  Live video stream from your webcam
-  Real-time object detection using YOLO 
-  Displays object labels and confidence scores
-  Fast and responsive UI

## Technologies Used

- HTML5, CSS3, JavaScript
- YOLOv8  
- OpenCV 
- Flask 

##  How to Use

### Frontend-Only 
1. Clone the repository.
2. Open `index.html` in a modern browser.
3. Click **Start Camera** and allow webcam access.
4. The app will detect and label objects in real time.

### Backend-Powered (YOLO with Flask )
1. Set up a Python virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  
   pip install -r requirements.txt
2. Run the server:
 -python app.py

3. Open the provided localhost URL in your browser.
