# Smart Zone AI (Intelligent Factory Monitoring & Optimisation System)

An interactive factory digital twin that simulates industrial operations, monitors machine performance, identifies production bottlenecks and explores data-driven optimisation strategies.

## Overview

Smart Zone AI is a browser-based factory simulation platform designed to demonstrate how intelligent monitoring and optimisation systems can improve manufacturing efficiency, operational safety and resource utilisation.

The application creates a simulated factory environment where users can monitor machines, workers, production flow and safety conditions through an interactive grid-based dashboard.

Users can introduce operational disruptions, observe their impact on factory performance, analyse production indicators and experiment with optimisation parameters to understand how industrial processes can be improved.

## Key Features

### 1. Interactive Factory Digital Twin
- 12 × 16 grid-based factory floor mapping.
- Visual representation of machines, workers and production areas.
- Simulated material movement and production flow.
- Interactive factory components and operational controls.

### 2. Machine Monitoring & Predictive Insights
- Machine status and performance monitoring.
- Simulated overheating and equipment failure indicators.
- Trend-based predictive risk estimates.
- Identification of potential production bottlenecks.
- Operational alerts and recommended corrective actions.

### 3. Worker & Safety Monitoring
- Simulated worker movement across the factory floor.
- PPE compliance monitoring.
- Restricted-zone monitoring.
- Safety violation alerts and anomaly simulation.

### 4. Camera Coverage & Surveillance Simulation
- Visualisation of camera coverage areas.
- Identification of potential blind spots.
- Camera availability controls.
- Simulated camera failure alerts.

### 5. Anomaly Detection & Alert Management
- Injection of simulated machine failures.
- Conveyor obstruction scenarios.
- Overheating and operational disruptions.
- Alert generation, acknowledgement and resolution.

### 6. Factory Optimisation
- Adjustable machine operating parameters.
- Production speed and resource allocation controls.
- Baseline versus optimised performance comparison.
- Evaluation of changes in production efficiency and operational performance.

### 7. Dashboard & Data Persistence
- Dark-themed industrial monitoring interface.
- Real-time simulation indicators.
- Interactive dashboard controls.
- LocalStorage-based persistence of settings and alerts.
- Factory reset functionality.

## How It Works

The platform follows a simulated industrial monitoring and optimisation workflow:

1. **Factory Mapping:** Represents the factory floor through a grid-based digital environment.
2. **Operational Simulation:** Models machine activity, worker movement and production flow.
3. **Monitoring:** Tracks simulated machine conditions, safety indicators and operational performance.
4. **Anomaly Detection:** Uses predefined rules and operating thresholds to identify potential disruptions.
5. **Performance Analysis:** Evaluates production conditions and identifies inefficiencies.
6. **Optimisation:** Allows users to modify operating parameters and compare simulated performance outcomes.

## Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Visualisation:** HTML Canvas and browser-based graphics
- **Data Persistence:** Browser LocalStorage
- **Simulation:** JavaScript-based rule-driven logic
- **Deployment:** GitHub and Vercel

## Getting Started

### Prerequisites
- A modern web browser.
- Python 3 (for running a local development server).

### Run Locally

Clone the repository:

```bash
git clone https://github.com/niya-tech/smart-zone-ai.git
```

Navigate to the project directory:

```bash
cd smart-zone-ai
```

Start the local server:

```bash
python3 -m http.server 8000
```

Open the application:

```text
http://localhost:8000
```

Alternatively, open `index.html` directly in a modern browser.

## How to Use

1. Open the dashboard and explore the factory overview.
2. Launch the factory simulation.
3. Select machines and experiment with operating parameters.
4. Introduce simulated anomalies and observe system alerts.
5. Explore machine performance and safety indicators.
6. Experiment with optimisation controls.
7. Compare factory performance under different operating conditions.

## Project Scope & Limitations

Smart Zone AI is an educational and experimental factory digital twin prototype.

- Machine readings, worker movements and camera observations are simulated.
- Anomaly detection uses predefined rules and thresholds.
- Predictive indicators use trend-based calculations rather than a trained machine learning model.
- Camera coverage is a simplified visual simulation and does not represent actual CCTV integration.
- The application operates locally in the browser without a connected industrial backend or live factory sensors.

These limitations define the current prototype scope and provide opportunities for future development.

## Future Enhancements

- Machine learning-based predictive maintenance.
- Advanced production analytics and visualisation.
- More realistic camera field-of-view modelling.
- Integration with IoT sensors and industrial data sources.
- Advanced production scheduling and resource allocation.
- Backend integration for persistent multi-user monitoring.

## Project Information

**Project:** Smart Zone AI – Intelligent Factory Monitoring & Optimisation System

**Category:** Industrial Technology | Digital Twin | Factory Simulation | Operational Optimisation

**Repository:** https://github.com/niya-tech/smart-zone-ai

**Deployment:** Vercel

---

*Smart Zone AI demonstrates how digital simulation, operational monitoring and optimisation concepts can be brought together to explore smarter and more efficient manufacturing environments.*
