## Hi, I'm Diyar 👋

**Edge AI & ML Engineer.** I build real-time inference systems: optimized TensorRT pipelines on NVIDIA Jetson and data-center GPUs, and LLM-powered agents that turn models into working tools.

---

### ⚡ Edge AI on NVIDIA Jetson

- Deploy **DeepStream / GStreamer** pipelines on Jetson, with one codebase for Jetson and dGPU. The platform is detected at runtime and Tegra-specific elements are added only when needed.
- Build **TensorRT FP16 engines** from ONNX models, directly on the target device.
- Use **hardware-accelerated video** through NVDEC/NVENC (`nvv4l2decoder`, `nvv4l2h264enc`), with decoders tuned for maximum performance on integrated GPUs.
- Ingest **multiple RTSP cameras** and run them through a single batched inference call, with live-source latency handling.
- Deploy in containers with NVIDIA's multi-arch DeepStream images.

### 🤖 LLMs, VLMs & Agentic AI

- Built an **AI job search agent** that works in several steps:
  - An LLM turns an uploaded CV into a structured profile and plans the searches.
  - The agent queries job boards and employer ATS APIs in parallel and filters the results with rules.
  - An LLM scores each posting's fit in parallel batches and writes a tailored CV and cover letter.
- **Provider-agnostic LLM layer:** Claude, OpenAI-compatible APIs or fully local models through Ollama. Every response is validated against a Pydantic schema.
- **Agentic coding** with **Claude Code** in my daily development workflow.
- Currently exploring **vision-language models (VLMs)** and running LLM/VLM inference on edge devices.

### 🎯 Real-time computer vision

Detection, multi-object tracking, instance segmentation and multi-person pose estimation. This includes custom post-processing written directly on raw output tensors.

---

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**AI Job Search Agent**](https://github.com/diyaralma/ai-job-search-agent) | Multi-step LLM agent: CV parsing, search planning, multi-source job retrieval, LLM fit scoring and tailored CV generation | Python · FastAPI · Pydantic · Next.js · Claude / OpenAI / Ollama |
| [**Basketball Player Tracking**](https://github.com/diyaralma/basketball-player-tracking-deepstream) | Player detection and tracking with stable IDs, live per-player stats and a court minimap | DeepStream · PeopleNet · NvDCF · Docker |
| [**Multi-Stream Pose Estimation**](https://github.com/diyaralma/deepstream-multistream-pose-estimation) | Multi-person pose estimation on several RTSP/file streams, with skeletons decoded from raw tensors | DeepStream · TensorRT · GStreamer |
| [**YOLO Instance Segmentation**](https://github.com/diyaralma/deepstream-yolo-segmentation) | Multi-stream YOLO11 segmentation with end-to-end TensorRT engines | DeepStream · TensorRT · YOLO |
| [**DeepStream Pose Estimation in Python**](https://github.com/diyaralma/deepstream-pose-estimation-python) | Python port of NVIDIA's C++ pose estimation app, with PAF decoding and Hungarian matching | DeepStream · TensorRT · NumPy |
| [**SwiftWheels**](https://github.com/diyaralma/swiftwheels-car-rental) | Vehicle rental system whose business logic lives in PostgreSQL procedures and triggers | Java · PostgreSQL |

---

### Tech stack

**Edge AI & inference**<br>
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![DeepStream](https://img.shields.io/badge/DeepStream-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![GStreamer](https://img.shields.io/badge/GStreamer-FF3131?style=for-the-badge&logo=gstreamer&logoColor=white)

**LLMs & agentic AI**<br>
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI--compatible%20APIs-412991?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

**Computer vision**<br>
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & tools**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### Contact

[![Email](https://img.shields.io/badge/Email-diyaralma457%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diyaralma457@gmail.com)
