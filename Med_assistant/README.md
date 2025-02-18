# Student Mental Health Assistant

An AI-powered mental health chat assistant specifically designed for students, built using Google's Generative AI and LangGraph. The system provides empathetic, professional guidance for academic and emotional well-being concerns.

## Features

- Empathetic AI therapist for student support
- Intelligent conversation tracking and summarization
- Structured knowledge base for student information
- Severity assessment for mental health concerns
- Multi-model approach using different Gemini models
- Checkpoint system for conversation persistence

## Architecture

The system utilizes three specialized LLM models:
- **Main Therapist (Gemini 2.0 Flash)**: Handles primary student interactions
- **Conversation Summarizer (Gemini 1.5 Flash)**: Maintains and updates conversation context
- **Knowledge Base Manager (Gemini 1.5 Pro)**: Manages student information

## Prerequisites

- Python 3.11+
- Google AI API key (Gemini models access)
- Jupyter Notebook environment

## Setup

1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a .env file and add your Google AI API key:
   ```
   GOOGLE_API_KEY=your_api_key_here
   ```
4. Choose a notebook to run:
   - `demo.ipynb`: Basic implementation with memory persistence
   - `demo_checkpoint.ipynb`: Implementation with SQLite checkpoints

## Usage

The system provides:
- Interactive therapy sessions for students
- Automatic tracking of:
  - Student identification
  - Mental health status
  - Academic concerns
  - Stress levels
  - Severity assessment
- Conversation summarization and context maintenance
- Persistent conversation storage using checkpoints

## Important Notes

1. This is a demonstration project and should not be used as a replacement for professional mental health services.
2. Always refer students to qualified mental health professionals for serious concerns.
3. The system includes severity assessment but should not be used for clinical diagnosis.

## License

MIT License

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
