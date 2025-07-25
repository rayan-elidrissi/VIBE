# VIBE: Vision-based Interface Benchmarking Environment

VIBE is an open-source web platform for benchmarking vision models in gesture-based interaction contexts. It enables HCI researchers to quickly evaluate and compare multiple vision models using short video clips, providing immediate feedback on key metrics such as accuracy, latency, and resource usage.

## 🌟 Key Features

- **Zero-Setup Model Evaluation**: Drag-and-drop a short video (≤30s) and benchmark models instantly—no coding required.
- **Multi-Model Comparison**: Evaluate several vision models side-by-side with synchronized playback and quantitative scoring.
- **Comprehensive Metrics Suite**: Monitor 20+ evaluation metrics grouped into 4 categories:
  - Accuracy & Quality
  - Performance & Latency
  - Resource Utilization (CPU/GPU/memory)
  - Robustness under variable conditions
- **Realistic Deployment Simulation**: Performance contextualized for embedded CPUs, mobile GPUs, and desktop workstations.
- **Interactive Dashboard**: Intuitive charts (latency histograms, memory graphs, model trade-off visualizations).
- **Exportable Reports**: Generate LaTeX-ready comparison tables and detailed evaluation summaries.

## 🚀 Getting Started

Visit [VIBE Platform] to start using the web interface.

## 📊 Supported Models

VIBE currently supports the following vision models:

- **MediaPipe Hands** – Lightweight real-time hand tracking from Google.
- **RTMPose-Hand** – Real-time multi-person hand pose estimation from OpenMMLab.
- **BlazePose** – Full body pose estimation optimized for on-device inference.
- **OpenPose** – Classic multi-person 2D pose estimation using Part Affinity Fields.
- **Hand4Whole** – Accurate 3D hand pose estimator integrated into whole-body mesh pipelines.
- **Lite-HRNet-Hand** – Lightweight high-resolution hand pose model.
- **Ego3DHands** – Egocentric 3D hand pose estimation for first-person views.
- **DexYCB++** – Fine-grained 3D hand-object pose estimation in interaction settings.
- **HaMeR** – Hand Mesh Recovery model for high-fidelity pose and mesh reconstruction.

## 💻 System Requirements

For optimal performance:
- Modern web browser (Chrome, Firefox, Safari)
- Stable internet connection
- Webcam (for live capture)

For local deployment:
- NVIDIA GPU (RTX 3060 8GB or better recommended)
- Docker and Docker Compose
- 16GB RAM minimum

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

