# 🖥️ RISC-V Reference SoC Tapeout Program VSD

![RISC-V](https://img.shields.io/badge/RISC-V-VSD-blue) ![Participants](https://img.shields.io/badge/Participants-India-orange) ![India](https://img.shields.io/badge/Made%20in-India-green)

## Welcome to my journey through the SoC Tapeout Program VSD!
This repository documents my week-by-week progress with tasks inside each week.

## 📑 Table of Contents
1. [System Requirements](#-system-requirements)
2. [Setup Instructions](#-setup-instructions)
   - [Update Packages](#1️⃣-update-packages)
   - [Yosys Installation](#2️⃣-yosys-installation)
   - [Icarus Verilog Installation](#3️⃣-icarus-verilog-installation)
   - [GTKWave Installation](#4️⃣-gtkwave-installation)
3. [Notes](#-notes)

---

## 🖥️ System Requirements
- Ubuntu 20.04 or higher  
- 6 GB RAM  
- 50 GB HDD  
- 4 vCPU  

---

## ⚙️ Setup Instructions

### 1️⃣ Update Packages
```bash
sudo apt update
sudo apt install build-essential dkms linux-headers-$(uname -r)



1️⃣ Yosys Installation
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
<img width="753" height="181" alt="Screenshot from 2025-09-20 12-22-47" src="https://github.com/user-attachments/assets/4edbbf42-3ea2-403c-9001-b15fc97489da" />







2️⃣ Icarus Verilog Installation

sudo apt-get update

sudo apt-get install iverilog

<img width="721" height="424" alt="Screenshot from 2025-09-20 12-23-10" src="https://github.com/user-attachments/assets/ac14c44e-e623-4103-9e44-c9db131cf37d" />


3️⃣ GTKWave Installation

sudo apt-get update

sudo apt install gtkwave

<img width="724" height="417" alt="Screenshot from 2025-09-20 12-23-35" src="https://github.com/user-attachments/assets/60b44559-524a-4409-a147-5a27a103149d" />




