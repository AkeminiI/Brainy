# Brainy: Integrated Autonomous Rover System

Brainy is a tri-brain robotics platform combining:
- **Pixhawk** — the pilot  
- **Jetson Nano** — the intelligence  
- **Arduino Mega** — the senses  

Together they form a modular, intelligent autonomous rover capable of advanced AI navigation, sensor fusion, voice control, and multi-system coordination.

---

## 🧠 Project Overview
Brainy integrates:
- AI-based perception  
- MAVLink control  
- Real-time sensor fusion  
- Environmental sensing  
- Safety shutdown systems  
- Advanced planning and voice interaction  

This project is designed for research, engineering development, and robotics experimentation using professional-grade tools.

---

## 🚗 The Three-Brain Architecture

### **Jetson Nano (High-Level AI)**
- Runs neural networks  
- Handles speech recognition  
- Performs vision processing  
- Sends navigation commands to Pixhawk  

### **Pixhawk (Pilot / Motion Control)**
- Controls motors + steering  
- Executes autonomous modes  
- Maintains stability  
- Implements safety failsafes  

### **Arduino Mega (Sensor Hub)**
- Reads ultrasonic, IR, tilt, shock, rain, and light sensors  
- Provides microsecond timing  
- Relays data to Jetson + Pixhawk  
- Acts as the rover’s “sensory nervous system”  

---

## 🛠️ Key Features (Planned)

- **Voice-controlled rover** using Vosk/Whisper  
- **Multi-sensor obstacle detection** (Ultrasonic + IR + camera)  
- **AI perception system** for object detection  
- **Safety shutdown** via tilt and shock sensors  
- **Environmental monitoring** (DHT11, moisture, rain, light)  
- **Day/night auto mode** with IR LEDs  
- **Modular architecture** for mixing Jetson, Pixhawk, Arduino  

---

## 📁 Repository Structure
