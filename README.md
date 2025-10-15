# 🎥 YouTube Clone (AI + 3D Camera Effects)

> A modern **YouTube-like video platform** enhanced with **AI-powered filters** and **3D camera effects**, built using **React**, **Node.js**, **TensorFlow.js**, and **Three.js**.  
> Designed to demonstrate advanced **AI integration**, **real-time rendering**, and **seamless UI/UX performance**.

---

## 🚀 Features

✨ **AI Face Filters** – Real-time facial tracking using TensorFlow.js  
🎞️ **3D Camera Effects** – Interactive visual layers with Three.js  
🔴 **Live Video Preview** – Watch & record videos with integrated camera  
💬 **Real-Time Interaction** – WebSocket-based messaging & updates  
🧠 **AI Detection Models** – Facial landmark detection & motion effects  
📱 **Responsive UI** – Fully optimized for desktop & mobile  
🧩 **Scalable Architecture** – Frontend + Backend designed with clean structure  

---

## 🧠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | React.js, TailwindCSS, ShadCN UI, Vite |
| **Backend** | Node.js, Express.js, REST API, WebSocket |
| **AI / ML** | TensorFlow.js, MediaPipe FaceMesh |
| **3D Graphics** | Three.js, GSAP |
| **Database** | MongoDB |
| **Deployment** | Vercel (Frontend) + Render / Railway (Backend) |

---

## 🧩 Architecture Overview

```mermaid
graph TD;
  A[Camera Stream 🎥] --> B[TensorFlow.js 🤖];
  B --> C[AI Detection 🔍];
  C --> D[3D Effects Layer 🌐];
  D --> E[Render in Three.js 🧱];
  E --> F[React UI 🎨];
  F --> G[User Interaction 💬];
  G --> H[Backend API 🌍];
