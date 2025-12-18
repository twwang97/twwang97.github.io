---
title: "4-bit Counter: Circuit Simulator and FPGA Implementation"
excerpt: "Simulation of circuit behavior in LTspice and FPGA implementation of a 4-bit counter with J-K flip-flops and a two-stage synchronizer<br>"
collection: fpga
---

* This [GitHub repo](https://github.com/twwang97/altera-de2-115.git) not only analyzes LTspce behavior simulation but also provides testbenches based on both ModelSim and XSim. Besides, the counter design are implemented both in Altera DE2 ([video](https://youtu.be/KPDtDhJqPgE)) and Diligent Basys3 ([video](https://youtu.be/lHUYbL7JJKo)).
  * Designed a 4-bit counter using J-K FFs in LTspice with an R-2R D/A converter and ran simulation.
  * Implemented a 4-bit counter in VHDL, synthesized with Quartus, and verified such a design using ModelSim testbenches.
  * Developed a two-stage synchronizer to debounce the pushbutton and demonstrated real‑time operation with 7‑segment display on (1) Intel Altera DE2-115 and (2) Diligent Basys 3.
  * External Link: [GitHub](https://github.com/twwang97/altera-de2-115/tree/nycu2025/4bit-counter-jkff), [Report](http://twwang97.github.io/files/report_fpga_4bit_counter.pdf), [YouTube](https://youtu.be/lHUYbL7JJKo)