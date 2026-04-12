<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=AutoSenseLab&fontSize=55&fontColor=ffffff&fontAlignY=40" width="100%"/>

### Industrial AI — built for the real world, not just the lab.

![Location](https://img.shields.io/badge/📍-Thailand-red)
![Focus](https://img.shields.io/badge/🏭-Industrial%20AI-blue)
![Stack](https://img.shields.io/badge/🛠️-Python%20%7C%20TensorFlow%20%7C%20IoT-orange)

</div>

---

## เกี่ยวกับเรา

AutoSenseLab เริ่มจากคนที่ทำงานในโรงงานจริง เจอปัญหาจริง แล้วแก้ด้วย AI

เราไม่ได้ทำ AI เพื่อความสวยงามใน presentation
แต่ทำเพราะอยากให้มันแก้ปัญหาได้จริงในสายการผลิต

ทุก project ที่เราทำ มาจากโจทย์ที่เจอในชีวิตจริง
และถูกออกแบบให้ deploy ได้ ไม่ใช่แค่ทดลองใน notebook

---

## Projects

### ✅ Steel Surface Defect Detection

ระบบตรวจสอบพื้นผิวเหล็กด้วย Computer Vision
จำแนก defect ได้ 6 ประเภท พร้อม GradCAM Heatmap
ที่บอกได้ชัดเจนว่า AI กำลังดูที่จุดไหนของรูป

- Model: MobileNetV2 + GradCAM
- Dataset: NEU Steel (1,800 images, 6 classes)
- Demo: Streamlit web app

[![View Project](https://img.shields.io/badge/GitHub-steel--surface--defects--detection-181717?logo=github)](https://github.com/AutoSenseLab/steel-surface-defects-detection)

---

### 🚧 Time-to-Event Prediction *(กำลังพัฒนา)*

ระบบทำนายว่าค่าของเครื่องจักรจะถึง threshold เมื่อไหร่
เหมาะกับงาน predictive maintenance และ process monitoring

- Model: TCN / LSTM + sliding window
- Output: เวลาที่คาดว่าจะถึงจุดวิกฤต (นาที)

---

### 🚧 Industrial IoT Dashboard *(กำลังพัฒนา)*

เชื่อม PLC เข้ากับ dashboard real-time และ LINE alert
ดูสถานะเครื่องจักรได้จากมือถือ ไม่ต้องอยู่หน้างาน

- Stack: Mitsubishi PLC + Raspberry Pi + MQTT + Streamlit
- Features: real-time chart, threshold alert, LINE Notify

---

## สิ่งที่รับทำ

ถ้ากำลังมองหาคนช่วยพัฒนาระบบ AI หรือ automation
ในโรงงานหรือสายการผลิต นี่คือสิ่งที่ทำได้:

- **AI Vision Inspection** — ตรวจจับ defect อัตโนมัติแทนคนตรวจ
- **Predictive Maintenance** — รู้ก่อนเครื่องจะพัง
- **IoT Monitoring System** — sensor → dashboard → alert ครบในระบบเดียว
- **Custom AI Solution** — รับออกแบบตามโจทย์

📧 ติดต่อได้เลยที่ **ditsayabodin12@gmail.com**

---

## Tech Stack

```
AI / ML     →  TensorFlow, Keras, PyTorch, OpenCV, YOLO
Backend     →  FastAPI, Streamlit
IoT         →  Raspberry Pi, Mitsubishi PLC, MQTT, NETPIE
Edge AI     →  Jetson Nano, Jetson Orin Nano
Control     →  PID, MATLAB, Simulink
```

---

## Founder

**Ditsayabodin "Heart" Khunpanuk**

ทำงานด้าน Metrology และ Machine Integration ที่ Seagate Thailand
ก่อนหน้านี้เคยเป็น Assistant Researcher ที่ NECTEC

พื้นหลังมาจาก Mechatronic Engineering
เลยถนัดทั้ง software, hardware, และการเอาสองอย่างมาทำงานด้วยกัน

[![GitHub](https://img.shields.io/badge/GitHub-Ditsayabodin12-181717?logo=github)](https://github.com/Ditsayabodin12)
[![Email](https://img.shields.io/badge/Email-ditsayabodin12%40gmail.com-red?logo=gmail)](mailto:ditsayabodin12@gmail.com)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
