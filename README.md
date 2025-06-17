# Project URJA ⚡🌱

Project URJA aims to harness hybrid renewable energy by integrating **Vertical Axis Wind Turbines (VAWTs)** with **solar panels** to produce sustainable electricity in urban areas such as highways and metro corridors. It targets unused wind sources from vehicular movement and natural wind, combined with solar irradiation, to generate and feed electricity into the grid.

---

## 🌍 Problem Statement

Urban areas in India suffer from high levels of air pollution and increasing energy demand. With fossil fuels causing economic and environmental strain, the need for clean, decentralized, and efficient energy generation has become urgent.

---

## 🧠 Solution Overview

Project URJA proposes a dual-source renewable system:
- A **Helical Vertical Axis Wind Turbine (VAWT)** driven by ambient and vehicle-induced wind.
- **Solar panels** mounted on the turbine structure for additional power generation.
- **Permanent Magnet Synchronous Generator (PMSG)** coupled via gearbox for efficient power conversion.

Both sources produce electricity that is analyzed, validated, and simulated in **MATLAB Simulink**.

---

## ⚙️ Technical Specifications

- **Software**: MATLAB R2023a with Simulink
- **Simulation Components**:
  - PV Array
  - Wind Turbine
  - DC Generator
  - Scope, Display, PowerGUI
  - Multiplexers, Measurement Blocks
- **Hardware (for simulation)**: macOS Sonoma 14.2.1, MacBook Pro i7 2.6GHz

---

## 📊 Simulation Results

Three simulation outputs were generated:
1. **Solar Power Output** (`PowerBySolarPanelOnly.fig`)
2. **Wind Turbine Output** (`PowerByWindTurbineOnly.fig`)
3. **Combined Output Power** (`TotalPower.fig`)

The outputs validate the feasibility of combining wind and solar energy for efficient hybrid renewable generation.

---

## 📁 File Structure

├── EAD Project Report.pdf # Detailed project documentation<br>
├── projectURJA.slx # MATLAB Simulink model<br>
├── PowerBySolarPanelOnly.fig # Solar-only power output<br>
├── PowerByWindTurbineOnly.fig # Wind-only power output<br>
├── TotalPower.fig # Total combined power output<br>
├── README.md # GitHub README file<br>



---

## 🚧 Limitations

- MATLAB model uses DC outputs instead of real-world 3-phase AC.
- Helical shape could not be modeled accurately in Simulink.
- MATLAB resource-heavy due to multiple scopes and display elements.
- Transitioning to AC representation adds significant complexity and instability.

---

## 🔮 Future Scope

- Implement 3-phase AC modeling for real-world validation.
- Optimize blade design for higher wind capture.
- Include IoT-based monitoring and automation.
- Perform economic and environmental impact assessments.
- Deploy small-scale prototypes on metro pillars or highway dividers.

---

## 👨‍💻 Team

- **Anurag Singh** – 2022UIC3528
- **Kirtan Gupta** – 2022UIC3559
- **Shamiul Mirza** – 2022UIC3565


---

## 📬 Contact

For any queries or collaboration interests, feel free to reach out via GitHub or email the contributors.

---

> "Reviving dormant energy, one rotation at a time."


