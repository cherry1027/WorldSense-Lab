# WorldSense Lab

A polished two-page React prototype for exploring synthetic autonomous-driving world models, future predictions, model comparisons, and failure cases.

## Live Demo

https://worldsense-lab.charanvaranasi44.workers.dev

## Pages

### 1. World Model Explorer

- Urban, highway cut-in, and pedestrian-crossing scenarios
- Top-down synthetic driving visualization
- Ego vehicle, surrounding vehicles, and pedestrians
- Occupied, free, and unknown areas
- Current and predicted trajectories
- Animated 1–3 second future-world prediction
- Prediction confidence, conflicts, and object-state forecasts

### 2. Synthetic Data & Evaluation

- Clear, rain, and fog conditions
- Day and night modes
- Adjustable traffic and occlusion levels
- Baseline Training vs. Baseline + Synthetic Data
- Trajectory Error, Occupancy IoU, and Rare Scenario Recall
- Interactive night/rain/occlusion failure-case explorer

## Important Disclaimer

**Independent Research Prototype — Synthetic Driving Scenes & Results**

All scenes, predictions, metrics, and evaluation results are synthetic and illustrative.

- No backend
- No real neural network
- No CARLA
- No Zenseact data
- No real sensor data
- No claims of validated autonomous-driving performance

## Technology

- React 19
- TypeScript
- Vinext/Vite
- Tailwind CSS
- Radix UI
- Lucide icons
- Cloudflare Workers
