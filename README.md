## Hi, I'm Diyar 👋

**Computer Vision & Edge AI Engineer.** I build real-time inference pipelines that take models from ONNX to optimized TensorRT engines and run them on live video, on both NVIDIA Jetson devices and data-center GPUs.

Day to day, that means:
- building **NVIDIA DeepStream / GStreamer** pipelines for detection, tracking, instance segmentation and pose estimation
- running many camera streams through a single batched inference call
- writing custom post-processing on raw output tensors
- keeping the whole pipeline fast enough for live RTSP input

I also build LLM-powered tools that validate model output against a schema and can run on any model provider, including fully local models.

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Basketball Player Tracking**](https://github.com/diyaralma/basketball-player-tracking-deepstream) | Player detection and tracking with stable IDs, live per-player stats and a court minimap | DeepStream · PeopleNet · NvDCF · Docker |
| [**Multi-Stream Pose Estimation**](https://github.com/diyaralma/deepstream-multistream-pose-estimation) | Multi-person pose estimation on several RTSP/file streams at once, with skeletons decoded from raw tensors in Python | DeepStream · TensorRT · GStreamer |
| [**YOLO Instance Segmentation**](https://github.com/diyaralma/deepstream-yolo-segmentation) | Multi-stream YOLO11 segmentation with end-to-end TensorRT engines | DeepStream · TensorRT · YOLO |
| [**DeepStream Pose Estimation in Python**](https://github.com/diyaralma/deepstream-pose-estimation-python) | Python port of NVIDIA's C++ pose estimation app, with PAF decoding and Hungarian matching | DeepStream · TensorRT · NumPy |
| [**AI Job Search Agent**](https://github.com/diyaralma/ai-job-search-agent) | Scans job boards and ATS APIs, ranks postings by fit with an LLM, and writes a tailored CV for each posting | Python · FastAPI · Next.js · LLMs |
| [**SwiftWheels**](https://github.com/diyaralma/swiftwheels-car-rental) | Vehicle rental system whose business logic lives in PostgreSQL procedures and triggers | Java · PostgreSQL |

### Tech

**Inference & edge AI:** NVIDIA DeepStream · TensorRT · ONNX · Jetson · CUDA-accelerated video (NVDEC/NVENC)<br>
**Computer vision:** YOLO · object tracking (NvDCF) · instance segmentation · pose estimation · OpenCV · GStreamer<br>
**AI / LLM:** Anthropic Claude API · OpenAI-compatible APIs · Ollama · structured outputs · Claude Code<br>
**Languages & backend:** Python · FastAPI · TypeScript / Next.js · Java · C · SQL (PostgreSQL)<br>
**Tooling:** Docker · Linux · Git

### Contact

📫 [diyaralma457@gmail.com](mailto:diyaralma457@gmail.com)
