# ❤️ Pacemaker Simulator

Pacemaker Simulator is a real-time embedded system that models and simulates how an actual pacemaker functions. Using Simulink, Python, and the FRDM K64F microcontroller, the system processes cardiac signals in real time and visualizes heart activity under multiple pacing modes.

## 🚀 Features

- ⚡ **Supported Pacemaker Modes**
  - AOO – Asynchronous atrial pacing
  - VOO – Asynchronous ventricular pacing
  - AAI – Atrial demand pacing (paces atrium only if needed)
  - VVI – Ventricular demand pacing (paces ventricle only if needed)

- 🔄 **Real-Time Data Flow**
  - 📥 **Input:** DCM (Device Communication Module) simulates or streams cardiac signals.
  - 🔧 **Processing:** FRDM K64F microcontroller receives signals, communicates with Simulink, and applies pacemaker logic in real time.
  - 📊 **Output:** Processed signals are displayed in **heartView**, a visualization tool for pacing and heart rhythm.

## 🎬 Watch a Live Demo

- ▶️ **Live Demo:**  
  Watch a demonstration of the Pacemaker Simulator in action:  
  [Pacemaker Simulator Demo – YouTube](https://www.youtube.com/watch?v=8jMjvy24pko) 

## 🛠️ Tech Stack

- 🧩 **Simulink:** Models pacemaker algorithms and handles signal processing  
- 🐍 **Python:** Provides control scripts, integration, and data communication  
- 💻 **FRDM K64F Board:** Embedded real-time processor and communication hub  
- 🫀 **heartView:** Visualization of cardiac activity and pacing response  

## 📊 Performance Metrics

- ✅ Fully functional support for AOO, VOO, AAI, and VVI pacing modes
- 🔗 Real-time serial communication between DCM, K64F, and Simulink
- 🩺 Stable heart rhythm visualization through heartView
- 🔄 Demonstrated end-to-end pipeline from input signals → processing → output visualization

## 🧰 Future Improvements

- ➕ Add more advanced pacemaker modes (e.g., DDD, rate-responsive pacing)
- ⚡ Improve real-time performance with optimized data handling
- 🖼️ Expand visualization features in heartView for detailed diagnostics
- 🩻 Implement patient-specific parameter tuning
- 🗃️ Explore integration with biomedical datasets for validation


Showcasing the project: https://www.youtube.com/watch?v=8jMjvy24pko
