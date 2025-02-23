# Book Summary and Interaction Application

This project is a web application that allows users to upload documents (in DOCX format), generate summaries, interact with a chatbot, and create images based on the document's content. The application leverages state-of-the-art NLP and image generation models to provide a rich and interactive user experience.

## Features

- **Document Summarization**: Upload a DOCX file to generate a concise summary using a transformer model.
- **Chatbot Interaction**: Ask questions about the summary and receive responses from a conversational AI.
- **Text-to-Image Generation**: Generate images based on the summary using a text-to-image model.
- **Speech-to-Text and Text-to-Speech**: Interact with the application using voice commands and listen to responses.

## Technologies Used

- **Flask**: A lightweight web framework for building the application.
- **Hugging Face Transformers**:
  - `sshleifer/distilbart-cnn-12-6` for summarization.
  - `microsoft/DialoGPT-medium` for the chatbot.
- **Diffusers Library**: Used for text-to-image generation with Stable Diffusion.
- **Web Speech API**: Enables speech-to-text and text-to-speech functionalities.
- **PIL (Python Imaging Library)**: For image creation and manipulation.
- **JavaScript and jQuery**: For client-side scripting and AJAX requests.
- **Bootstrap**: For responsive and visually appealing UI design.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
