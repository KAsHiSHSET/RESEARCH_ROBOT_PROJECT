# 🚰 Autonomous Pipeline Inspection Robot  

An **AI-powered autonomous robot** designed to inspect underground water pipelines.  
It detects cracks in real-time using **computer vision (YOLOv8 + OpenCV)**, stores defect images with location metadata, and provides a **low-cost, scalable solution** for pipeline monitoring.  

---

## 📌 Problem Definition  
Underground water pipelines often suffer from **cracks, corrosion, and blockages** due to pressure changes and environmental factors.  
These hidden damages cause **water loss, contamination, and expensive repairs**.  
Current manual and CCTV inspections are **slow, error-prone, and lack automation**.  

👉 Our robot solves this by providing **AI-powered real-time crack detection, defect localization, and optimized data storage.**

---

## 🎯 Approved Objectives  
1. Design and develop a compact, autonomous robot for real-time pipeline inspection.  
2. Implement **computer vision algorithms (YOLOv8 + OpenCV)** to detect and map cracks.  
3. Use **rotary encoders** for defect localization by measuring distance traveled.  
4. Integrate hardware + AI software for **real-time detection, analysis, and reporting**.  

---

## ⚙️ Tools & Technology  

### 🔹 Hardware  
- **Raspberry Pi 4** – central processor for vision & navigation.  
- **HD Camera Module + LEDs** – captures clear images in low light.  
- **Rotary Encoder** – measures distance traveled for defect location.  
- **DC Motors + L298N Motor Driver** – movement control in pipelines.  
- **Six-Wheel Triangular Chassis** – stable waterproof design.  
- **SD Card Module** – saves only crack images + metadata.  
- **LED Lighting System** – waterproof LEDs for visibility.  

### 🔹 Software  
- **Python** – motor control, logging, AI pipeline.  
- **OpenCV** – image preprocessing & feature detection.  
- **YOLOv8** – real-time crack detection.  
- **NumPy & SciPy** – matrix + numerical operations.  
- **Matplotlib & Seaborn** – testing/validation visualization.  
- **Raspberry Pi OS** – lightweight OS for AI deployment.  

---

## 📐 Assumptions & Constraints  

### Assumptions  
- Pipeline water flow is steady & clear.  
- Tested first in controlled conditions.  
- Pipes are PVC/Concrete with smooth inner walls.  
- Battery backup: 20–30 mins per run.  

### Constraints  
- Works only in straight or curved **non-branching pipelines**.  
- Limited onboard computation (Raspberry Pi).  
- Optimized for specific diameter range.  
- Not designed for **highly turbid/chemical water** or extreme pressures.  

---

## 🛠️ Methodology  

### 1. Design & Mechanical  
- Triangular **six-wheel configuration** for stability.  
- Rubberized tires powered by DC motors.  

### 2. Movement & Distance  
- Robot moves forward; encoders log distance.  
- Each defect tagged with encoder-based location.  

### 3. Crack Detection  
- Cameras record inner walls (360° coverage).  
- Raspberry Pi runs YOLOv8 → highlights cracks in **red**.  
- Reduces human error with automated detection.  

### 4. Data Storage  
- SD card stores:  
  - Crack images (with bounding boxes).  
  - Distance logs for each defect.  

### 5. Workflow  
1. Place robot in pipeline.  
2. Robot moves forward autonomously.  
3. Cameras stream images → AI detects cracks.  
4. Encoder logs distance + stores crack image.  
5. Data saved → robot retrieved → analysis done.  

---

## 🌍 Environmental, Economic & Social Benefits  

### 🌱 Environmental  
- **Early detection** → prevents major leaks.  
- **Water conservation** → reduces wastage.  
- **Soil & ecosystem protection** → avoids contamination.  
- Promotes **sustainability** in water management.  

### 💰 Economic  
- **Reduced inspection costs** vs manual teams.  
- **Cheaper repairs** by fixing cracks early.  
- **Targeted maintenance** improves efficiency.  
- Affordable (₹10,000–15,000) solution for cities.  

### 👨‍👩‍👧 Social  
- **Reliable water supply** for homes, schools, hospitals.  
- Improved **quality of life & hygiene**.  
- Supports **sustainable urban growth**.  

---

## 📊 Project Outcomes  
- **Working Prototype** – waterproof six-wheel robot.  
- **AI Vision System** – YOLOv8 detects cracks in real time.  
- **Defect Logging** – saves crack images + location metadata.  
- **Optimized Storage** – only crack images stored (not full video).  
- **Efficient Maintenance** – targeted repair planning with reports.  

### Comparison of model
![image](https://github.com/user-attachments/assets/d821a233-dff4-47c4-a823-144b0f408e13)
---

## 📷 Demo (Prototype & Results)  

![image](https://github.com/user-attachments/assets/e9be93de-e628-4747-8a86-31e0846c8c3d)
![image](https://github.com/user-attachments/assets/6832e456-7b2e-4ffd-b628-1196819157df)
### Video demonstration

---

## ✅ Conclusion  
The **Smart Pipeline Inspection Bot** is a practical, low-cost, and efficient system for **real-time underground crack detection**.  
By combining **mechanical stability, AI-based vision, and optimized storage**, it significantly improves pipeline monitoring, reduces costs, conserves water, and supports sustainable urban infrastructure.  

---

## PPT presentation
[PPT Presentation](https://www.canva.com/design/DAGwzbTs7v4/ano-nGuKEUFgb8FWuXt2vA/edit?utm_content=DAGwzbTs7v4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 📷 Demo (Prototype & Results)  

![image](https://github.com/user-attachments/assets/e9be93de-e628-4747-8a86-31e0846c8c3d)
![image](https://github.com/user-attachments/assets/6832e456-7b2e-4ffd-b628-1196819157df)









### Comparison of model
![image](https://github.com/user-attachments/assets/d821a233-dff4-47c4-a823-144b0f408e13)



