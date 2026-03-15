# ⚡ 5V Regulated DC Power Supply

A simple hardware project that converts **230V AC mains supply into a stable 5V DC output** using a transformer, bridge rectifier, filter capacitors, and a **7805 voltage regulator**.

This power supply can be used for **charging small devices, powering microcontrollers, and running low-voltage electronic circuits**.

---

## 📌 Project Overview

### 📷 Project Images

| Hardware Setup | Circuit Diagram |
|----------------|----------------|
| ![Project](images/project.jpg) | ![Circuit](images/circuit.png) |

Most electronic devices require a **stable DC voltage**, while the electricity supplied in homes is **AC**.
This project demonstrates the fundamental process of **AC to DC conversion and voltage regulation** using basic electronic components.

The circuit performs three major operations:

* **Step-down transformation** of high voltage AC
* **Rectification** of AC into DC
* **Filtering and regulation** to produce a stable 5V output

---

## ⚙️ Components

All components used in this project are listed here:

➡️ See **[Components List](components.md)**

---

## 🔧 Working Principle

### 1. Step-Down Transformation

A step-down transformer reduces the **230V AC mains voltage** to a lower AC voltage suitable for electronic circuits.

### 2. Rectification

A **bridge rectifier** made of four diodes converts the AC signal into **pulsating DC**.

### 3. Filtering

Capacitors smooth the pulsating DC signal by **reducing ripple voltage**.

### 4. Voltage Regulation

The **7805 voltage regulator** maintains a **constant 5V DC output** even if the input voltage fluctuates slightly.

### 5. Output Monitoring

A **digital voltmeter** is used to display the output voltage.

---

## 🔌 Applications

This power supply can be used for:

* Mobile phone charging
* Powering microcontroller circuits
* Embedded system prototypes
* Small electronic devices
* USB powered gadgets

---

## 🚀 Future Improvements

Possible enhancements for the project:

* Add a **USB charging port**
* Implement **overcurrent protection**
* Add **adjustable voltage output**
* Design a **PCB instead of a vero board**
* Integrate **battery backup**

---


## 👩‍💻 Author

**Anshika Jain**
BTech Student | Electronics Enthusiast


