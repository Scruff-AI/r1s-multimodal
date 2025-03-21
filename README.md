# R1 Supervisor Multimodal AI Assistant

A multimodal AI assistant powered by the R1 Supervisor system, capable of processing text, audio, and visual inputs.

## Features

- 🎤 Audio Processing
  - Speech recognition
  - Text-to-speech synthesis
  - Voice command processing

- 🖼️ Visual Processing
  - Image generation
  - Image analysis
  - Visual content understanding

- 🔍 Information Retrieval
  - Web search integration
  - Wikipedia queries
  - Link scraping and processing

- 📄 File Handling
  - Multi-format file processing
  - Document analysis
  - Data extraction

## Installation

```bash
# Clone the repository
git clone https://github.com/Scruff-AI/r1s-multimodal.git
cd r1s-multimodal

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
.\venv\Scripts\activate
# On Unix or MacOS:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## Project Structure

```
r1s-multimodal/
├── src/
│   ├── core/          # Core system functionality
│   ├── audio/         # Audio processing modules
│   ├── vision/        # Visual processing modules
│   └── utils/         # Utility functions
├── tests/             # Test suite
├── docs/              # Documentation
├── .gitignore         # Git ignore rules
├── README.md          # Project documentation
└── requirements.txt   # Project dependencies
```

## Environment Setup

Create a `.env` file in the root directory with the following variables:

```env
# API Keys and Configuration
OPENAI_API_KEY=your_key_here
CHAINLIT_AUTH_SECRET=your_secret_here

# Model Settings
MODEL_NAME=your_model_name
DEVICE=cuda  # or cpu
```

## License

MIT License
