## Hi, I'm Diyar 👋

**Edge AI & ML Engineer.** I build real-time inference systems: optimized TensorRT pipelines on NVIDIA Jetson and data-center GPUs, and LLM-powered agents that turn models into working tools.

---

### ⚡ Edge AI on NVIDIA Jetson & DGX Spark

- Hands-on with most of the NVIDIA edge lineup: **Jetson Nano**, the **Jetson Orin** family, **Jetson AGX Thor** and **DGX Spark**.
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
- Serve and run **LLMs and vision-language models (VLMs)** with **vLLM** and **Hugging Face**. Most of this work lives in private repositories.
- **Agentic coding** with **Claude Code** in my daily development workflow.

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

| Area | Tools |
|---|---|
| **Edge AI & inference** | ![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat&logo=nvidia&logoColor=white) ![DGX Spark](https://img.shields.io/badge/DGX%20Spark-76B900?style=flat&logo=nvidia&logoColor=white) ![DeepStream](https://img.shields.io/badge/DeepStream-76B900?style=flat&logo=nvidia&logoColor=white) ![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat&logo=nvidia&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white) ![GStreamer](https://img.shields.io/badge/GStreamer-FF3131?style=flat&logo=gstreamer&logoColor=white) |
| **LLMs & agentic AI** | ![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat&logo=vllm&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black) ![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat&logo=claude&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-191919?style=flat&logo=anthropic&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white) ![OpenAI-compatible APIs](https://img.shields.io/badge/OpenAI--compatible%20APIs-412991?style=flat) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white) |
| **Computer vision** | ![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white) |
| **Backend & tools** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |

---

### Contact

📫 [diyaralma457@gmail.com](mailto:diyaralma457@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/diyar-alma/)
