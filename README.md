<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=150&section=header&text=Hari%20Kruthik%20S%20K&fontSize=50&fontColor=c9d1d9&fontAlignY=45&desc=Digital%20VLSI%20%E2%80%94%20Embedded%20Systems%20%E2%80%94%20AI%20%2F%20TinyML%20Hardware&descSize=16&descAlignY=72&descColor=8b949e" width="100%"/>

</div>

<br/>

I am an **Electronics & VLSI / Embedded Systems Engineer** specializing in **Digital RTL Microarchitecture, FPGA Hardware Acceleration, Embedded Systems**, and **Edge AI / TinyML**. My work focuses on the intersection of custom hardware architectures (Synthesizable Verilog, NoC Routers, Systolic Arrays) and constrained edge computing (ESP32, FreeRTOS, TFLite Micro, Industrial IoT telemetry).

---

## Portfolio Architecture & Domain Grouping

- **Verilog & VLSI Microarchitecture** — VOQ 2×2 NoC Router, CNN Hardware Accelerator (FYP), Precision-Scalable 4×4 NPU (PSNPU).
- **Embedded Systems & Industrial IoT** — Smart Industrial Machine Monitoring, Real-Time Edge-Controlled Agriculture, Real-Time Athlete Assistive Device.
- **AI/ML & Edge Intelligence** — Solar Panel Fault CNN Model Development, TinyML Garbage Classification on ESP32.

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

**Embedded Systems & Firmware**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-008B8B?style=flat-square&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F58225?style=flat-square&logo=platformio&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino_IDE-00979D?style=flat-square&logo=arduino&logoColor=white)
![Sensors](https://img.shields.io/badge/Sensors_(MPU6050_/_MAX30102_/_DHT22)-4B6F44?style=flat-square&logoColor=white)

**AI / ML & TinyML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![TFLite Micro](https://img.shields.io/badge/TensorFlow_Lite_Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Knowledge Distillation](https://img.shields.io/badge/Knowledge_Distillation_%26_INT8-6C3483?style=flat-square&logoColor=white)

**IoT, Telemetry & Full-Stack**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)
![Server-Sent Events](https://img.shields.io/badge/SSE_Telemetry-24292E?style=flat-square&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Featured Projects

### 1. VOQ 2×2 Network-on-Chip (NoC) Router
**Domain:** VLSI / Verilog  
> A synthesizable Verilog-2001 32-bit packet router with Virtual Output Queues, XOR CRC, and aging-based matrix arbitration.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p1_noc_router.jpg" width="85%" alt="VOQ 2x2 NoC Router Architecture"/>
</div>

- **Pipeline Architecture** — 4-stage hardware pipeline comprising Input Latching, Routing & VOQ Decoupling, Aging-Matrix Arbiter, and Switch Crossbar Traversal.
- **Fault Tolerance & Flow Control** — 5-bit XOR segment CRC parity generation, anti-starvation matrix aging arbiter, and per-packet cycle-accurate latency tracking.
- **Timing Closure & Verification** — SDC timing constraints targeting 100 MHz clock closure; thoroughly verified across 6 ModelSim testbenches (TB_S1 to TB_S6) under zero packet loss.

![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
![Quartus Prime](https://img.shields.io/badge/Intel_Quartus_Prime-0071C5?style=flat-square&logo=intel&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/VOQ-2x2-NoC-Router)

---

### 2. CNN-Based Hardware Accelerator for Solar Panel Fault Classification
**Domain:** VLSI / Verilog + AI *(B.Tech Capstone FYP — Hardware Architecture)*  
> Custom hardware accelerator microarchitecture targeting edge classification of photovoltaic defects, featuring dynamic zero-operand power gating.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p2_cnn_solar_accel.jpg" width="85%" alt="CNN Hardware Accelerator Microarchitecture"/>
</div>

- **Accelerator Status** — Final-Year Project hardware datapath design. Currently validated at the Zero-Aware MAC microarchitectural level with full array RTL implementation in progress.
- **Zero-Aware MAC Architecture** — Synthesizable Verilog datapath (`rtl/zero_aware_mac.v`) featuring dynamic zero-operand detection on weights and activations, clock-gating redundant multiplication cycles to maximize energy efficiency under sparse neural workloads.
- **Hardware Verification** — Self-checking testbench (`tb/tb_zero_aware_mac.v`) validating bit-exact INT8 multiply-accumulate operations and cycle-accurate dynamic switching power reduction.
- **Connected Pipeline** — Tightly coupled with the CNN model development and weight-zeroing sparsity experiments in **Project 5**.

![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
![Hardware Accelerator](https://img.shields.io/badge/Status-RTL_In_Progress-orange?style=flat-square)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Solar-Panel-Fault-Hardware-Accelerator)

---

### 3. Smart Industrial Machine Monitoring & Predictive Maintenance
**Domain:** Embedded Systems  
> Industrial edge IoT monitoring system with on-device FFT spectral vibration analysis and unsupervised anomaly detection.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p3_industrial_monitoring.jpg" width="85%" alt="Smart Industrial Machine Monitoring"/>
</div>

- **Edge Signal Processing** — ESP32 computing 128-point vibration FFT (MPU6050, DS18B20, DHT22) on raw acceleration data, reducing telemetry bandwidth consumption by >90%.
- **Anomaly Detection Backend** — FastAPI telemetry server integrated with an Isolation Forest machine learning model scoring multi-axis vibration severity against baseline operational profiles.
- **Digital Twin Visualizer** — Real-time Server-Sent Events (SSE) telemetry pipeline streaming live machine states into an interactive 3D digital twin dashboard.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Smart-Industrial-Machine-Monitoring)

---

### 4. Real-Time Edge-Controlled Smart Agriculture
**Domain:** Embedded Systems  
> Autonomous closed-loop edge microclimate controller with deterministic relay actuation and leaf disease classification.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p4_smart_agriculture.jpg" width="85%" alt="Real-Time Smart Agriculture Edge Control"/>
</div>

- **Deterministic Edge Control** — Sub-50ms control loop decision time with 180 ms actuator response time across soil moisture, ambient luminosity, and NPK nutrient telemetry channels.
- **Hardware Interfacing** — Optocoupled 3-channel relay control driving irrigation pumps, ventilation fans, and supplemental grow lighting.
- **Disease Inference & Simulation** — MobileNetV2 leaf disease classifier (92.3% validation accuracy) and a 24-hour diurnal microclimate simulation harness.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F58225?style=flat-square&logo=platformio&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Smart-Agriculture-Edge-Control)

---

### 5. Solar Panel Fault Classification: CNN Model Development
**Domain:** AI / ML *(B.Tech Capstone FYP — Model Training & Optimization)*  
> Deep learning model experiments, transfer learning comparisons, knowledge distillation, and weight-zeroing sparsity sweeps.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p5_solar_cnn_model.jpg" width="85%" alt="Solar Panel CNN Model Development"/>
</div>

- **Dataset & Model Training** — Evaluated across 21,660 aerial electroluminescence and thermal images spanning 4 fault categories; EfficientNetV2-B0 achieved 92.36% validation accuracy, 92.21% macro F1-score, and 84.91% test accuracy.
- **Knowledge Distillation & Sparsity** — Knowledge distillation pipeline compressing heavy backbones into lightweight students, followed by numerical weight-zeroing experiments to measure accuracy trade-offs across induced network sparsity levels.
- **Hardware Bridge** — Provides the quantized, zero-sparse weight distributions specifically tailored to feed the Zero-Aware MAC accelerator in **Project 2**.

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
[![View Model Pipeline](https://img.shields.io/badge/View_Model_Pipeline_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Solar-Panel-Fault-Hardware-Accelerator/tree/main/ml_pipeline)

---

### 6. TinyML Garbage Classification on ESP32
**Domain:** AI / ML + Embedded  
> Knowledge-distilled, INT8-quantized deep learning vision model deployed on resource-constrained Xtensa LX6 microcontrollers.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p6_tinyml_garbage.jpg" width="85%" alt="TinyML Garbage Classification on ESP32"/>
</div>

- **Teacher-Student Distillation** — EfficientNetB0 teacher compressed into MobileNetV3Large ($\alpha=0.75$) student, maintaining 84.49% classification accuracy.
- **Quantization & Flash Allocation** — Post-training INT8 quantization producing a compact 2.19 MB flatbuffer footprint partitioned in external SPI flash.
- **Edge Runtime** — C++ inference pipeline executed via TensorFlow Lite Micro utilizing a tightly constrained 120 KB SRAM tensor arena.

![TFLite Micro](https://img.shields.io/badge/TensorFlow_Lite_Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/TinyML-Garbage-Classification-ESP32)

---

### 7. Real-Time Athlete Assistive Device
**Domain:** Embedded + IoT  
> Intelligent multi-rate wearable sensor system combining kinematics monitoring, clinical vitals filtering, and on-device machine learning.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p7_athlete_device.jpg" width="85%" alt="Real-Time Athlete Assistive Device"/>
</div>

- **Multi-Rate Edge Architecture** — ESP32 cooperative scheduling separating high-frequency kinematics (200 Hz IMU posture/squat tracking) from optical vitals (25 Hz MAX30102 PPG).
- **Signal Processing & Edge AI** — 16-tap FIR bandpass filter (HR MAE 2.1 BPM, SpO₂ error 1.3%) paired with an embedded Random Forest classifier (93.9% F1, 18 ms inference latency).
- **Connected Ecosystem** — On-device EEQA encrypted QR code generator (120 ms display), Node.js telemetry gateway, and real-time React dashboard.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Real-Time-Athlete-Monitoring)

---

### 8. Precision-Scalable Neural Processing Unit (PSNPU-4×4)
**Domain:** VLSI / RTL *(Flagship Hardware Architecture)*  
> Synthesizable 16-tile systolic MAC accelerator with runtime precision scaling (INT8/INT4/INT2) implemented on Altera Cyclone IV FPGA.

<div align="center">
<img src="https://raw.githubusercontent.com/HARIKRUTHIK/HARIKRUTHIK/main/assets/p8_psnpu.jpg" width="85%" alt="PSNPU 4x4 Systolic Array Architecture"/>
</div>

- **Microarchitecture** — 4×4 systolic MAC array featuring Scalable Bit-Block (SBB) Baugh-Wooley multipliers, Bit-Bypassing Units (BBU), and Reconfigurable Filtering Units (RFU).
- **Hardware Metrics & Timing** — Fully synthesized on Altera Cyclone IV `EP4CE115F29C7` operating at 40 MHz $F_{max}$, utilizing 0 embedded DSP blocks (pure logic synthesis).
- **Automated Verification** — 2,588 passing assertions in comprehensive testbenches; benchmarked against Chest X-Ray Pneumonia (91.4% accuracy) and ECG Arrhythmia (98.2% accuracy) edge workloads.

![Verilog](https://img.shields.io/badge/Verilog_HDL-FF6F00?style=flat-square&logoColor=white)
![Cyclone IV FPGA](https://img.shields.io/badge/Altera_Cyclone_IV-003C71?style=flat-square&logo=intel&logoColor=white)
![Quartus Prime](https://img.shields.io/badge/Intel_Quartus_Prime-0071C5?style=flat-square&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-002B49?style=flat-square&logoColor=white)
[![View Repository](https://img.shields.io/badge/View_Repository_%E2%86%92-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HARIKRUTHIK/Precision-Scalable-4x4-NPU)

---

## Additional Repositories & Academic Labs

| Repository Name | Domain | Primary Technology | Description & Contents |
| :--- | :--- | :--- | :--- |
| **[`FPGA-Digital-Design`](https://github.com/HARIKRUTHIK/FPGA-Digital-Design)** | Digital RTL / VLSI | Verilog, ModelSim, Cadence Virtuoso | Modular digital library: Adders (RCA, CLA, CSA, CSkipA, CSelectA), Multipliers, FIR, Sobel, RAM, FIFOs, and **CMOS 4-bit Transistor RCA**. |
| **[`IoT-Air-Quality-Monitoring-System`](https://github.com/HARIKRUTHIK/IoT-Air-Quality-Monitoring-System)** | Embedded / IoT | ESP32, MQ-2, BMP280, MicroSD, Blynk | Calibrated multi-protocol firmware, breadboard schematic, SD logger, and live hardware demonstration. |
| **[`FPGA-Real-Time-Audio-FFT-Classifier`](https://github.com/HARIKRUTHIK/FPGA-Real-Time-Audio-FFT-Classifier)** | FPGA / DSP | Cyclone IV, Intel 512-pt FFT IP | 48 kHz hardware acoustic streaming, magnitude calculation block, and 3-class acoustic classifier. |
| **[`Dipole-Antenna-Design-HFSS`](https://github.com/HARIKRUTHIK/Dipole-Antenna-Design-HFSS)** | RF / Electromagnetics | ANSYS HFSS, FEM, Python | 1 GHz half-wave dipole simulation ($S_{11} = -15.4\text{ dB}$), adaptive meshing, and analytical impedance solver. |

---

## Professional Experience & Key Training

**VLSI Design & Verification Intern** &nbsp;|&nbsp; Maven Silicon
- Authored synthesizable Verilog RTL for digital sub-blocks and Moore/Mealy FSM controllers.
- Executed functional verification and coverage analysis in ModelSim; achieved FPGA timing closure in Intel Quartus Prime.

**Technical Intern** &nbsp;|&nbsp; PlasmaGen Biosciences Pvt Ltd
- Programmed and validated industrial PLC automation routines and multi-channel sensor acquisition nodes.
- Conducted hardware-in-the-loop (HIL) calibration and signal reliability testing for manufacturing lines.

**RTL to GDSII (ASIC/FPGA Design Flow)** &nbsp;|&nbsp; VIT SENSE
- Completed 30-hour specialized value-added training covering synthesis, static timing analysis (STA), and physical layout verification.

**Pre-VDAT Hands-on VLSI Design** &nbsp;|&nbsp; Cadence Design Systems Workshop
- Conducted schematic capture, transient analysis, power-delay-product (PDP) optimization, and parasitic extraction in Cadence Virtuoso.

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
