# Adaptive Reader

> An AI-powered wearable reading assistant that captures printed text, extracts it using Optical Character Recognition (OCR), and converts it into speech to assist visually impaired users in reading physical documents.

---

## Overview

Adaptive Reader is a wearable assistive technology project developed to improve access to printed text for visually impaired individuals. The system combines computer vision, OCR, and text-to-speech technologies on a Raspberry Pi-based platform to provide real-time audio feedback from printed documents.

Originally developed as an undergraduate thesis project, this repository is being actively refactored into a modular, open-source project with improved software architecture, documentation, and modern AI capabilities.

---

## Features

- Capture text using a Raspberry Pi camera
- Image preprocessing using OpenCV
- Optical Character Recognition (OCR)
- Text-to-Speech (TTS) output
- Wearable hardware design
- Modular software architecture
- Expandable pipeline for future AI enhancements

---

## System Pipeline

```
Camera
   │
   ▼
Image Capture
   │
   ▼
Image Preprocessing
   │
   ▼
OCR Engine
   │
   ▼
Extracted Text
   │
   ▼
Text-to-Speech
   │
   ▼
Audio Output
```

---

## Hardware

- Raspberry Pi 4 Model B
- Sony IMX708 Camera Module
- Speaker / Audio Output
- Portable Power Supply
- 3D Printed Wearable Housing

---

## Software Stack

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Computer Vision | OpenCV |
| OCR | Tesseract OCR |
| Text-to-Speech | pyttsx3 |
| Hardware | Raspberry Pi |
| CAD Design | Onshape / SolidWorks |

---

## Repository Structure

```
Adaptive-Reader/

├── docs/
├── hardware/
├── research/
├── demo/
├── src/
├── tests/
├── scripts/
├── legacy/
├── README.md
├── LICENSE
└── requirements.txt
```

---

## Current Status

This repository is currently undergoing a complete redesign.

The original implementation has been preserved while the project is being upgraded with:

- Cleaner project architecture
- Better documentation
- Modular codebase
- Improved OCR pipeline
- AI-assisted text processing
- REST API support
- Docker deployment
- Automated testing

---

## Roadmap

### Phase 1
- [x] Original prototype
- [x] Undergraduate thesis
- [x] Wearable hardware prototype

### Phase 2
- [ ] Codebase refactoring
- [ ] Documentation improvements
- [ ] Repository restructuring

### Phase 3
- [ ] Modern OCR benchmarking
- [ ] FastAPI integration
- [ ] Docker support
- [ ] Performance optimization

### Phase 4
- [ ] Multi-language support
- [ ] Cloud deployment
- [ ] Mobile companion application
- [ ] Offline AI pipeline

---

## Research Background

This project was originally developed as part of my Bachelor's thesis in Engineering Physics at the National Institute of Technology Calicut (NIT Calicut).

The primary objective was to design a wearable system capable of assisting visually impaired users by converting printed text into speech in real time.

---

## Future Improvements

Some planned enhancements include:

- EasyOCR integration
- PaddleOCR integration
- Transformer-based OCR models
- Language detection
- Perspective correction
- Document enhancement
- LLM-assisted text correction
- Real-time translation
- Edge AI optimization

---

## Demo

Demo images and videos will be added soon.

---

## Contributing

Contributions, suggestions, and discussions are welcome.

If you'd like to improve the project, feel free to open an issue or submit a pull request.

---

## License

This isn't License under any regulatory body
---

## Acknowledgements

- National Institute of Technology Calicut
- OpenCV
- Tesseract OCR
- Raspberry Pi Foundation
- Open Source Community

---

## Author

**Himanshoo Jain**

Engineering Physics Graduate  
National Institute of Technology Calicut

GitHub: https://github.com/HimanshooJ

---

⭐ If you find this project interesting, consider giving it a star.
