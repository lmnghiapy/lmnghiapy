<div align="center">

<!-- ===================== BANNER ===================== -->

<img src="./assets/sakura.gif" width="50%" alt="sakura banner"/>

<br><br>

<table>
<tr>

<td width="5%" align="center">
  <img src="./assets/vivian.gif" width="100">
</td>

<td width="60%" align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=34&duration=2500&pause=900&color=2788F7&center=true&vCenter=true&width=700&lines=Welcome+To+My+GitHub;Hi%2C+I'm+Le+Minh+Nghia;Computer+Engineering+Student" />

</td>

<td width="5%" align="center">
  <img src="./assets/vivian.gif" width="100">
</td>

</tr>
</table>

</div>

## 🪨 System Architecture & Profile

### ⚡ Hello, World! I'm Le Minh Nghia

🏫 **Computer Engineering Undergraduate @ UIT - VNUHCM** 🌐  
📍 Base of Operations: **Ho Chi Minh City, Vietnam**

🛰️ **Core Competencies:**

- 🔹 **RTL Design** — Verilog, SystemVerilog, synthesizable datapaths, FSMs
- 🧪 **Design Verification** — Testbenches, functional simulation, waveform debugging
- 🔐 **Hardware Cryptography** — AES-256 architecture and pipelined implementation
- 🖼️ **Image Processing Hardware** — Streaming image pipelines and hardware filtering
- 🏗️ **Computer Architecture** — Datapaths, control logic, and digital system design
- 🐍 **Hardware-Software Co-Simulation** — Python automation and file-I/O verification

<br>

🔭 **Current Trajectory:**

![RTL](https://img.shields.io/badge/◆_Hardware-RTL_Design-3B82F6?style=flat-square)
![DV](https://img.shields.io/badge/⚗_Verification-DV-7C3AED?style=flat-square)
![ASIC](https://img.shields.io/badge/◢_Front--End-ASIC-475569?style=flat-square)
![FPGA](https://img.shields.io/badge/⚡_FPGA-Design-2563EB?style=flat-square)

---

## 🧰 The Tech Arsenal

### ▼ ⌨️ Languages & HDLs

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/VERILOG-005A8D?style=for-the-badge)
![SystemVerilog](https://img.shields.io/badge/SYSTEMVERILOG-6D28D9?style=for-the-badge)
![Tcl](https://img.shields.io/badge/TCL-1F6FEB?style=for-the-badge)
![Assembly](https://img.shields.io/badge/ASSEMBLY-6B4F1D?style=for-the-badge)

<br>

### ▼ 🏗️ EDA & FPGA Toolchains

![Vivado](https://img.shields.io/badge/XILINX_VIVADO-243B53?style=for-the-badge)
![ModelSim](https://img.shields.io/badge/MODELSIM-005A9C?style=for-the-badge)
![Quartus](https://img.shields.io/badge/INTEL_QUARTUS-0071C5?style=for-the-badge)
![Synopsys](https://img.shields.io/badge/SYNOPSYS_CUSTOM_COMPILER-6D28D9?style=for-the-badge)
![Cadence](https://img.shields.io/badge/CADENCE_EDA-E31837?style=for-the-badge)

<br>

### ▼ 💻 Platforms & Development

![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/WINDOWS-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🚀 Engineered Solutions

<table>

<tr>

<td width="50%" valign="top">

### 🔐 Hardware Cryptography

#### AES-256 Encryption Engine

Designed a **14-round pipelined AES-256 cryptographic core** in Verilog with on-the-fly key expansion.

Achieves sustained processing of **one 128-bit block per cycle after initial pipeline latency**.

Verified against **NIST FIPS-197 test vectors** and synthesized in Vivado targeting a **265 MHz Fmax on Virtex-7**.

<br>

![Verilog](https://img.shields.io/badge/Verilog-005A8D?style=flat-square)
![Vivado](https://img.shields.io/badge/Vivado-FPGA-1D4ED8?style=flat-square)
![AES](https://img.shields.io/badge/AES--256-Cryptography-334155?style=flat-square)

<br>

[**View Project →**](https://github.com/lmnghiapy/AES_256_Pipeline)

</td>

<td width="50%" valign="top">

### 🖼️ Image Processing Hardware

#### Hardware Median Filter Processor

Implemented a **loop-free median filter core** in Verilog for real-time salt-and-pepper noise reduction.

Replaced iterative behavioral loops with **parallel comparison logic** for synthesizable RTL implementation.

Verified with **ModelSim + Python image streaming**, achieving:

- **PSNR: 33.24 dB**
- **SSIM: 0.9608**

<br>

![Verilog](https://img.shields.io/badge/Verilog-005A8D?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-Simulation-2563EB?style=flat-square)
![Python](https://img.shields.io/badge/Python-CoSim-3776AB?style=flat-square)

<br>

[**View Project →**](https://github.com/lmnghiapy/Salt-and-pepper-noise)

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🎨 RTL Image Pipeline

#### RGB to Grayscale + Brightness Adjust

Designed an RTL datapath converting **24-bit RGB pixel streams into 8-bit grayscale** using fixed-point arithmetic.

Implemented signed brightness adjustment with **hardware saturation clamping** to keep pixel values within `0–255`.

Validated using **2048 × 1365 image streams** through ModelSim and Python verification scripts.

<br>

![Verilog](https://img.shields.io/badge/Verilog-005A8D?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-Simulation-2563EB?style=flat-square)
![Python](https://img.shields.io/badge/Python-Verification-3776AB?style=flat-square)

<br>

[**View Project →**](https://github.com/lmnghiapy/RGB_To_Grayscale_With_Brightness_Adjust)

</td>

<td width="50%" valign="top">

### 🧪 Design Verification

#### RTL Verification Workflow

Building verification experience through:

- Functional testbenches
- Waveform debugging
- Python-based golden-model comparison
- File-I/O co-simulation
- RTL simulation and validation

<br>

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-DV-7E22CE?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-Simulation-1D4ED8?style=flat-square)
![Python](https://img.shields.io/badge/Python-Automation-3776AB?style=flat-square)

</td>

</tr>

</table>

---

## 🎓 Education

**University of Information Technology (UIT) - VNUHCM**

B.Eng. in **Computer Engineering**  
Expected Graduation: **July 2027**

**Cumulative GPA: 8.75 / 10.0**

🏅 Academic Excellence Scholarship  
Semester 1 & Semester 2 — Year 1

---

## 📚 Publication

### International Conference on Smart Learning Technologies — ICSLT 2026

**Co-author**

*"The Impact of Short-Form Video Platforms’ Infinite Scrolling on Reduced Concentration and Academic Procrastination Among University Students in Viet Nam."*

Accepted for oral presentation and publication in **Springer's Lecture Notes in Networks and Systems**.

---

## 📈 Engineering Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=lmnghiapy&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lmnghiapy&layout=compact&hide_border=true" />

</div>

---

## 📬 Transmission Channels

<div align="center">

<a href="mailto:lmnghiapy@gmail.com">
<img src="https://img.shields.io/badge/EMAIL_ME-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<!-- THAY LINKEDIN_URL bằng link LinkedIn thật của m -->
<a href="LINKEDIN_URL">
<img src="https://img.shields.io/badge/LINKEDIN_NETWORK-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/lmnghiapy">
<img src="https://img.shields.io/badge/GITHUB_PROFILE-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

<div align="center">

`RTL Design` • `Design Verification` • `Digital Logic` • `FPGA`

### From algorithms to gates.

</div>
