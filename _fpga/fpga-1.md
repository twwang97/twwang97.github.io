---
title: " Real‑time Edge Detection on Basys 3 using an OV7670 Camera and VGA Output"
excerpt: "Built a real‑time image processing pipeline in Verilog to capture camera frames from an OV7670, perform edge detection, and display results over VGA on a Basys 3 board using Vivado 2025.2.<br/><img src='/images/fpga_vga_display.jpg'>"
collection: fpga
---

This project implements **real‑time edge detection** on a Digilent Basys‑3 FPGA using an OV7670 camera and VGA output; the [repository](https://github.com/twwang97/edge-detection-basys3-ov7670-vga) includes Vivado project files, RTL, and build scripts.

- **Designed and implemented**: Implemented a real‑time Sobel/edge detection pipeline in synthesizable Verilog on a Basys‑3 FPGA, processing live OV7670 camera frames and driving VGA output.  
- **Optimized for timing and resource use**: Reduced logic utilization and met 25–50 MHz timing constraints by pipelining pixel operations and balancing BRAM/FF usage; enabled stable VGA refresh rates.  
- **Integrated camera interface**: Developed OV7670 configuration and parallel pixel capture modules (SCCB/I2C control + pixel clock domain crossing) to reliably ingest 640×480 (or scaled) frames.  
- **Automated build and deployment**: Wrote Vivado TCL scripts to create the project, synthesize, implement, and generate bitstream for rapid iteration and reproducible demos.  
- External Link: [GitHub Repo](https://github.com/twwang97/edge-detection-basys3-ov7670-vga) and [YouTube Video](https://youtu.be/Ro8rp9voRJ4?t=93)