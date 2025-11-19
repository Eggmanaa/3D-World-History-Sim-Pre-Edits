# 3D World History Simulator

A React-based 3D interactive world history simulation using Three.js and React Three Fiber.

## 🌐 Live Deployment

- **Production URL**: https://3dworldhissim.pages.dev
- **Latest Deployment**: https://fdc5c282.3dworldhissim.pages.dev
- **Platform**: Cloudflare Pages
- **Status**: ✅ Active

## 📦 Project Overview

- **Name**: 3D World History Simulator
- **Goal**: Interactive 3D visualization of world history with civilizations, events, and cultural development
- **Tech Stack**: React + TypeScript + Three.js + React Three Fiber + Vite
- **Features**: 
  - 3D globe visualization
  - Historical civilizations and their territories
  - Timeline-based events
  - Cultural stages (Barbarism, Classical, Imperial)
  - Interactive statistics and metrics

## 🚀 Development

### Prerequisites
- Node.js (v18 or higher)

### Local Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   NODE_OPTIONS="--max-old-space-size=4096" npm run build
   ```

### Deployment

Deploy to Cloudflare Pages:
```bash
npx wrangler pages deploy dist --project-name 3dworldhissim
```

## 📊 Data Architecture

- **Data Models**: Civilizations, Historical Events, Cultural Stages, Statistics (Martial, Defense, Faith, Industry, Science, Culture, Capacity)
- **Storage**: Client-side state management with React
- **3D Rendering**: Three.js with React Three Fiber for WebGL rendering

## 🎮 User Guide

1. Visit https://3dworldhissim.pages.dev
2. View the interactive 3D globe with historical civilizations
3. Navigate through historical timeline
4. Observe civilization development and cultural stages
5. Track various metrics (population, martial, defense, faith, industry, science, culture)

## 🔗 Links

- **GitHub Repository**: https://github.com/Eggmanaa/3D-World-History-Sim-Pre-Edits
- **AI Studio**: https://ai.studio/apps/drive/1_vgX2GpTCV8BJZohXfUqbUCJM7ZPOsYv

## 📝 Recent Updates

- Fixed TypeScript error in App.tsx for capacity stat handling
- Optimized Vite build configuration with code splitting
- Deployed to Cloudflare Pages with optimized bundle size
- Last Updated: November 19, 2025
