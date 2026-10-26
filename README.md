# AquaPulse Virtual Controller (Mobile Remote)

A dedicated, mobile-optimized Progressive Web Controller for **AquaPulse**.
Allows researchers, testers, and demonstrators to stream virtual ESP32 sensor telemetry directly to the AquaPulse FastAPI backend (`/api/sensor-data`).

## Features
- **1-Tap Scientific Presets**: Pure Drinking, Hard Water / Scale Risk, Acidic Runoff, High Turbidity / Sediment.
- **Micro-Jitter Emulation**: Simulates natural analog ADC sensor fluctuations.
- **Continuous 5s Live Stream & Single Burst Injection**.
- **Works on any Smartphone Browser**: Zero installation required.

## Local Development
```bash
npm install
npm run dev
```

## Production Deployment (Vercel)
- **Framework**: Vite
- **Root Directory**: `./` (Default)
- **Environment Variable**:
  - `VITE_API_URL`: `https://aquapulse-ne52.onrender.com`
