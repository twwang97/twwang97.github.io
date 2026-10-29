---
title: "gPTP Time Sync with FPGA (Vecow)"
excerpt: "PetaLinux<br/>"
collection: fpga
---

<!-- VTS-1200 at Vecow -->

We ported ROS2 Humble gPTP time sync into PetaLinux using a meta‑ros layer, so the timers across different devices such as cameras and LiDAR were synchronized. This [report](/files/report_vecow_vts_simple.pdf) demonstrated how both stereo depth camera and 32-thread LiDAR synchronize their timers with our VTS series.