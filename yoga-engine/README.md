# Yoga Engine

**Yoga Engine** is a modular React/TypeScript project designed to manage multiple yoga-related modules including presence tracking, analytics, breathwork, Tai Chi/Qigong, regulation, licensing, and a master dashboard. Each module is self-contained with its own app and dashboard components.

---

## 🗂 Project Structure

yoga-engine/
│
├─ core/
│ ├─ package.json # Core module package info
│ ├─ types.ts # Shared type definitions
│ ├─ utils.ts # Utility functions
│ └─ server.ts # Core server placeholder
│
├─ modules/
│ ├─ presence/
│ │ ├─ package.json
│ │ ├─ App.tsx
│ │ └─ Dashboard.tsx
│ ├─ analytics/
│ │ ├─ package.json
│ │ ├─ App.tsx
│ │ └─ Dashboard.tsx
│ ├─ breath/
│ │ ├─ package.json
│ │ ├─ App.tsx
│ │ └─ Dashboard.tsx
│ ├─ tai-chi-qigong/
│ │ ├─ package.json
│ │ ├─ App.tsx
│ │ └─ Dashboard.tsx
│ ├─ regulation/
│ │ ├─ package.json
│ │ ├─ App.tsx
│ │ └─ Dashboard.tsx
│ ├─ licensing/
│ │ ├─ package.json
│ │ ├─ App.tsx
│ │ └─ Dashboard.tsx
│ └─ master-dashboard/
│ ├─ package.json
│ ├─ App.tsx
│ ├─ Dashboard.tsx
│ └─ types.ts
