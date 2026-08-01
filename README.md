# 🚗Vehicle Counter using OpenCV and YOLO

## 📌 Project Description
This project is a vehicle counter that uses OpenCV and YOLO for vehicle detection. It can detect and differentiate between various types of vehicles such as trucks, bicycles, cars, and buses. Each detected vehicle is assigned a unique tracker ID. The application also counts the total number of vehicles that pass through a specified region.

This project demonstrates the practical application of object detection, object tracking, and video analytics for intelligent traffic monitoring.
 ---

## ✨ Features

- 🚘 **Real-Time Vehicle Detection**
  - Detects vehicles from traffic videos using the YOLOv8 object detection model.

- 🎯 **Multi-Class Classification**
  - Recognizes multiple vehicle types including:
    - Car
    - Bus
    - Truck
    - Motorcycle
    - Bicycle

- 🆔 **Object Tracking**
  - Assigns a unique tracking ID to every detected vehicle.
  - Tracks vehicle movement across consecutive video frames.

- 🔢 **Vehicle Counting**
  - Counts vehicles when they cross a predefined virtual line.
  - Prevents duplicate counting using object tracking.

- 📹 **Live Visualization**
  - Displays bounding boxes, class labels, tracking IDs, and the total vehicle count in real time.

---
## 🛠️ Technologies Used

- Python
- OpenCV
- YOLOv8 (Ultralytics)
- NumPy
---
## 📂 Project Workflow

1. Read traffic video frames.
2. Detect vehicles using YOLOv8.
3. Filter vehicle classes.
4. Track detected vehicles with unique IDs.
5. Monitor vehicles crossing the counting line.
6. Update the vehicle count.
7. Display annotated video with live statistics.

---

## 🎯 Applications

- Smart Traffic Monitoring
- Traffic Flow Analysis
- Intelligent Transportation Systems (ITS)
- Vehicle Volume Analysis
- Urban Traffic Management

---

## 🚀 Future Enhancements

- Vehicle speed estimation
- Lane-wise vehicle counting
- Traffic congestion analysis
- Vehicle direction detection
- Web dashboard for live analytics
- Cloud deployment for remote monitoring

