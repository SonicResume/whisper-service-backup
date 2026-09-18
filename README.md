# Whisper Service Backup

Backup documentation for the local Whisper transcription service used by Justice on Call.

## Whisper executable

/home/lee1967/dev/voice-generator/.venv/bin/whisper

## FFmpeg

/usr/bin/ffmpeg

## Current model

small

## Public transcription endpoint

https://transcribe.justiceoncall.ca/api/interview/transcribe

## Architecture

Internet
→ Cloudflare Tunnel
→ local Next.js transcription service
→ FFmpeg
→ local OpenAI Whisper
→ transcript

## Important

The Whisper virtual environment and model files are intentionally NOT stored in Git.
They must be rebuilt/downloaded on the host if the machine is replaced.
