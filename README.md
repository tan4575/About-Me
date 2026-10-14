# About-Me

**Wei Siang Tan — Building AI from model to metal**

Senior Software & Machine Learning Engineer · Edge AI · Computer Vision · Embedded Systems · Full-Stack

This repository hosts my interview presentation as a single self-contained web page ([index.html](index.html)). Open it in any browser to view the slides.

## About me

A physics researcher turned engineer. I take AI from model to metal, building systems that run on real hardware for Dyson, Thermo Fisher, Jabil and Toshiba.

- 8+ years shipping production software and firmware
- 2 Master's degrees: NUS and WIU Physics
- 5 publications, including ApJ and MNRAS

## Career journey

| Year | Company | Focus |
| ---- | ------- | ----- |
| 2018 | Exclusive Master | Vision-guided robotics |
| 2019 | Toshiba TEC | Printer firmware & web panel |
| 2020 | Thermo Fisher Scientific | Project lead, diagnostics firmware |
| 2023 | Scooterson | EV IoT firmware, DSP & cloud |
| 2023 | Dyson | Edge ML, NPU & kernel drivers |
| 2025 | Jabil | Lead, optical transceiver firmware |
| 2026 | Zenika | Senior CV & ML engineer |

## Project spotlights

1. **Live 3D pose & occupancy at the edge** (personal project): RTSP camera → PeopleNet (INT8, TensorRT) → NvTracker → BodyPose3DNet → NvDsAnalytics, with Kafka + HLS output, a database-backed backend and a Next.js frontend animating a live 3D character over WebSocket. Runs at 30 FPS on a single Jetson Orin Nano.
2. **Semantic video search on multi-GPU cloud** (Zenika, 2026): DeepStream ingest of many RTSP streams with optical flow and YOLO26 detection, Kafka metadata, enrichment (make & model, OCR, ANPR) and Milvus indexing for image and natural-language retrieval.
3. **SkillCompass: evidence-first career AI** (PyCon 2026, Job & Skills Track): FastAPI backend, Next.js dashboard, SkillsFuture data pipeline, ChromaDB retrieval with Ollama embeddings and a fully local llama.cpp LLM that turns skills or a PDF resume into next roles, priority skills and actions, each with its evidence.
4. **Leading optical transceiver firmware** (Jabil, 2025–2026): lead engineer for 100G–1.8T transceivers; .NET/C# firmware regression testing, DSP–PMIC firmware interfaces and an Azure CI pipeline built from scratch.
5. **Dyson CameraJet: sensor to NPU** (Dyson, 2023–2025): MIPI-CSI capture, custom Linux kernel drivers for PWM–flash sync and Wi-Fi streaming, and on-device NPU gap detection; eliminated flash-induced motion blur. Also NPI demo rigs, DC motor control, embedded GUIs (Qt, LVGL, Flutter), Wi-Fi driver integration, board bring-up and a Make → CMake migration.
6. **Firmware leadership in life science** (Thermo Fisher Scientific, 2020–2023): led an IVDR compliance project, load-cell filtering, S-curve stepper motion control, CAN bus integration, MCU migrations through the chip shortage, and first runner-up in an inter-company AI hackathon.

## Technical toolkit

- **Languages:** Python, C++ and C, TypeScript / JavaScript, C# / .NET, SQL
- **Computer vision & ML:** PyTorch, TensorRT, NVIDIA DeepStream, OpenCV, GStreamer, YOLO, UNet
- **Full-stack & cloud:** React, Next.js, Node.js, Kafka, PostgreSQL, Milvus, Docker, Kubernetes, GCP, Terraform
- **Edge & embedded:** Jetson Orin, NPU, Embedded Linux, kernel drivers, bootloaders, MIPI-CSI, I2C, SPI

## Credentials

- **MSc, NUS** — Smart Industries & Digital Transformation, 2021–2023 (CGPA 4.03 / 5.0)
- **MSc Physics, Western Illinois University** — 2015–2017 (CGPA 3.85 / 4.0); dissertation on massive star formation
- **BSc Microelectronics with Physics, Campbell University** — 2012–2014; thesis on blood vein pattern recognition
- **Astrophysics research** at WIU since 2015; best poster award
- **Certifications:** Google Associate Cloud Engineer; NUS Graduate Certificate in Deep Learning for Industry
- **Publications:** ApJ, two MNRAS papers, Bulletin of the AAS and NI ASEAN Engineering Impact

## Contact

- Email: ws-tan@wiu.edu
- LinkedIn: [linkedin.com/in/wei-siang-tan](https://linkedin.com/in/wei-siang-tan)
- Website: [tan4575.github.io/joinme.github.io](https://tan4575.github.io/joinme.github.io)
