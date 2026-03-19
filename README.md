# 🔊 Ultrasonic Acoustic Levitation using Arduino

A small experimental project that demonstrates **acoustic levitation** using ultrasonic sound waves.  
By generating a **40 kHz standing wave** between two facing ultrasonic transducers, a tiny thermocol bead can be suspended in mid-air.

No magnets. No airflow.  
Just **sound waves creating acoustic pressure strong enough to counter gravity.**

---

## 🚀 Project Overview

This project explores the fascinating physics of **standing waves and acoustic pressure**.

Two ultrasonic piezoelectric transducers are placed facing each other. When driven at their resonant frequency (~40 kHz), they create a **standing wave pattern** between them.

At specific points called **nodes**, the acoustic pressure stabilizes small lightweight objects like thermocol beads, causing them to **levitate in mid-air**.

---

## ⚡ Features

- 🔊 Acoustic levitation using **40 kHz ultrasonic waves**
- 🎯 Stable levitation at **standing wave nodes**
- 💻 Controlled using **Arduino**
- ⚡ Powered through **L298 motor driver**
- 🧩 Built using **salvaged ultrasonic sensor transducers**
- 🔬 Demonstrates **practical physics and wave behavior**

---

## 🧰 Components Used

| Component | Description |
|-----------|-------------|
| Arduino | Generates the 40 kHz driving signal |
| Ultrasonic Piezo Transducers | Salvaged from ultrasonic distance sensors |
| L298 Driver Module | Amplifies signal to drive transducers |
| Custom PCB / Motherboard | Used to mount the components |
| Thermocol Bead | Lightweight object for levitation |
| Power Supply | Provides power to the driver circuit |

---

## ⚙️ Working Principle

The system works by generating **ultrasonic standing waves**.

1. Arduino generates a **40 kHz signal**.
2. The signal is amplified using the **L298 driver**.
3. Two facing **piezoelectric transducers** emit ultrasonic waves.
4. The waves interfere and form a **standing wave pattern**.
5. At specific points (nodes), **acoustic pressure traps lightweight objects**.

The distance between nodes is approximately **half the wavelength**, which is around **4 mm for 40 kHz sound waves in air**.

---

## 🔌 System Architecture

```
Arduino
   │
   │ 40 kHz Signal
   ▼
L298 Driver
   │
   │ Amplified Signal
   ▼
Ultrasonic Transducers (Facing Each Other)
   │
   ▼
Standing Wave Field
   │
   ▼
Levitation Node (Thermocol Bead Floats)
```

---

## 🛠️ Build Steps

1. Remove **piezoelectric transducers** from ultrasonic sensors.
2. Mount them on a **custom PCB or support frame** facing each other.
3. Connect the transducers to the **L298 driver module**.
4. Use an **Arduino to generate a 40 kHz signal**.
5. Power the system and adjust the **distance between transducers (~4 mm node spacing)**.
6. Carefully place a **small thermocol bead** at a node to observe levitation.

---

## 💡 Key Learnings

- Understanding **standing wave formation**
- Importance of **resonant frequency for piezo transducers**
- Practical demonstration of **acoustic radiation pressure**
- Precision in **transducer alignment and spacing**

---

## 🚀 Future Improvements

- Add **multiple transducers for stronger levitation**
- Implement **automatic frequency tuning**
- Design a **3D printed levitation frame**
- Add **adjustable node control**

---

## 📌 Applications

- Physics demonstrations
- Acoustic manipulation research
- Particle trapping experiments
- Educational engineering projects

---

## 🤝 Contribution

Contributions, suggestions, and improvements are welcome.

If you like this project, consider **starring the repository ⭐**.

---
