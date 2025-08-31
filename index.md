---
layout: page
title: "About me"
---

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<img src="{{ '/assets/img/me.jpg' | relative_url }}" alt="Enes Kasoglu" width="180" style="border-radius:12px;display:block;margin:0 auto 10px;" />

# Enes Kaşoğlu
Embedded & FPGA Engineer · Cologne, DE  

<p style="text-align:center;">
  <a href="mailto:enes@eneskasoglu.com"><i class="fas fa-envelope"></i> enes@eneskasoglu.com</a> · 
  <a href="https://www.linkedin.com/in/eneskasoglu" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a> · 
  <a href="https://github.com/eneskasoglu" target="_blank"><i class="fab fa-github"></i> GitHub</a>
</p>

<p style="text-align:center;">
  <a href="{{ '/assets/cv/Enes-Kasoglu-CV.pdf' | relative_url }}" class="btn btn-primary">
    📄 Download my CV
  </a>
</p>

---

I develop real-time embedded systems, FPGA and Linux-based solutions. My expertise covers **end-to-end development** (driver ↔ userspace integration), **low-latency video processing**, **Yocto/Buildroot**, **GStreamer**, **DMA**, and **CI/CD** pipelines.

> Focus: Zynq/ZU+ MPSoC, Spartan-7, Vitis/Vivado, device tree, U-Boot, kernel modules, userspace I/O (UIO).

---

## Experience
- **Embedded Software Engineer — Bertrandt (DE)** · *2023–present*  
  - Railway converter projects (e.g. B7 series **Aux-Converter**), automotive/rail validation & testing.  
  - **C/C++** (RTOS & Linux), **Python** test/tool scripts, **Git & JIRA** workflows, ASPICE-compliant development.  
  - Driver ↔ application integration on Embedded Linux, documentation, and on-site test support.

- **FPGA & Video Processing — Internship & R&D** · *2024–2025*  
  - **Spartan-7 SP701 + ADV7511**: MIPI input → basic PL processing → HDMI output pipeline experiments.  
  - **ZUBoard 1CG**: Tiny-YOLO based object detection PoC; low-latency optimizations (GStreamer + appsink).  
  - **Yocto/Buildroot** images, kernel configuration, DTS/overlay customization, user-space interfaces.

---

## Selected Projects
- **Low-Latency Video Pipeline (FPGA + Linux)**  
  Minimal PL-side image processing; PS-side GStreamer encode/display; buffer management and profiling/optimization for **<10–20 ms** target latency.
- **Userspace I/O (UIO) IP Control**  
  Register access to Vivado IPs from Linux userspace; simple CLI tool and Python wrapper.  
- **Yocto + GStreamer + OpenCV Integration**  
  Custom layer, package recipes, appsink-based frame capture, C++/Python demo apps.  
- **Test & Tool Scripts**  
  Python/Batch automation: log collection, measurement reporting, hardware-in-the-loop helpers.

---

## Technical Skills
**Languages:** C, C++, Python, Bash  
**FPGA/EDA:** Vivado/Vitis, HLS (basic), Verilog/VHDL (basic-intermediate)  
**Linux (Embedded):** Yocto, Buildroot, Device Tree, U-Boot, Kernel modules, systemd  
**Multimedia:** GStreamer (appsink/appsrc), v4l2, OpenCV  
**Tools:** Git, CMake, JIRA, Docker/Podman, VS Code, Markdown  
**Domains:** Low-latency video, DMA & memory mapping, driver-userspace bridges, ASPICE practices

---

## Education & Certifications (highlights)
- **Embedded Linux / Yocto** – Udemy (2023)  
- **C Programming** – Association of C and System Programmers (various terms)  
- **Python** – Association of C and System Programmers (2024)  
- **FreeRTOS / RTOS**, **Vivado Timing & VHDL** – Various trainings  
> Certificates/details available in CV.

---

## Community & Interests
FPGA-based video processing, industrial Linux systems, real-time systems, and **HW-SW co-design**. In free time: maker projects, Raspberry Pi, and open-source.

---

## 🌍 Languages
- 🇹🇷 **Türkçe**
- 🇬🇧 **English**
- 🇩🇪 **Deutsch**

---

## Contact
- <i class="fab fa-linkedin"></i> [linkedin.com/in/eneskasoglu](https://www.linkedin.com/in/eneskasoglu)  
- <i class="fab fa-github"></i> [github.com/eneskasoglu](https://github.com/eneskasoglu)  
- <i class="fas fa-envelope"></i> [enes@eneskasoglu.com](mailto:enes@eneskasoglu.com)
