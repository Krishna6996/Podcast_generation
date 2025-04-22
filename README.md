# Automated Podcast Generation Pipeline

**Last Updated:** 10 April, 2025

A fully automated end-to-end pipeline that converts user-provided text or audio input into studio-quality podcast episodes. The system integrates text-to-speech (TTS), voice cloning, sound effects (SFX) placement, and post-production mixing to produce professional-grade content with minimal human intervention.

## Features

- Input Flexibility: Accepts both textual scripts and voice recordings.
- Context-Aware SFX Insertion: Automatically identifies suitable points in the podcast to insert relevant sound effects using basic keyword detection and rule-based heuristics.
- Voice Cloning & TTS: Uses advanced speech synthesis models (e.g., ElevenLabs or alternatives) for natural and expressive narration.
- Audio Mixing: Seamlessly combines narration and SFX into a polished audio file using dynamic volume normalization and fade effects.

## Tech Stack

- Python for scripting and orchestration  
- Whisper / SpeechRecognition for speech-to-text (if audio input)  
- ElevenLabs / TTS APIs for voice generation  
- Pydub / FFmpeg for audio manipulation and post-production  
- OpenAI / LangChain (optional) for script polishing or generation

## Pipeline Overview

1. Input: Script (.txt) or voice note (.wav/.mp3)
2. Preprocessing: Transcription (if audio), normalization, punctuation
3. Voice Synthesis: Text-to-speech or cloned voice generation
4. SFX Tagging: Keyword detection or rule-based tagging
5. Audio Stitching: Merge voice + SFX using Pydub or FFmpeg
6. Output: Final polished podcast episode (.mp3/.wav)

##working demo
https://youtu.be/zmwE_D1knyw?si=Wo4LOl9y2V-jam7v

