# VIBE: Vision-based Interface Benchmarking Environment

VIBE is an open-source web platform for benchmarking vision models in gesture-based interaction contexts. It enables HCI researchers to quickly evaluate and compare multiple vision models using short video clips, providing immediate feedback on key metrics such as accuracy, latency, and resource usage.

## 🌟 Key Features

- **Quick Model Evaluation**: Upload a video (up to 30s) and get immediate performance metrics
- **Multi-Model Comparison**: Compare different vision models side by side
- **Real-time Analytics**: Monitor 20+ metrics across 4 categories:
  - Accuracy & Quality
  - Performance & Speed
  - Resource Usage
  - Robustness
- **Interactive Dashboard**: Visualize results through intuitive graphs and comparisons
- **Export Capabilities**: Generate LaTeX-ready comparison tables and performance reports

## 🚀 Getting Started

Visit [VIBE Platform] to start using the web interface.

For local development:

```bash
git clone https://github.com/mines-paris/vibe.git
cd vibe
docker-compose up
```

## 📊 Supported Models

Currently supported vision models include:
- MediaPipe Hands
- OpenPose
- Custom models (via API)

## 💻 System Requirements

For optimal performance:
- Modern web browser (Chrome, Firefox, Safari)
- Stable internet connection
- Webcam (for live capture)

For local deployment:
- NVIDIA GPU (RTX 3060 8GB or better recommended)
- Docker and Docker Compose
- 16GB RAM minimum

## 📖 Documentation

- [User Guide](docs/user-guide.md)
- [API Documentation](docs/api.md)
- [Model Integration Guide](docs/model-integration.md)
- [Contributing Guidelines](CONTRIBUTING.md)

## 📝 Citation

If you use VIBE in your research, please cite:

```bibtex
@inproceedings{el2025vibe,
  title={VIBE: Plateforme Open-source de Benchmark des Modèles de Vision pour l'Interaction Gestuelle},
  author={El Idrissi Dafali, Rayan and Glushkova, Alina},
  booktitle={IHM '25: 26e Conférence Francophone sur l'Interaction Humain-Machine},
  year={2025},
  publisher={ACM}
}
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- Rayan El Idrissi Dafali (Mines Paris – PSL)
- Alina Glushkova (Mines Paris – PSL)

## 📬 Contact

For questions and support:
- 📧 Email: vibe@minesparis.psl.eu
- 💬 [Discord Community](https://discord.gg/vibe-community)
- 🐦 Twitter: [@VIBE_Platform](https://twitter.com/VIBE_Platform)

---
Made with ❤️ at [Centre de Robotique, Mines Paris – PSL](https://www.minesparis.psl.eu/) 
