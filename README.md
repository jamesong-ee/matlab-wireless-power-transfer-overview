# Resonant Wireless Power Transfer – MATLAB Simulation & Analysis

This project models and simulates a wireless power transfer (WPT) system using LC resonance principles. Developed as a hands-on study of how resonance tuning and coil distance affect power transfer efficiency, this project combines theory, simulation, and physical circuit insights.

---

## Features

- **Resonant Frequency Calculation**
  - Based on circuit parameters:  
**f = 1 / (2π√(LC))**


- **Frequency Response Analysis**
  - Output voltage and phase plotted across a frequency sweep from 60 kHz to 300 kHz
  - Confirms resonance near 159.16 kHz with minimal percent error

- **Efficiency vs. Coil Distance**
  - Simulated using a simplified exponential decay model for coupling coefficient \( k \)
  - Power transfer efficiency plotted over distances from 2 cm to 10 cm

- **Time-Domain Waveform Simulation**
  - Sinusoidal transmitter and received voltage signals plotted to show energy transfer dynamics
  - Observes attenuation and phase lag in the receiver waveform

---

## Simulation Snapshots

![image](https://github.com/user-attachments/assets/a2b7348d-c1af-4f42-89d2-23b7303cd98b)


---

## Files Included (in private repo)

- `WPT_Trial1.m` – Full MATLAB code for simulation and analysis
- `TimeDomainVoltageWaveform_Trial1.fig` – Time-domain voltage plot at resonance
- `EECS150_Project.pdf` – Project write-up detailing background, theory, methods, and results

---

## Tools Used

- MATLAB (base + plotting functions)
- Falstad Circuit Simulator (for visual validation)
- LTSpice (optional circuit modeling)
- Physical LC circuit testing (lab work)

---

## Author

James Ong  
This is a public-facing overview. The full implementation is available privately and can be shared upon request.

---

## 📌 Academic Honesty Notice

This project was completed as part of an academic assignment.  
It is shared for educational and portfolio purposes only.  
**Do not reuse or submit this work for course credit.**

---

## 📄 License

This work is licensed under the [Creative Commons BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.

> You may view and share this work with attribution, but you may not reuse it for academic submission, modify it, or use it commercially.
