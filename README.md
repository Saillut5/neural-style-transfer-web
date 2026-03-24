# Neural Style Transfer Web Application

## Overview

This repository contains a web application that demonstrates Neural Style Transfer, a fascinating deep learning technique that allows you to recompose images in the style of other images. The application is built with a React frontend for a responsive user interface and a FastAPI backend to handle the neural network computations, providing a fast and interactive experience.

## Features

- **Interactive UI:** Upload your content and style images, and see the results in real-time.
- **FastAPI Backend:** Efficiently serves style transfer requests using optimized deep learning models.
- **React Frontend:** Modern and responsive user interface for a seamless user experience.
- **Customizable Styles:** Experiment with various pre-trained artistic styles or upload your own.
- **Dockerized Deployment:** Easy to deploy using Docker containers for both frontend and backend.

## Getting Started

### Prerequisites

- Node.js and npm (for React frontend)
- Python 3.8+ and pip (for FastAPI backend)
- Docker (optional, for containerized deployment)

### Installation

#### Backend

```bash
git clone https://github.com/Saillut5/neural-style-transfer-web.git
cd neural-style-transfer-web/backend
pip install -r requirements.txt
```

#### Frontend

```bash
cd neural-style-transfer-web/frontend
npm install
```

### Usage Example

#### Backend

```bash
cd neural-style-transfer-web/backend
uvicorn main:app --reload
```

#### Frontend

```bash
cd neural-style-transfer-web/frontend
npm start
```

## Contributing

We welcome contributions! Please see `CONTRIBUTING.md` for details on how to get started.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
