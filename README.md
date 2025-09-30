## 🛩️ Aerodynamic and Stability Analysis of the Flying Wing Effect of Elevon Trim and Winglet Cant Angle Variation

⚠️ **Note:** All Results and figures in this repository are original work. Please **do not copy, distribute, or use** them without prior permission from the author 
📬 **How to reach me**: [📩 Mail](mailto:modake21@gmail.com) | [🔗 LinkedIn](https://www.linkedin.com/in/vrushal-modake-486a2b206/) . 

### 🎯 Objective  
To analyze and optimize the aerodynamic efficiency and stability of a **tailless flying wing aircraft** by studying the effect of variable **winglet cant angles** and **elevon trim adjustments**.  

---

### 🧪 Methodology  
- **Design & Geometry**: Flying wing UAV with variable winglet cant angles (5°, 30°, 60°, 90°).  
- **Simulation Tools**: CFD for aerodynamic performance, XFLR5 and MATLAB for stability analysis.  
- **Analysis Performed**:  
  - Aerodynamic efficiency (L/D ratio) at varying cant angles  
  - Longitudinal and lateral stability modes  
  - Root locus analysis for dynamic stability  
  - Trim condition recovery using elevon deflection  

---

### 📊 Results  
- **Low cant angles (5° & 30°):** Higher aerodynamic efficiency with **L/D up to 18.3**, but reduced lateral stability.  
- **High cant angles (60° & 90°):** Improved Dutch roll and spiral damping, but at the cost of higher drag.  
- **Elevon trimming:** Restored trim conditions across all winglet angles and stabilized Dutch roll at low cant angles.  
- **Spiral instability:** Persisted at 5° cant angle, showing inherent geometry-driven limitations.  
- **Longitudinal stability:** Short-period and phugoid modes remained stable across all cases.  

---

### 💬 Discussion  
- There is a clear **trade-off** between aerodynamic efficiency and lateral stability.  
- Lower cant angles favor **efficiency** but compromise **stability**, requiring control surface adjustments.  
- Higher cant angles enhance **stability**, but drag penalties reduce aerodynamic performance.  
- Elevon trimming proved effective in restoring trim and stability without redesigning wing geometry.  

---

### ✅ Conclusion  
The study demonstrates that **variable winglet positions** significantly impact the aerodynamic and stability characteristics of flying wing aircraft.  
- **Optimal compromise:** Cant angles around **30°–60°** offer a balance between aerodynamic efficiency and stability.  
- **Control integration:** Elevon trimming is an effective method to stabilize Dutch roll instabilities at lower cant angles.  
- The findings can guide UAV designers in selecting winglet configurations for specific mission requirements (efficiency vs. stability trade-offs).  

---

### 📎 Appendix  

### Figure 1: Flying Wing Geometry (mm)
  <img width="285" height="150" alt="Flyingwing" src="https://github.com/user-attachments/assets/5e54dbef-9ecd-4efb-9919-5f6b5f958b76" />
<img width="201" height="200" alt="Flying wing dim" src="https://github.com/user-attachments/assets/35b37d74-74b7-4a56-a2bd-da9235f30ae9" />
<img width="245.5" height="100" alt="Sidev" src="https://github.com/user-attachments/assets/636a45bf-c7aa-4d14-a26e-b607d2cd0001" />

### Figure 2: Effect on Aerodynamic Coefficients 
 <img width="374" height="200" alt="Clcdaoa" src="https://github.com/user-attachments/assets/92e77af6-d7f2-4eb8-8887-33b9ef01d89a" />
 <img width="374" height="200" alt="DCAOA" src="https://github.com/user-attachments/assets/eb329d46-b599-407a-92cb-8b89ffe75505" />
<img width="374" height="200" alt="CmAOA" src="https://github.com/user-attachments/assets/d0e8e797-96c9-457d-9b29-006109aa6618" />
<img width="374" height="200" alt="CMVSCCD" src="https://github.com/user-attachments/assets/3e1e037c-8a56-4401-a0d3-3e4570ca02c4" />

### Figure 3: Longitudinal Stability Root Locus  
<img width="675" height="200" alt="LongEgn" src="https://github.com/user-attachments/assets/c3bbb86d-eae7-4e09-b3ac-f8f3c9bbc108" />

### Figure 4: Lateral-Directional Stability Root Locus 
<img width="553" height="350" alt="Lategn" src="https://github.com/user-attachments/assets/d9f008c3-3e9f-4af4-8436-d02ac8bf02ec" />

--- 
