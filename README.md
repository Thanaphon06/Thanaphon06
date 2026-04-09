![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif) Thanaphon Sithhimat
============================================================================================================================================

A dedicated Final-Year Information Technology student at King Mongkut's University of Technology North Bangkok (Prachinburi Campus). I possess a deep passion for programming and a logic-driven approach to complex problem-solaving. With over 1.5 years of combined internship and project-based experience in IoT, AI, and Software Development, I am highly focused and driven—often losing track of time when immersed in building innovative solutions and tackling technical challenges.

----------

* 🌍  I'm based in Thailand
* ✉️  You can contact me at [Thanaphons0602@gmail.com](mailto:Thanaphons0602@gmail.com)

## 🚀 Projects & Experience

### 🌳 1. Autonomous Carbon Stock Monitor (AI & IoT)
*An Integrated System for Precision Forestry & Environmental Monitoring*

- **Description:** พัฒนาระบบ และ อุปกรณ์วัดปริมาณการกักเก็บคาร์บอนในป่าชายเลนโดยใช้ YOLO Model ในการตรวจจับและวิเคราะห์ภาพต้นไม้เพื่อคำนวณมวลชีวภาพ (Biomass) อัตโนมัติ โดยทำงานร่วมกับโมดูลกล้อง Raspberry Pi HD-Camera และ Raspberry Pi 5 พร้อมทั้งอุปกรร์สามารถทำงานได้ตามเวลาที่กำหนดโดยใช้งาน esp32 และ relay ในการกำหนดการทำงานตามเวลา และ มีระบบไฟฟ้าจากโซล่าเซล และ แบตเตอร์รี่
- **Tech Stack:** <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/YOLOv11-00FFFF?style=flat-square&logo=ultralytics&logoColor=black" /> <img src="https://img.shields.io/badge/Raspberry%20Pi%205-C51A4A?style=flat-square&logo=raspberry-pi&logoColor=white" /> <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
- **Key Features:**
    - **Computer Vision:** ใช้ Python และ YOLOv11 บน Raspberry Pi 5 เพื่อตรวจจับชนิดต้นไม้และคำนวณเส้นผ่านศูนย์กลาง (DBH) เพื่อประมาณค่ามวลชีวภาพ (Biomass)
    - **Energy :** ออกแบบระบบพลังงานสะอาดด้วย Solar Cell และ Battery Storage ควบคุมการจ่ายไฟผ่าน ESP32 และ Relay Module ไปยัง Raspberry Pi 5
    - **Scheduled Automation:** ระบบตั้งเวลาการทำงานอัตโนมัติ (Deep Sleep/Wake-up) เพื่อการประหยัดพลังงาน
    - **Data Integration:** เชื่อมต่อและส่งข้อมูลวิเคราะห์ผ่าน FastAPI เพื่อการจัดเก็บข้อมูล

---

### 🧩 2. MicroBlocks Extensions & Hardware Tooling
*Custom Library Development for Educational IoT Ecosystem*

- **Description:** พัฒนาส่วนขยาย (Extensions) สำหรับแพลตฟอร์ม **MicroBlocks** เพื่อเพิ่มขีดความสามารถให้อุปกรณ์ IoT สำหรับสื่อการเรียนการสอน เพื่อควบคุม Hardware ผ่านการเขียนบล็อกคำสั่ง
- **Tech Stack:** <img src="https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /><img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" />
- **Key Features:**
    - **Hardware Control Logic:**พัฒนาชุดคำสั่งควบคุมอุปกรณ์ด้วย MicroPython และ C++ พร้อมออกแบบหน้า Block-based UI ด้วย JavaScript
    - **Reverse Engineering:** วิเคราะห์และแกะโครงสร้างโค้ดเดิม (Legacy Code) เพื่อนำมาพัฒนาต่อยอดและเพิ่มประสิทธิภาพการทำงานของ Library
    - **Embedded Mastery:** ปรับแต่ง Firmware สำหรับบอร์ด ESP32, ESP8266 และ Arduino ให้ทำงานร่วมกับสภาพแวดล้อมของ MicroBlocks
    - **Educational Innovation:** สร้างเครื่องมือที่เปลี่ยนโค้ดที่ซับซ้อนให้กลายเป็นบล็อกที่เข้าใจง่าย ช่วยให้ผู้เริ่มต้นเรียนรู้ IoT ได้รวดเร็วขึ้น
- **Repositories:**
    - [![BeetleCar Extension](https://img.shields.io/badge/BeetleCar_Ext-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Thanaphon06/beetlecar_extention)
    - [![Warp IoT Extension](https://img.shields.io/badge/Warp_IoT_Ext-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Thanaphon06/warp_IoT_extentionn)

---
## ⌚️ Free Time Project

### 📱 2. Daily Word Spark

- **Description:** พัฒนาแอปพลิเคชันเพื่อแก้ปัญหาการเรียนรู้คำศัพท์ภาษาอังกฤษ โดยรวบรวมคำศัพท์พื้นฐานที่สำคัญ 3,000 คำจาก **Oxford 3000™** มาไว้ในรูปแบบที่ฝึกฝนได้ง่ายในชีวิตประจำวัน
- ### 🛠️ Tech Stack & Languages
- ![TypeScript](https://img.shields.io/badge/TypeScript-98.2%25-3178C6?style=flat-square&logo=typescript&logoColor=white)
- ![CSS](https://img.shields.io/badge/CSS-1.1%25-1572B6?style=flat-square&logo=css3&logoColor=white)
- ![Other](https://img.shields.io/badge/Other-0.7%25-lightgrey?style=flat-square)
**ทักษะและเทคโนโลยีที่ได้เรียนรู้ (Skills & Learning):**
- **Modern Web & Mobile Development:** พัฒนาแอปพลิเคชันด้วย **React** และ **TypeScript** พร้อมเสริมประสิทธิภาพการแสดงผลด้วย **Tailwind CSS** และ **shadcn/ui**
- **Mobile Platform Integration:** เรียนรู้การใช้ **Capacitor** เพื่อแปลง Web Application ให้ทำงานบนระบบปฏิบัติการ **Android** 
- **Full-Stack Architecture:** ออกแบบโครงสร้างระบบที่รองรับการทำงานร่วมกับ **FastAPI (Backend)** และ **Firebase** สำหรับการจัดการข้อมูลผู้ใช้และระบบฐานข้อมูลคำศัพท์
- **Modern Tooling & Bundling:** ฝึกฝนการใช้ **Vite** เป็น Build Tool และการจัดการ Dependency ด้วย **Bun** เพื่อความรวดเร็วในการพัฒนาและส่งมอบซอฟต์แวร์

**Repository:** [![Daily Word Spark](https://img.shields.io/badge/Daily_Word_Spark-GitHub-181717?style=flat-square&logo=github)](https://github.com/Thanaphon06/daily-word-spark)

### 💻 **Languages & Core**
<p align="left">
<a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" alt="C" title="C" width="36" height="36" /></a>
<a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" alt="C++" title="C++" width="36" height="36" /></a>
<a href="https://docs.microsoft.com/en-us/dotnet/csharp/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/csharp-colored.svg" alt="C#" title="C#" width="36" height="36" /></a>
<a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" alt="Java" title="Java" width="36" height="36" /></a>
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" alt="Python" title="Python" width="36" height="36" /></a>
</p>

### 🌐 **Web & Backend Development**
<p align="left">
<a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" alt="HTML5" title="HTML5" width="36" height="36" /></a>
<a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" alt="CSS3" title="CSS3" width="36" height="36" /></a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" alt="React" title="React" width="36" height="36" /></a>
<a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/fastapi-colored.svg" alt="Fast API" title="Fast API" width="36" height="36" /></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" alt="MySQL" title="MySQL" width="36" height="36" /></a>
<a href="https://firebase.google.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/firebase-colored.svg" alt="Firebase" title="Firebase" width="36" height="36" /></a>
</p>

### 🔌 **Hardware & OS**
<p align="left">
<a href="https://store.arduino.cc/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/arduino-colored.svg" alt="Arduino" title="Arduino" width="36" height="36" /></a>
<a href="https://www.raspberrypi.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/raspberrypi-colored.svg" alt="Raspberry Pi" title="Raspberry Pi" width="36" height="36" /></a>
<a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" alt="Linux" title="Linux" width="36" height="36" /></a>
<a href="https://ubuntu.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/ubuntu-colored.svg" alt="Ubuntu" title="Ubuntu" width="36" height="36" /></a>
</p>

### 🛠️ **Tools & Design**
<p align="left">
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" alt="Git" title="Git" width="36" height="36" /></a>
<a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode-colored.svg" alt="VS Code" title="VS Code" width="36" height="36" /></a>
<a href="https://www.adobe.com/uk/products/photoshop.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/photoshop-colored-dark.svg" alt="Photoshop" title="Photoshop" width="36" height="36" /></a>
</p>
