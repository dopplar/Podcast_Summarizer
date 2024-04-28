# Podcast Summarizer

This project aims to summarize YouTube podcast videos into concise LinkedIn posts using various tools and technologies.

## Basic Flow

1. **Input**: YouTube Podcast Video
2. **Audio Extraction**: PyTube
3. **Transcription**: Whisper JAX
4. **Prompt Template**: LangChain
5. **Summarization**: GPT3.5 Turbo API
6. **Output**: LinkedIn Post

## Tools Used

- Python
- Whisper JAX (Credit: [Sanchit Gandhi](https://github.com/sanchit-gandhi))
- Azure OpenAI
- LangChain
- GPT3.5 Turbo API

## Whisper JAX

Whisper JAX is an improved version of OpenAI Whisper, capable of transcribing audio 70x faster. This version addresses the slowness issue of Whisper, delivering a 30-minute audio transcription within 30 seconds on personal machines without requiring a dedicated GPU.

## Tips

1. Azure OpenAI is a paid service.
2. Consider using a normal GPT API if data security is not the highest priority.
3. A company/business email address is required to create an account on Azure OpenAI.
4. An active subscription (paid) is necessary to test this project even with a work email.

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Set up Azure OpenAI account and obtain API credentials.
4. Run the project with appropriate inputs.

## License

This project is licensed under the [MIT License](LICENSE).
