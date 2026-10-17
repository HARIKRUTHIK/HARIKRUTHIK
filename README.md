<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=150&section=header&text=Hari%20Kruthik%20S%20K&fontSize=50&fontColor=c9d1d9&fontAlignY=45&desc=Digital%20VLSI%20%E2%80%94%20FPGA%20RTL%20%E2%80%94%20Edge%20AI%20%2F%20TinyML%20%E2%80%94%20Embedded%20Systems&descSize=16&descAlignY=72&descColor=8b949e" width="100%"/>

</div>

<br/>

I am an **Electronics & VLSI / Embedded Systems Engineer** specializing in **Digital RTL Architecture, FPGA Acceleration, Edge AI / TinyML**, and **Real-Time Embedded Systems**. My work focuses on bridging hardware microarchitecture with production edge computing — designing scalable systolic array processors (Altera Cyclone IV), low-latency Network-on-Chip routers, quantized deep learning inference pipelines (ESP32, TFLite Micro), and multi-rate industrial telemetry networks.

---

## Technical Skills

**VLSI & Digital Hardware Design**

![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-185F89?style=flat-square&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
![Quartus Prime](https://img.shields.io/badge/Intel_Quartus_Prime-0071C5?style=flat-square&logo=intel&logoColor=white)
![Cadence Virtuoso](https://img.shields.io/badge/Cadence_Virtuoso-DE1C24?style=flat-square&logoColor=white)
![Cyclone IV FPGA](https://img.shields.io/badge/Altera_Cyclone_IV-003C71?style=flat-square&logo=intel&logoColor=white)
![SDC Timing](https://img.shields.io/badge/SDC_Timing_STA-4A154B?style=flat-square&logoColor=white)
![CMOS Logic](https://img.shields.io/badge/CMOS_Transistor_Design-5C2D91?style=flat-square&logoColor=white)

**Edge AI, TinyML & Embedded Systems**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![TFLite Micro](https://img.shields.io/badge/TensorFlow_Lite_Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-008B8B?style=flat-square&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F58225?style=flat-square&logo=platformio&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**IoT, Telemetry & Full-Stack**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)
![Server-Sent Events](https://img.shields.io/badge/SSE_Telemetry-24292E?style=flat-square&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**RF & Electromagnetic Simulation**

![ANSYS HFSS](https://img.shields.io/badge/ANSYS_HFSS-FFA500?style=flat-square&logoColor=black)
![FEM Analysis](https://img.shields.io/badge/FEM_Electromagnetics-0A3B5C?style=flat-square&logoColor=white)
![S-Parameters](https://img.shields.io/badge/S--Parameters_%26_Radiation-2E7D32?style=flat-square&logoColor=white)

---

## Featured Projects

### CNN Hardware Accelerator for Solar Panel Faults (B.Tech Capstone / FYP)
> Deep-learning-driven photovoltaic defect classification paired with a synthesizable Zero-Aware MAC hardware accelerator.

- **Transfer Learning Pipeline** — Trained EfficientNetV2-B0 across 21,660 aerial electroluminescence and thermal images spanning 4 fault classes (92.36% validation accuracy, 92.21% macro F1-score, 84.91% test accuracy)
- **Zero-Aware MAC Architecture** — Synthesizable Verilog datapath (`rtl/zero_aware_mac.v`) featuring dynamic zero-operand detection and power gating to bypass redundant multiplication cycles
- **Verification & Hardware Metrics** — Self-checking testbench (`tb/tb_zero_aware_mac.v`) validating bit-exact INT8 accumulation and cycle-accurate dynamic power reduction under high activation sparsity

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Solar-Panel-Fault-Hardware-Accelerator)

---

### VOQ 2×2 Network-on-Chip (NoC) Router
> A synthesizable Verilog-2001 32-bit packet router with Virtual Output Queues, XOR CRC, and aging-based matrix arbitration.

- **Pipeline Architecture** — 4-stage pipeline (Input Latch, Routing & VOQ Decoupling, Aging-Matrix Arbiter, Switch Traversal)
- **Fault Tolerance & Flow Control** — 5-bit XOR segment CRC error detection, anti-starvation matrix aging arbiter, per-packet cycle latency measurement
- **Timing & Verification** — SDC timing closure at 100 MHz clock; verified with ModelSim regression testbenches (TB_S1 to TB_S6) under zero packet loss

![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
![Quartus Prime](https://img.shields.io/badge/Intel_Quartus_Prime-0071C5?style=flat-square&logo=intel&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/VOQ-2x2-NoC-Router)

---

### Real-Time Athlete Monitoring System
> An intelligent multi-rate wearable sensor system combining kinematics, clinical vitals filtering, and on-device machine learning.

- **Sensor Fusion & Edge Compute** — ESP32/ESP32-S3 cooperative scheduling (200 Hz IMU kinematics / 25 Hz photoplethysmography vitals)
- **Signal Processing & Edge AI** — 16-tap FIR bandpass filter (HR MAE 2.1 BPM, SpO₂ error 1.3%), embedded Random Forest classifier (93.9% F1, 18 ms latency)
- **Ecosystem** — EEQA encrypted QR code generator (120 ms display), full-stack Node.js telemetry gateway, and real-time React dashboard

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Real-Time-Athlete-Monitoring)

---

### Smart Industrial Machine Monitoring & Predictive Maintenance
> An industrial IoT solution with on-device FFT spectral vibration analysis and unsupervised machine learning.

- **Edge Signal Processing** — ESP32 computing 128-point vibration FFT (MPU6050, DS18B20, DHT22) achieving >90% telemetry bandwidth reduction
- **Anomaly Detection Engine** — FastAPI backend with Isolation Forest machine learning scoring multi-axis vibration severity
- **Digital Twin Visualizer** — Real-time Server-Sent Events (SSE) telemetry pipeline driving an interactive 3D machine dashboard

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Smart-Industrial-Machine-Monitoring)

---

### TinyML Garbage / Waste Classification on ESP32
> Knowledge-distilled and INT8-quantized deep learning vision model running on Xtensa LX6 microcontrollers.

- **Knowledge Distillation** — EfficientNetB0 teacher compressed to MobileNetV3Large ($\alpha=0.75$) student (84.49% accuracy)
- **Quantization & Footprint** — Post-training INT8 quantization producing 2.19 MB flatbuffer footprint fitting in external Flash
- **Embedded Runtime** — C++ inference pipeline using TensorFlow Lite Micro with a 120 KB SRAM tensor arena

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![TFLite Micro](https://img.shields.io/badge/TensorFlow_Lite_Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/TinyML-Garbage-Classification-ESP32)

---

### Consolidated FPGA Digital Design Lab Suite & CMOS Transistor RCA
> Digital RTL IP library and transistor-level CMOS microarchitectures with automated verification harnesses.

- **RTL IP Modules** — Parameterized Adders (RCA, CLA, CSA, CSkipA, CSelectA, ConsumA), Multipliers, FIR filters, Sobel Edge Detector, Dual-Port RAM, FIFOs, FSMs
- **Transistor-Level Design** — Static CMOS, PTL, and Transmission Gate 4-bit Ripple Carry Adders characterized in Cadence Virtuoso
- **Automated Regression** — Self-checking testbench suite with ModelSim batch scripts (`run_all.do`) and automated Python regression runner

![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
![Cadence Virtuoso](https://img.shields.io/badge/Cadence_Virtuoso-DE1C24?style=flat-square&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/FPGA-Digital-Design)

---

## Professional Experience & Training

**VLSI Design & Verification Intern** &nbsp;|&nbsp; Maven Silicon
- Authored synthesizable Verilog RTL for digital sub-blocks and Moore/Mealy FSM controllers
- Executed functional verification and coverage analysis in ModelSim; achieved FPGA timing closure in Intel Quartus Prime

**Technical Intern** &nbsp;|&nbsp; PlasmaGen Biosciences Pvt Ltd
- Programmed and validated industrial PLC automation routines and multi-channel sensor acquisition nodes
- Conducted hardware-in-the-loop (HIL) calibration and signal reliability testing for manufacturing lines

**RTL to GDSII (ASIC/FPGA Design Flow)** &nbsp;|&nbsp; VIT SENSE
- Completed 30-hour specialized value-added training covering synthesis, static timing analysis (STA), and physical layout verification

**Pre-VDAT Hands-on VLSI Design** &nbsp;|&nbsp; Cadence Design Systems Workshop
- Conducted schematic capture, transient analysis, power-delay-product (PDP) optimization, and parasitic extraction in Cadence Virtuoso

---

## Contact

[![Email](https://img.shields.io/badge/harikruthik06%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:harikruthik06@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/@HARIKRUTHIK-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/Hari_Kruthik_S_K-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harikruthik-sk/)

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=80&section=footer" width="100%"/>

</div>
