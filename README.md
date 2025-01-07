# AI-Podcast-Generator

**AI-Podcast-Generator** is an innovative tool that transforms the text from PDF documents into engaging, AI-generated podcasts. By leveraging state-of-the-art AI models, this project extracts, summarizes, and converts the content into dynamic conversations, which are then converted into speech using advanced text-to-speech technology. Whether you're looking to create podcasts from research papers, articles, or any PDF content, this tool will do it automatically!

## Features

- **PDF Text Extraction**: Automatically extracts text from PDF files.
- **Text Summarization**: Uses powerful AI models to summarize lengthy text into concise points.
- **Conversational Script Generation**: Creates a natural, dynamic conversation from the summarized text, simulating a two-person discussion.
- **Text-to-Speech Conversion**: Converts the conversation into audio using ElevenLabs' AI-powered text-to-speech technology.
- **Audio Export**: Generates an MP3 file for easy podcast distribution.

## Requirements

- **Python 3.x** or higher
- **Libraries**:
  - `requests` for API communication
  - `PyPDF2` for PDF text extraction
  - `transformers` for AI-based text summarization
  - `pydub` for audio processing
  - `google-colab` for file upload functionality (when running on Google Colab)

## Installation

To get started with the **AI-Podcast-Generator**, clone this repository and install the necessary dependencies.

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/AI-Podcast-Generator.git
   cd AI-Podcast-Generator
