<div align="center">

<a href="https://github.com/shafinDesigner">
  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=13&duration=2800&pause=1200&color=39D353&center=true&vCenter=true&width=600&lines=VLSI+Physical+Design+%7C+RTL-to-GDSII;Cadence+Genus+%E2%86%92+Innovus+%E2%86%92+Tempus+%E2%86%92+Voltus+%E2%86%92+Pegasus;SKY130+%C2%B7+OSU+45nm+%C2%B7+ASAP7+7nm;Clean+tape-out.+Every+time." alt="Typing SVG" />
</a>

<br/>

# SIAM AL SHAFIN

**VLSI Physical Design · RTL-to-GDSII · ASIC Implementation**

Final-year EEE @ [Islamic University of Technology](https://www.iutoic-dhaka.edu/), Gazipur · Bangladesh

<br/>

![](https://img.shields.io/badge/Cadence-Genus%20%7C%20Innovus%20%7C%20Tempus%20%7C%20Voltus%20%7C%20Pegasus-39d353?style=for-the-badge&labelColor=0d1117&color=39d353)
![](https://img.shields.io/badge/PDK-SKY130%20%C2%B7%20OSU45%20%C2%B7%20ASAP7-58a6ff?style=for-the-badge&labelColor=0d1117&color=58a6ff)
![](https://img.shields.io/badge/HDL-Verilog%20%7C%20TCL%20%7C%20Python-bc8cff?style=for-the-badge&labelColor=0d1117&color=bc8cff)

</div>

---

## `// signoff metrics`

| | |
|:---:|:---:|
| ![500 MHz](https://img.shields.io/badge/500_MHz-MAX_FREQ-39d353?style=for-the-badge&labelColor=161b22) | ![15,261 cells](https://img.shields.io/badge/15%2C261-STD_CELLS-58a6ff?style=for-the-badge&labelColor=161b22) |
| ![0 DRC](https://img.shields.io/badge/0-DRC_VIOLATIONS-bc8cff?style=for-the-badge&labelColor=161b22) | ![4 nodes](https://img.shields.io/badge/4-PROCESS_NODES-f0883e?style=for-the-badge&labelColor=161b22) |

---

## `// asic design flow`

```
RTL  →  GENUS  →  LEC  →  INNOVUS  →  TEMPUS  →  VOLTUS  →  PEGASUS  →  ✓ GDSII
       Synth     Conformal   P&R        STA      Power/IR    DRC/LVS     Tape-Out
```

---

## `// process nodes · PDKs`

| PDK | Node | Type |
|-----|------|------|
| 🟢 SkyWater SKY130 | 130nm | Open-source |
| 🔵 OSU FreePDK45 | 45nm | Academic |
| 🟣 ASAP7 | 7nm | Predictive |
| 🟠 gsclib045 | 45nm | Industrial |

---

## `// featured projects`

<details open>
<summary><b>🏆 Tiny GPU RTL-to-GDSII</b> — Full Cadence suite · 2026</summary>

<br/>

<div align="center">
  <img src="assets/TinyGPU_layout.png" alt="Tiny GPU GDSII Layout — 222 MHz · 15,261 cells · 241×237 µm · 0 DRC violations" width="80%"/>
</div>

<br/>

> Complete RTL-to-GDSII ASIC implementation of an open-source Tiny GPU design.
> Achieved a clean Conformal LEC pass after RTL optimization, resolving equivalence issues in the reference design.
>
> **Flow:** Logic Synthesis → LEC → Floorplanning → Placement → CTS → Routing → ECO Timing Closure → STA → DRC/LVS/Antenna → GDSII

![222 MHz](https://img.shields.io/badge/222_MHz-Frequency-39d353?style=flat-square&labelColor=161b22)
![15261 cells](https://img.shields.io/badge/15%2C261-Std_Cells-39d353?style=flat-square&labelColor=161b22)
![241x237](https://img.shields.io/badge/241×237_µm-Die_Area-39d353?style=flat-square&labelColor=161b22)
![8 metal](https://img.shields.io/badge/8-Metal_Layers-39d353?style=flat-square&labelColor=161b22)
![WNS](https://img.shields.io/badge/WNS_+0.054_ns-Setup-39d353?style=flat-square&labelColor=161b22)
![0 DRC](https://img.shields.io/badge/0_DRC_·_0_LVS_·_0_Antenna-Clean_Signoff-39d353?style=flat-square&labelColor=161b22)

</details>

<details>
<summary><b>⚡ Tiny GPU Multi-Node Synthesis</b> — ASAP7 7nm + OSU 45nm · 2026</summary>

<br/>

> Synthesized the Tiny GPU across 7nm (ASAP7) and 45nm (OSU) to compare PPA scaling — 22× area reduction at 7nm.

![500 MHz](https://img.shields.io/badge/500_MHz-7nm_Freq-bc8cff?style=flat-square&labelColor=161b22)
![+262 ps](https://img.shields.io/badge/+262_ps-Slack-bc8cff?style=flat-square&labelColor=161b22)
![1284 um2](https://img.shields.io/badge/1%2C284_µm²-Area_@_7nm-bc8cff?style=flat-square&labelColor=161b22)
![1.7 mW](https://img.shields.io/badge/1.7_mW-Power-bc8cff?style=flat-square&labelColor=161b22)
![22x area](https://img.shields.io/badge/22×-Area_Reduction-bc8cff?style=flat-square&labelColor=161b22)

</details>

<details>
<summary><b>🔬 8-Bit Counter — Full Cadence Suite</b> — RTL-to-GDSII + Power Analysis · 2026</summary>

<br/>

> Complete flow on 45nm gsclib045: Xcelium simulation → Genus synthesis + DFT scan → Conformal LEC → Innovus P&R → Tempus STA → Voltus power/IR drop → GDSII.

![5 mW](https://img.shields.io/badge/5_mW-Total_Power-f0883e?style=flat-square&labelColor=161b22)
![IR drop](https://img.shields.io/badge/0.0017%25-IR_Drop-f0883e?style=flat-square&labelColor=161b22)
![WNS](https://img.shields.io/badge/WNS_+8.313_ns-Setup-f0883e?style=flat-square&labelColor=161b22)
![92%](https://img.shields.io/badge/92.31%25-Code_Coverage-f0883e?style=flat-square&labelColor=161b22)
![0 DRC](https://img.shields.io/badge/0-DRC_Violations-f0883e?style=flat-square&labelColor=161b22)

</details>

<details>
<summary><b>🖥 PicoRV32 RISC-V CPU RTL-to-GDSII</b> — 45nm · 2026</summary>

<br/>

> PicoRV32 RISC-V CPU through full RTL-to-GDSII using 45nm ASIC process node.

![Genus](https://img.shields.io/badge/Genus-Synthesis-58a6ff?style=flat-square&labelColor=161b22)
![Innovus](https://img.shields.io/badge/Innovus-P%26R-58a6ff?style=flat-square&labelColor=161b22)
![45nm](https://img.shields.io/badge/OSU-45nm-58a6ff?style=flat-square&labelColor=161b22)
![GDSII](https://img.shields.io/badge/GDSII-✓_Signoff-58a6ff?style=flat-square&labelColor=161b22)

</details>

<details>
<summary><b>🔷 32-bit ALU RTL-to-GDSII</b> — SkyWater SKY130 · 2026</summary>

<br/>

> 32-bit ALU through full RTL-to-GDSII using Cadence Innovus on the SkyWater SKY130 130nm open-source PDK.

![SKY130](https://img.shields.io/badge/SkyWater-SKY130-39d353?style=flat-square&labelColor=161b22)
![130nm](https://img.shields.io/badge/Process-130nm-39d353?style=flat-square&labelColor=161b22)
![GDSII](https://img.shields.io/badge/GDSII-✓_Signoff-39d353?style=flat-square&labelColor=161b22)

</details>

<details>
<summary><b>🧮 8051 Full-Expression Calculator</b> — AT89C51 Assembly · 2024</summary>

<br/>

> Full expression calculator in 8051 assembly supporting operator precedence, brackets, and memory. 4×4 keypad + LCD display on AT89C51.

![AT89C51](https://img.shields.io/badge/AT89C51-Microcontroller-58a6ff?style=flat-square&labelColor=161b22)
![Assembly](https://img.shields.io/badge/8051-Assembly-58a6ff?style=flat-square&labelColor=161b22)
![LCD](https://img.shields.io/badge/4×4_Keypad-LCD_Display-58a6ff?style=flat-square&labelColor=161b22)

</details>

---

## `// technical skills`

**Cadence EDA**

`Genus` `Innovus` `Tempus` `Voltus` `Conformal LEC` `Xcelium` `Pegasus`

**Hardware Description & Scripting**

`Verilog` `TCL` `Python` `C` `C++` `8051 Assembly`

**Open-Source VLSI**

`OpenLane` `Qflow` `SKY130 PDK` `ASAP7`

**Simulation & EDA**

`MATLAB` `Simulink` `Proteus` `Linux`

---

## `// github stats`

<div align="center">

<a href="https://github.com/shafinDesigner">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=shafinDesigner&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&icon_color=58a6ff&text_color=c9d1d9&ring_color=39d353" />
</a>
<a href="https://github.com/shafinDesigner">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shafinDesigner&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=c9d1d9&langs_count=6" />
</a>

</div>

---

## `// connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siam_Al_Shafin-58a6ff?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://www.linkedin.com/in/siam-al-shafin-0175bb395)
[![GitHub](https://img.shields.io/badge/GitHub-shafinDesigner-39d353?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/shafinDesigner)
[![Email](https://img.shields.io/badge/Email-shafiniutian@icloud.com-f0883e?style=for-the-badge&logo=apple&logoColor=white&labelColor=0d1117)](mailto:shafiniutian@icloud.com)

<br/>

![](https://img.shields.io/badge/●_Open_to-VLSI_/_ASIC_Internships_&_Research_·_2026-39d353?style=flat-square&labelColor=0d1117)

<br/>

<sub><code>IUT · Gazipur, Bangladesh</code></sub>

</div>
