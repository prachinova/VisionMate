# 👁️ VisionMate

## AI-Powered Assistive Vision System for the Visually Impaired

VisionMate is an AI-based assistive system that helps visually impaired users understand their surroundings in real time by converting visual information into **audio feedback** using computer vision and deep learning.

---

## 📌 Overview

VisionMate leverages **YOLOv8** for real-time object detection and a lightweight web-based interface to deliver spoken feedback.  
The system is designed to be **hardware-agnostic**, affordable, and scalable, requiring only a standard camera.

---

## ✨ Features

- 🚀 Real-time object detection using YOLOv8  
- 🔊 Audio feedback via Text-to-Speech (TTS)  
- 📷 Works with standard webcams (no special hardware)  
- 📏 Approximate distance estimation using bounding-box heuristics  
- 🌐 Web-based interface for easy interaction  
- ⚡ Low-latency and lightweight deployment  

---

## 🧠 System Architecture

```text
Camera Feed
     ↓
YOLOv8 Object Detection
     ↓
Bounding Box & Distance Estimation
     ↓
Flask Backend API
     ↓
Text-to-Speech Audio Output
