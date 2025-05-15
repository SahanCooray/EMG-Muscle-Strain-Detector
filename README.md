#  EMG-Muscle-Strain-Detector

> A **fully analog** EMG-based muscle strain detection system with real-time LED feedback — no microcontrollers, no programming.



---

## ⚡ Overview

The **EMG-Muscle-Strain-Detector** is a **portable, low-cost, analog-only device** designed to monitor muscle activity and detect muscle strain levels using surface EMG signals. Built entirely with analog components, this device provides **real-time feedback** using LEDs to indicate the intensity of muscle strain — **Low**, **Medium**, or **High**.

---

## 🔑 Key Features

- 🔌 **Fully Analog Circuitry**  
  No microcontrollers or digital processing — purely hardware-based design.

- 🎯 **Strain Level Indication**  
  - Green LED: Low strain  
  - Yellow LED: Medium strain  
  - Red LED: High strain  

- 🧪 **Three Wet Electrodes**  
  Reliable signal acquisition using industry-standard wet electrodes.

- ⚙️ **Analog Signal Processing**  
  - Instrumentation Amplifier for EMG signal amplification  
  - Second-order Low-Pass Filters to remove noise  
  - Precision Full-Wave Rectifier to extract envelope  
  - Comparator with thresholds to drive LED indicators

- 🔋 **Battery Powered**  
  Operates with **two 9V batteries** for true portability.

---

## 🧠 How It Works

1. **Signal Acquisition:**  
   EMG signals are picked up using **three wet electrodes** (2 active + 1 reference/ground).

2. **Amplification:**  
   An **instrumentation amplifier** boosts the weak EMG signal to a usable range.

3. **Filtering:**  
   A **second-order low-pass filter** removes high-frequency noise and interference.

4. **Rectification:**  
   A **precision full-wave rectifier** converts the AC signal to a DC signal representing muscle activation.

5. **Level Detection:**  
   A **comparator circuit** with multiple thresholds activates different LEDs based on the detected voltage (signal strength).

---

## 🧰 How to Use

1. **Attach Electrodes**  
   - Place two active electrodes on the target muscle.  
   - Place the reference electrode on a bony or neutral area (e.g., elbow or wrist).

2. **Power the Circuit**  
   - Connect two 9V batteries (±9V power rails).

3. **Read the LEDs**  
   - Green LED: Low muscle strain  
   - Yellow LED: Moderate strain  
   - Red LED: High muscle strain

> 🔍 Ideal for simple muscle strain detection, sports science demos, or educational labs.


---

## 🧪 Applications

- Physio and sports therapy demos  
- EMG signal visualization in educational setups  
- Precursor for digital EMG and prosthetic interface projects  
- Muscle training and strain detection

---
