project link https://ai-smart-classroom-monitoring.vercel.app/
# 🚀 INFRAWATCH  
### Smart AI-Based Surveillance & Attendance System

INFRAWATCH is an AI-powered smart monitoring system that automates student attendance using CCTV cameras and computer vision. It leverages deep learning-based face recognition to identify students in real time and maintain accurate attendance records without manual intervention.

---

## 📌 Project Overview

Traditional attendance systems are time-consuming and prone to errors such as proxy attendance. INFRAWATCH solves this problem by using CCTV camera feeds and AI to automatically detect, recognize, and record student attendance in real time.

This project is designed to support smart classrooms and smart campus infrastructure.

---

## ✨ Features

- 🎯 Automatic face recognition-based attendance  
- 📷 Real-time student detection using CCTV feeds  
- 🧠 Deep Learning (CNN) for face recognition  
- 🔐 Secure and structured data storage  
- 🌐 Flask-based web interface  
- 📊 Scalable system for classrooms and campuses  

---

## 🛠️ Tech Stack

| Category        | Technology Used        |
|----------------|----------------------|
| Language       | Python               |
| Libraries      | OpenCV, NumPy        |
| Framework      | Flask                |
| AI Model       | CNN / Face Recognition |
| Database       | JSON (extendable to SQL) |

---

## 🧠 How It Works

1. CCTV camera captures live video feed  
2. Frames are processed using OpenCV  
3. Face detection is performed  
4. Recognized faces are matched with stored student data  
5. Attendance is automatically recorded in the system  

---

## 📂 Project Structure
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
