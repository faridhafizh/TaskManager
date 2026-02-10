# TaskManager - Modern System Monitor & Process Manager

A high-performance, visually appealing Windows Task Manager built with Rust and React using the Tauri framework.

## 🚀 Features
- **Real-time System Metrics**: Monitor CPU usage, Memory consumption, and Swap space in real-time.
- **Process Management**: View all active processes with detailed information including PID, Name, CPU usage, and Memory usage.
- **Process Actions**: Standard process management capabilities, including the ability to terminate (kill) processes.
- **Modern UI**: A sleek, responsive dashboard built with Lucide icons, Framer Motion animations, and Tailwind CSS.
- **Cross-Platform Foundation**: Built on Tauri v2 for a small footprint and native performance.

## 🛠️ Technology Stack
### Frontend
- **Framework**: React 19 (TypeScript)
- **Styling**: Tailwind CSS 4
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Build Tool**: Vite 7

### Backend
- **Language**: Rust
- **Framework**: Tauri 2
- **System Info**: `sysinfo` crate for fetching hardware and process data

## 📂 Project Structure
- `/src`: Frontend React application source code.
- `/src/components`: UI components (Dashboard, ProcessTable, Sidebar, etc.).
- `/src-tauri`: Backend Rust application.
- `/src-tauri/src/lib.rs`: Core Rust logic for system data retrieval and process management.

---
