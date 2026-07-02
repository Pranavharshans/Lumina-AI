# CLAUDE.md — Lumina AI

Voice-controlled multimodal AI assistant for system automation and screen analysis.

## Key capabilities

- Voice command input (Whisper/Deepgram)
- Screen capture and analysis (Gemini Vision)
- System automation (file ops, app control)
- Multi-agent orchestration (CrewAI)

## Stack

- Speech: Whisper, Deepgram
- Vision/Language: Gemini API, Mistral AI
- Orchestration: CrewAI
- TTS output via system audio

## Running

```bash
pip install -r requirements.txt
python main.py
```

Requires API keys for Gemini, Mistral, and Deepgram in `.env`.
