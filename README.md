# PiezoBud: A Piezo-Aided Secure Earbud with Practical Speaker Authentication
## Abstract
With the advancement of AI-powered personal voice assistants, speaker authentication via earbuds has become increasingly vital, serving as a critical interface between users and mobile devices. However, existing audio-based speaker authentication methods fail to defend against voice spoofing threats such as replay and deepfake attacks. To counteract these risks, we introduce PiezoBud, a pioneering multi-modal user authentication system that is truly practical and lightweight for earbuds. PiezoBud uses miniature piezoelectric sensors to detect micro-vibrations on the skin, extracting user-specific biometric data to authenticate legitimate access
on the local smartphone and protect against malicious attacks. Our exploratory study, involving 85 participants, demonstrates the effectiveness of PiezoBud in various everyday scenarios, including ambient noise, body movement, and in-ear media playing. Using only 15 seconds of enrollment data, PiezoBud achieves an Equal Error Rate (EER) of 1.05% and attain a mean authentication latency of 0.06 seconds on mobile devices. We also evaluate PiezoBud’s effectiveness in countering challenging adaptive attack scenarios and its overall performance in various real-world situations. Our evaluation highlights that PiezoBud stands out as a practical, resilient, responsive, and secure option for earbuds users.
## Contents
This directory contains the PCB design for PiezoBud. It includes 2 seperate boards: **main board** and **amplification board**. The PCB was designed by **[EasyEDA](https://easyeda.com/)**.
- EDA design files are in Materials.
- Fabrication output (Gerbers) are in Materials/Gerber. Suggested BOM lists are in Materials/BOM. Suggested pick and place files are in Materials/PickandPlace.
- Schematic PDF files can be found in Materials/Schematics.
  
**Errata**: The current design includes minor issues that can be improved in future revisions. While these do not impact functionality, they do affect robustness. Specifically, there is an impedance mismatch between the piezoelectric sensor and the amplifier chip. To enhance performance, consider using a matched piezo-amplifier pair.
## Hardware Setup
1. Go to **[EasyEDA](https://easyeda.com/)**
2. Upload files under EasyEDA.

![image](https://github.com/user-attachments/assets/fa35d608-f243-449d-b9be-b3ffddb6606e)


**Note**: We also provided materals compatible with **Altium**. However, due to the different file format and object design, the format translation has some differences, please check carefully at Altium Designer after imported. We are are not responsible for any loss of fabrication due to export differences.
