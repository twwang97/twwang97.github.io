---
title: "VTS-1200"
excerpt: "Vecow VTS gPTP time sync<br/>"
collection: fpga
---
We ported ROS2 Humble gPTP time sync into PetaLinux using a meta‑ros layer, so the timers across different devices such as cameras and LiDAR were synchronized. This [report](http://twwang97.github.io/files/report_vecow_vts_simple.pdf) demonstrated how both stereo depth camera and 32-thread LiDAR synchronize their timers with our VTS series.