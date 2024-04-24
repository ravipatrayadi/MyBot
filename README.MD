

# ChatBot With Open AI 

This project demonstrates a simple chatbot implementation using OpenAI's GPT-3 model for text generation and Gradio for creating a user-friendly interface. The chatbot can converse with users using both text and voice inputs.

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/chatbot.git
cd chatbot
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Obtain an API key from OpenAI by signing up on their [website](https://openai.com/).

2. Replace `'add your open ai api key here'` with your OpenAI API key in the `chatgpt_api` function.

3. Run the code:

```
python chatbot.py
```

4. Once the program is running, the Gradio interface will open in your default web browser. You can interact with the chatbot by providing text or voice inputs.

## Dependencies

- [OpenAI API](https://openai.com/)
- [Gradio](https://gradio.app/)
- [Whisper](https://github.com/openai/whisper)
- [gTTS](https://pypi.org/project/gTTS/)
- [ffmpeg](https://ffmpeg.org/) (Make sure it's installed and added to your system PATH)

## Acknowledgments

- [OpenAI](https://openai.com/) for providing the GPT-3 model and API.
- [Gradio](https://gradio.app/) for simplifying the creation of interactive interfaces.
- [Whisper](https://github.com/openai/whisper) for audio processing capabilities.
- [gTTS](https://pypi.org/project/gTTS/) for text-to-speech conversion.


