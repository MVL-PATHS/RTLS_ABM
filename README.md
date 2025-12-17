# Agent-Based Modeling of Clostridioides difficile Transmission in a Hospital Using Real-Time Location System (RTLS) Movement Data
## Citation: If you use this model, please cite associated publication:
> Ravi Chandra Thota, Yusuf Sarwar Uddin, Majid Bani-Yaghoub, Mohamed Nezar Abourraja, Gary Sutkin, and Susanna Paschal. 2025. Enhancing Agent-Based Models with Real-Time Movement Data to Assess Impacts of Biosecurity Interventions on Disease Exposure in Healthcare Settings. Proceedings of the 16th ACM International Conference on Bioinformatics, Computational Biology, and Health Informatics. Association for Computing Machinery, New York, NY, USA, Article 16, 1–10. https://doi.org/10.1145/3765612.3767222

---

This repository contains an **AnyLogic agent-based model (ABM)** that uses **Real-Time Location System (RTLS) movement data** of healthcare workers and medical devices to simulate the transmission of **Clostridioides difficile (C. difficile)** in a hospital environment. RTLS provides time-stamped location trajectories that drive agent movement and interaction logic in the model.

---

## Input Data:
The model uses an RTLS input file named Hospital Data.csv. This file contains the columns tagId, time, type, x1, and y1. The tagId uniquely identifies each tracked entity, while time records the timestamp of each location update. The type column indicates the agent category associated with each tag, such as healthcare worker roles (for example, nurse or doctor) or medical devices. The x1 and y1 columns store spatial coordinates, which are used to drive agent movement and determine interactions within the simulation.

