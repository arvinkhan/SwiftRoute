**Description**
An automated traffic management system that uses computer vision to detect vehicle congestion levels at intersections, dynamically adjusting signal timers to optimize traffic flow and reduce idling time.

---

# SwiftRoute 🚦

**Smart Traffic Synchronization via Real-Time Congestion Analysis.**

SwiftRoute is an intelligent traffic control solution designed to replace static timers with data-driven automation. By analyzing live camera feeds, the system calculates vehicle density and adjusts traffic light durations dynamically to clear congestion faster.

### 🧠 The Logic

The system moves away from "fixed-time" signals and uses a density-based priority algorithm:

* **Vehicle Detection:** Uses specialized image processing to count vehicles in each lane at an intersection.
* **Dynamic Timing:** Automatically extends green lights for high-congestion lanes while shortening wait times for empty ones.
* **Congestion Mapping:** Identifies bottlenecks in real-time to prevent "gridlock" before it happens.
* **Emergency Overrides:** Built-in capability to prioritize specific lanes based on visual triggers.

---

### 🚀 Setup & Installation

To keep the repository clean, the environment folder (`mp_env`) is ignored. Set up your local instance below:

**1. Clone the Project**

```bash
git clone https://github.com/arvinkhan/SwiftRoute.git
cd SwiftRoute

```

**2. Initialize Your Environment**

```powershell
# Create the virtual environment
python -m venv mp_env

# Activate it (Windows)
.\mp_env\Scripts\activate

# Activate it (Mac/Linux)
source mp_env/bin/activate

```

**3. Install Dependencies**

```bash
pip install -r requirements.txt

```

---

### 🛠 How to Run

Ensure your video source or camera feed is configured in the settings, then execute:

```bash
python main.py

```

### 📈 Key Features

* **Adaptive Signal Control:** No more waiting at a red light when the intersection is empty.
* **Computer Vision Integration:** High-accuracy vehicle counting using optimized detection models.
* **Scalable Architecture:** Designed for easy deployment across multiple city junctions.
* **Resource Efficient:** Optimized to run on edge devices for real-time processing.

---

**Developed by [Arvin Khan](https://www.google.com/search?q=https://github.com/arvinkhan) & Team** *Reducing global carbon footprints through smarter infrastructure.*
