---
title: "Multiple GMSL Cameras with FPGA (Vecow)"
excerpt: "Vivado and Vitis<br/>"
collection: fpga
---

<!-- VE-1008 at Vecow -->

We developed some VHDL in Vivado and architected a Vitis pipeline to program our Zynq UltraScale+ MPSoC for deterministic multi‑camera streaming. This [report](http://twwang97.github.io/files/report_vecow_ve1008_simple.pdf) demonstrated the multi‑camera streaming and added a block RAM for data verification.

D‑PHY toggles between low‑power and high‑speed modes and is the foundation for reliable CSI‑2 links; physical‑layer issues will always mask as higher‑layer failures if not resolved first. What to prove before moving to CSI‑2: signal integrity, lane alignment, clock recovery, and LP/HS mode transitions. So I wrote a Verilog testbench to mirror a 4-lane MIPI camera and tested our CSI-2 receiver, and such a simulation was well-documented in this [report](http://twwang97.github.io/files/report_dphy_testbench_vivado.pdf).