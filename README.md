# Bio-Signal Amplifier for ECG, EMG, and EOG Acquisition

> *This project was implemented as a hardware prototype; therefore, no software code is included.*

## 📌 Overview
This project focuses on designing and implementing a high-gain bio-signal amplifier capable of acquiring low-amplitude physiological signals such as ECG (Electrocardiogram), EMG (Electromyogram), and EOG (Electrooculogram).

Bio-signals are typically in the microvolt (µV) range and are highly susceptible to noise. This system amplifies and filters these weak signals to produce a stable and observable output.

---

## 🎯 Objectives
- Design a high-gain amplification system for bio-signals  
- Capture real-time ECG, EMG, and EOG signals  
- Reduce noise using analog filtering techniques  
- Achieve stable and clear signal visualization  

---

## ⚙️ System Architecture

**Signal Flow:**

Electrodes → Instrumentation Amplifier → Gain Stage → Active Filters → Output

---

## 🔬 Working Principle

### 1. Signal Acquisition
Surface electrodes are used to capture bio-signals from the human body. These signals are extremely weak and require amplification.

### 2. Instrumentation Amplifier
The first stage uses an instrumentation amplifier to:
- Provide high gain  
- Ensure high Common Mode Rejection Ratio (CMRR)  
- Minimize noise from external interference  

### 3. Gain Stage
Additional amplification is applied using op-amps to bring the signal to a usable level.

### 4. Active Filtering
- **High-pass filter (HPF):** Removes baseline drift  
- **Low-pass filter (LPF):** Eliminates high-frequency noise  

This ensures a clean and stable signal output.

---

## 🔌 Circuit Details
- Multi-stage amplifier design using operational amplifiers  
- Instrumentation amplifier used for initial signal conditioning  
- Active filters implemented for noise reduction  
- Analog signal processing approach  

---

## 📊 Results

The system successfully captured:

- **ECG signals** with visible waveform patterns (P-QRS-T structure)  
- **EMG signals** representing muscle activity  
- **EOG signals** corresponding to eye movement  

The output signal showed improved clarity after filtering, with reduced noise and better stability.

📷 *Sample Output:*

![Output Signal](./output.jpg)

---

## ⚠️ Challenges Faced
- Noise interference from environment and power supply  
- Difficulty in stabilizing baseline signal  
- Proper electrode placement for accurate readings  
- Signal distortion at higher gain levels  

---

## 🔧 Future Improvements
- Implement PCB design for compact and stable hardware  
- Add digital filtering using microcontrollers  
- Improve shielding to reduce external noise  
- Integrate with data acquisition systems for real-time monitoring  

---

## 🛠️ Tools & Components Used
- Operational Amplifiers (Op-Amps)  
- Instrumentation Amplifier  
- Resistors & Capacitors  
- Breadboard for prototyping  
- Power supply unit  

---

## 📚 Learning Outcomes
- Practical understanding of bio-signal acquisition  
- Experience with analog circuit design and debugging  
- Knowledge of filtering techniques for noise reduction  
- Hands-on exposure to biomedical instrumentation  

---

## 👨‍💻 Author
**Swadheen Nayak**  
Biomedical Engineering Undergraduate  

- LinkedIn: https://www.linkedin.com/in/swadheen-nayak-6a1186325  
- GitHub: https://github.com/Swadheen-Nayak  

---
