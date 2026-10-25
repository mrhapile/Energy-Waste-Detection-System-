# Energy-Waste-Detection-System-
The main problem is energy waste that goes unnoticed because people struggle to identify where, when, and why energy is being wasted.


# ⚡ AI-Powered Energy Waste Detection & Resolution System

An AI-powered system that detects unusual energy consumption, investigates probable causes, coordinates corrective actions, and verifies whether energy waste has been reduced.

## 📌 Problem Statement

Energy waste often goes unnoticed in factories and industrial facilities because identifying where, when, and why electricity is being wasted requires manual investigation.

For example, when electricity consumption suddenly increases, staff may not know whether a machine is faulty, equipment is running unnecessarily, or production has increased.

This delays corrective action, resulting in unnecessary energy consumption and higher operational costs.

## 💡 Our Solution

We aim to build an intelligent system that closes the gap between detecting energy inefficiencies and verifying their resolution.

The system will:

1. **Detect anomalies** in energy consumption using historical and test datasets.
2. **Investigate root causes** by analysing energy usage alongside simulated machine status, production schedules, and maintenance records.
3. **Generate actionable alerts** with probable causes, supporting evidence, and recommended next steps.
4. **Coordinate corrective actions** by tracking maintenance tasks and incident status within the application.
5. **Verify improvements** by analysing energy consumption after a simulated corrective action.
6. **Estimate savings** by calculating potential energy and cost reductions.

## ✨ Key Features

- 📊 **Energy Monitoring:** Track consumption across simulated machines and production areas.
- 🚨 **Anomaly Detection:** Identify unexpected spikes and inefficient operating patterns.
- 🔍 **Root-Cause Analysis:** Investigate probable causes using historical and operational data.
- 🔔 **Smart Alerts:** Display prioritised incidents and reduce false alarms using production context.
- 🛠️ **Maintenance Coordination:** Assign tasks and track corrective actions through the dashboard.
- ✅ **Resolution Verification:** Check whether consumption returns to its expected range after an intervention.
- 💰 **Energy Savings Analysis:** Estimate excess consumption and potential cost savings.
- 👥 **Human-in-the-Loop:** Keep corrective-action approval and physical maintenance under human supervision.

## 🔄 How It Works

```text
Dummy / Test Energy Datasets
             |
             v
     Data Processing
             |
             v
     Anomaly Detection
             |
             v
     Root-Cause Analysis
             |
             v
       Smart Alerts
             |
             v
    Human Review & Approval
             |
             v
    Simulated Corrective Action
             |
             v
   Energy Usage Verification
             |
             v
    Savings & Outcome Report
```

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|---|---|---|
| Frontend | React.js + Tailwind CSS | Dashboard, alerts and incident tracking |
| Backend | Python + FastAPI | Application logic and API endpoints |
| AI / ML | Python, scikit-learn, PyTorch | Anomaly detection, forecasting and energy analysis |
| GPU Compute | Jarvis Labs | GPU-backed model training or inference |
| Workflow Orchestration | Temporal | Incident lifecycle, retries, follow-ups and resolution verification |
| Data Processing | Pandas + NumPy | Processing and analysing energy datasets |
| Visualisation | Recharts | Consumption trends, anomaly charts and savings reports |
| Containerisation | Docker + Docker Compose | Reproducible development and deployment environments |
| Version Control | Git + GitHub | Source control and collaboration |

## 🧪 Prototype Data

The initial prototype will use dummy or test datasets rather than live industrial sensors.

The datasets will represent:

- Energy consumption readings over time.
- Machine operating and idle states.
- Production schedules and output levels.
- Historical maintenance incidents.
- Normal consumption patterns and simulated anomalies.

This approach enables the complete detection-to-verification workflow to be demonstrated without requiring access to factory equipment.

## 🔄 Workflow Orchestration with Temporal

Temporal will manage the incident lifecycle as a durable workflow:

1. Start an investigation when an anomaly is detected.
2. Coordinate data analysis and root-cause investigation.
3. Record the incident and present recommended actions.
4. Wait for human approval and completion of the simulated corrective action.
5. Schedule a follow-up analysis.
6. Verify whether consumption has improved and record the outcome.

Retries, timeouts, and follow-up scheduling will help the workflow handle failures and delayed actions reliably.

## 🎯 Expected Impact

- Earlier detection of potential energy inefficiencies.
- Reduced manual investigation effort.
- Improved maintenance coordination and accountability.
- Better identification of false alarms.
- Measurable assessment of energy and cost savings.
- A foundation for future integration with real energy meters and industrial systems.

## 🚀 Core Objective

**Move beyond energy monitoring to actionable energy management.**

The goal is to build a system that detects potential energy waste, investigates its probable causes, coordinates corrective actions, and verifies whether the problem has been resolved.

## Run Locally

**Prerequisites:** Node.js

1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in `.env.local` to your Gemini API key.
3. Run the app:
   `npm run dev`

View the app in AI Studio: https://ai.studio/apps/1e8bc730-b1aa-4687-82bb-51f3403bc9cf
