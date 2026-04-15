# 🔬 OTA Design using MOSFET (LTspice)

## 📌 Overview

This project presents the design of a **basic Operational Transconductance Amplifier (OTA)** using MOSFET differential pair and current mirror load.

---

## ⚙️ Specifications

* VDD = +2.5V, VSS = -2.5V
* Load Capacitance: 5 pF
* Target Gain: 10⁴
* Slew Rate ≥ 15 V/µs
* Bandwidth ≥ 200 kHz
* Power Dissipation ≤ 1 mW

---

## 📊 Results

### 🔹 DC Operating Point

* Vout ≈ 0.82 V
* All transistors in saturation region

### 🔹 Gain & Frequency Response

* Gain ≈ 100 dB (low frequency)
* Bandwidth in MHz range

### 🔹 Slew Rate

* SR ≈ 30 V/µs

### 🔹 ICMR

* Linear operating region identified via Vcm sweep

---

## ⚡ Key Equations

* SR = Ibias / CL
* Av = gm × ro

---

## 🧪 Simulations Included

* DC Operating Point (.op)
* AC Analysis (Bode Plot)
* Transient Analysis (Slew Rate)
* Vcm Sweep (ICMR)

---

## 📎 Report

See full analysis:

📄 `report/OTA_Design.pdf`

---

## 👨‍💻 Author

Murat Emre Demirci
