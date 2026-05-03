# 🌆 Cyber-Grid IoT Dashboard (AI Home Automation)

A full-stack, cyberpunk-themed IoT home automation dashboard built with React and Node.js. Experience a high-fidelity, neon-infused interface featuring extensive animations, device management, and AI-driven optimization.

## ✨ Features

- **Neon Cyberpunk Aesthetic**: A visually stunning UI with glassmorphism, glowing accents, and fluid micro-animations (powered by Framer Motion).
- **Device Management System**: Add, list, and control various smart devices (ACs, smart bulbs, etc.) across different rooms.
- **Strategic Sector Assignment**: Custom zone management for grouping devices efficiently.
- **Power Output Visualization**: Real-time simulated data visualization using Recharts to monitor energy consumption.
- **AI-Driven Optimization**: Automated, intelligent control of appliances for optimal performance and energy savings.
- **Protocol Synchronization**: Robust synchronization across all integrated device types.
- **Vercel Deployment Ready**: Pre-configured `vercel.json` for seamless deployment.

## 🛠️ Tech Stack

**Frontend:**
- React (v19)
- Vite
- Tailwind CSS
- Framer Motion (Animations)
- Recharts (Data Visualization)
- Lucide React & React Icons
- React Router DOM

**Backend:**
- Node.js
- Express.js
- CORS

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn

### 1. Clone the Repository
```bash
git clone <repository-url>
cd ai_home
```

### 2. Setup Backend
```bash
cd backend
npm install
node index.js
```
*(The backend runs on Express and handles API routing for the devices.)*

### 3. Setup Frontend
Open a new terminal window:
```bash
cd frontend
npm install
npm run dev
```
*(The frontend will be available at `http://localhost:5173` or as specified by Vite.)*

## 🌐 Deployment
This project is configured for easy deployment on **Vercel**.
Ensure your API endpoints in the frontend point to the correct deployed backend URL. The `vercel.json` file in the root directory manages routing to support the backend serverless functions alongside the frontend.

## 📝 License
This project is licensed under the ISC License.