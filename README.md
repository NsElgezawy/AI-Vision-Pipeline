# AI-Vision-Pipeline

![Pipeline Diagram](assets/app_diagram.png)

## Overview
The **AI Vision Pipeline** is an end-to-end system that processes an input image and transforms it into a descriptive, creatively styled, and multilingual story.  
This project integrates **Computer Vision**, **Generative AI**, **prompt-based style control**, and an **interactive Gradio interface** to create a smooth, automated storytelling experience.

The pipeline allows users to upload an image → analyze its content → generate a story → apply a custom writing style → translate it into multiple languages → and view everything inside a clean web app.

---

## Tech Stack
- **Azure Computer Vision API** – image analysis and visual understanding  
- **Azure Translator API** – multilingual text translation  
- **Hugging Face Transformers** – generative text creation and style adaptation  
- **Python** – core implementation  
- **Prompt Engineering** – narrative tone and structure control  
- **Gradio** – interactive real-time UI  
- **Azure ML Studio (Notebooks)** – development and experimentation environment  

---

## Features
- **Image Understanding** – extract objects, scenes, and semantic details  
- **AI Story Generation** – convert vision output into a creative narrative  
- **Style Transformation** – apply custom writing tones (dramatic, poetic, etc.)  
- **Multilingual Translation** – generate output in different languages  
- **Interactive Web UI** – upload images and view results via Gradio  

---

## Project Structure
📦 project-root
│
├── app/
│ ├── gradio_app.py
│ ├── Gradio_web_UI_1.png
│
├── assets/
│ └── app_diagram.png
│
├── outputs/
│ ├── vision_summary.txt
│ ├── creative_generation.txt
│ ├── styled_output.txt
│ ├── translated_output.txt
│ └── gradio_interface_screenshot.png
│
└── README.md


---

## Screenshots & Outputs
- `outputs/vision_summary.txt`  
- `outputs/creative_generation.txt`  
- `outputs/styled_output.txt`  
- `outputs/translated_output.txt`  
- `app/gradio_app_preview.png`

---

## Usage
### 1. Clone the repository:
```bash
git clone <your-repo-url>
cd <repo-name>
