# 🧠 ADAS Sensors

## 📘 Overview
Sensors are the **core components of Advanced Driver Assistance Systems (ADAS)**.  
They continuously monitor the surroundings of the vehicle, collect real-time data, and send it to the **Electronic Control Unit (ECU)** for processing.  
The ECU then makes intelligent driving decisions such as braking, steering, or alerting the driver.

---

## ⚙️ Types of ADAS Sensors

### 1️⃣ Camera Sensors
**📍 Description:**  
Camera sensors are the “eyes” of an ADAS system.  
They capture real-time images and video frames from the vehicle’s surroundings.

**🧩 Working Principle:**  
- Uses **CMOS or CCD image sensors**.  
- Captured frames are processed using **computer vision** and **deep learning** algorithms.  
- The processed data helps identify lanes, vehicles, pedestrians, and traffic signs.

**🚘 Applications:**  
- Lane Departure Warning (LDW)  
- Traffic Sign Recognition (TSR)  
- Pedestrian Detection  
- Object and Vehicle Recognition  

**🧠 Technology:**  
- CNN (Convolutional Neural Networks)  
- OpenCV and YOLO for image processing and detection  

---

### 2️⃣ Radar Sensors
**📍 Description:**  
Radar (Radio Detection and Ranging) sensors use **radio waves** to detect the distance, speed, and direction of objects around the vehicle.

**🧩 Working Principle:**  
- Transmit radio signals that reflect off objects.  
- Measures time delay and frequency shift to calculate **distance and velocity**.

**🚘 Applications:**  
- Adaptive Cruise Control (ACC)  
- Forward Collision Warning (FCW)  
- Blind Spot Detection (BSD)  
- Rear Cross Traffic Alert (RCTA)  

**🧠 Technology:**  
- Uses **millimeter-wave radar** (24GHz, 77GHz)  
- Reliable in poor weather and lighting conditions  

---

### 3️⃣ LiDAR Sensors
**📍 Description:**  
LiDAR (Light Detection and Ranging) creates a **3D map of the environment** by emitting laser beams.

**🧩 Working Principle:**  
- Emits laser pulses and measures the time it takes for them to reflect back.  
- Creates a 3D “point cloud” for precise object positioning.

**🚘 Applications:**  
- Autonomous Navigation  
- Obstacle and Pedestrian Detection  
- 3D Mapping and Localization  

**🧠 Technology:**  
- Spinning or Solid-State LiDAR  
- High accuracy but expensive  

---

### 4️⃣ Ultrasonic Sensors
**📍 Description:**  
Ultrasonic sensors use **sound waves** to detect close-range objects.  
They are mainly used in low-speed and parking scenarios.

**🧩 Working Principle:**  
- Emit ultrasonic waves and measure the echo time to determine object distance.  
- Effective up to a few meters.

**🚘 Applications:**  
- Parking Assist  
- Reverse Assist  
- Blind Spot Detection  

**🧠 Technology:**  
- Low-cost and short-range detection  
- Not affected by lighting conditions  

---

### 5️⃣ Infrared (Thermal) Cameras
**📍 Description:**  
Infrared cameras detect **heat signatures** instead of visible light.  
They are extremely useful in **night-time or low-visibility** conditions.

**🧩 Working Principle:**  
- Detects infrared radiation emitted by objects.  
- Converts thermal energy into digital images.

**🚘 Applications:**  
- Night Vision Systems  
- Pedestrian and Animal Detection in Darkness  

**🧠 Technology:**  
- Thermal Imaging Sensors (LWIR or MWIR)  
- Works even in fog, smoke, and low-light environments  

---

### 6️⃣ GPS & IMU (Inertial Measurement Unit)
**📍 Description:**  
GPS provides **global position**, while the IMU provides **motion and orientation** information.  
Combined, they help in **vehicle localization and navigation**.

**🧩 Working Principle:**  
- GPS determines position via satellite signals.  
- IMU measures **acceleration**, **angular velocity**, and **orientation** using accelerometers and gyroscopes.  

**🚘 Applications:**  
- Path Planning and Localization  
- Autonomous Navigation  
- Stability Control Systems  

**🧠 Technology:**  
- Sensor Fusion of GPS + IMU + Vision  
- High accuracy with Kalman Filters  

---

## ⚡ Sensor Fusion
ADAS combines data from multiple sensors (Camera + Radar + LiDAR + IMU) to create a **comprehensive 360° understanding** of the vehicle’s surroundings.  
This process is called **Sensor Fusion**, which improves accuracy and reliability in decision-making.

---

## 🧩 Summary Table

| Sensor Type | Range | Weather Resistance | Typical Use |
|--------------|--------|--------------------|--------------|
| **Camera** | Medium | Low | Lane & Object Detection |
| **Radar** | Long | High | Distance & Speed Detection |
| **LiDAR** | Medium–Long | Medium | 3D Mapping, Obstacle Detection |
| **Ultrasonic** | Short | High | Parking & Close Objects |
| **Infrared (Thermal)** | Medium | High | Night Vision, Pedestrian Detection |
| **GPS & IMU** | Global | High | Localization & Navigation |

---

## 🧠 Technologies Used in ADAS Sensor Processing
- **Deep Learning (CNN, YOLO, UNet)** for image understanding  
- **Kalman Filters** for sensor fusion and state estimation  
- **ROS (Robot Operating System)** for communication between sensor nodes  
- **Python, C++, OpenCV, TensorFlow, PyTorch** for development  

---

## 📷 Example ADAS Sensor Setup
