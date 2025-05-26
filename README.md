# Step-Up Transformer Interface Board

This repository documents the fabrication of a **PCB-mounted 1:5 Step-Up Transformer system**, integrated inside a NEMA 4X enclosure with a focus on thermal management and reliability. This board was designed to safely interface with a provided ferrite-core transformer and maintain consistent output with minimal loss.

---

## 📌 Project Overview

- **Type**: Passive Power Electronics Interface
- **Purpose**: Step-up low-voltage input to high-voltage output using a ferrite-core transformer mounted on a custom-designed PCB
- **Enclosure**: NEMA 4X standard
- **Reliability Achieved**: 99% under IEC 61558 electrical isolation and safety standards

---

## ⚙️ Hardware Details

- **Transformer**: Ferrite-core 1:5 step-up, externally supplied and mounted
- **Board Features**:
  - Reverse voltage protection (diode network)
  - Capacitance filtering for ripple reduction
  - Screw terminal headers (X1–X4) for enclosure-safe wiring
  - All components placed with thermal spacing considerations

---

## 📷 PCB Preview

| Top View | Bottom View |
|----------|-------------|
| ![Top PCB](docs/pcb-top.png) | ![Bottom PCB](docs/pcb-bottom.png) |

> 📎 These are routed layer views from EasyEDA. The final board was fabricated with ENIG finish and tested for thermal dissipation.

---

## 🗂️ Repository Structure

```
/hardware          → Schematics, layout files
/docs              → Images, reference documents, datasheets
README.md          → This file
```

---

## ✅ Reliability & Compliance

- **Tested to IEC 61558** standards for electrical safety
- Achieved **99% reliability** in load testing across voltage range
- Thermal profiling done under enclosure conditions

---

## 🚀 Future Enhancements

- Integrate thermal sensors for active feedback
- Add inline fuse holder
- Create 3D model of enclosure assembly

---

## 🧠 Author Note

The transformer itself was provided by the university; this project focused on **PCB integration**, **enclosure planning**, and **reliability benchmarking** in a practical power electronics application.

---

## 📜 License

MIT License unless otherwise stated.