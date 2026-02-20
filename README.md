# EC-mini-projects

1. Designing a Center-Tapped Full-Wave Rectifier to obtain a 6V DC average output with a 200mA current rating, including capacitive filtering.
The objective was not only to obtain the required average DC output, but also to ensure proper ripple reduction, stable operation under load, and controlled current limiting.
The design involved a 230V–12V center-tapped 606 transformer, full-wave rectification using 1N4007 diodes, capacitor-based filtering, and a BJT-based series pass regulator with emitter current sensing for limiting the load current to approximately 200mA. Particular attention was given to reference stability, transistor biasing, ripple behavior, and practical trade-offs between regulation and efficiency.
Through LTspice simulation, the circuit was verified for average output voltage (6V), ripple characteristics under load, and current limiting behavior near the specified rating. This project significantly strengthened my understanding of linear regulation techniques, zener reference loading effects, and practical current control using discrete components.
Looking forward to implementing the hardware prototype and further refining the design in the lab.
🎯 Specifications Achieved:
✔ Average output ≈ 6V DC
✔ Load current limited ≈ 200mA
✔ Controlled ripple under load
✔ Stable operation across cycles
✔ Proper biasing and symmetrical behavior
Waveform analysis confirmed:
Output ripple behavior
Current limiting near 200mA
Stable regulation under resistive load
