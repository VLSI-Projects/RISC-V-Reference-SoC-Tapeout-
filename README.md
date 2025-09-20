# RISC-V-Reference-SoC-Tapeout
# VLSI Tool Installation Repository

This repository provides **step-by-step installation guidelines** and **automation scripts** for setting up open-source VLSI tools.  
It is designed to help students, researchers, and chip designers quickly set up their environment for RTL-to-GDS flows.

---


---

## 🛠️ Tools Covered
- **Yosys** – Open-source synthesis tool  
- **Icarus Verilog** – Verilog simulation tool  
- **GTKWave** – Waveform viewer  
- **Ngspice** – SPICE circuit simulator  
- **Magic** – VLSI layout tool  
- **OpenLANE** – RTL-to-GDSII flow  

---

## ⚙️ System Requirements
- **OS:** Ubuntu 20.04+  
- **RAM:** 6 GB minimum  
- **Disk:** 50 GB free  
- **CPU:** 4 vCPUs  

---
## RUN System Check

cat system_check.md

##  Install tools

Navigate to the setup folder and run the script of your choice, e.g.:

cd setup
bash install_yosys.sh

## Verify installation

After installation, verify by running:

yosys -V
iverilog -V
gtkwave -h
ngspice -v
magic -v
docker --version   # for OpenLANE

## 📑 References

VirtualBox

Yosys GitHub

OpenLANE GitHub

GTKWave

Ngspice

Magic VLSI


