<p align="center">
  <img src="assets/detective_logo.png" alt="Detektif Sarkanto Logo" width="250"/>
</p>

<h1 align="center">🔍 Sarcasm Detector Project</h1>
<h3 align="center"><em>Detektif Sarkanto — Find the sarcasm hiding in every headline</em></h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Flask-2.2.5-black?style=flat-square&logo=flask" />
  <img src="https://img.shields.io/badge/TensorFlow-2.13-orange?style=flat-square&logo=tensorflow" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
</p>

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Details](#model-details)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
A Flask-based web application that detects sarcasm in headlines using a pre‑trained TensorFlow model. The UI provides a clean, modern interface built with responsive CSS and custom graphics.

## Features
- Detect sarcasm levels (Very Low, Mild, Moderate, High)
- Supports English and Indonesian headlines (auto‑translation)
- Responsive design with glass‑morphism style elements
- Dark‑mode compatible colors

## Installation
```bash
# Clone the repository (if not already)
git clone https://github.com/Zzybeanie/Final-Project-Alogrotma-Pemrograman-II-Web-based.git
cd Final-Project-Alogrotma-Pemrograman-II-Web-based

# Set up Python environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
# or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

## Usage
```bash
# Run the Flask app
python sarcasm/main.py
```
Open a web browser and navigate to `http://127.0.0.1:5000/`.

## Project Structure
```
├── sarcasm/
│   ├── static/          # CSS, images, assets
│   ├── templates/       # HTML templates
│   ├── main.py          # Flask app entry point
│   └── sarcasm-model5/  # TensorFlow model directory
├── .gitignore
├── requirements.txt
└── README.md
```

## Model Details
The model is stored in the `sarcasm-model5` directory and loaded without the `.h5` extension for compatibility with TensorFlow 2.x.

## Contributing
Feel free to open issues or submit pull requests. Please ensure code follows PEP8 standards and updates the documentation as needed.

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
