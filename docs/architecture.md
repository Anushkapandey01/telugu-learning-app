### System Architecture

1. Flutter App
   - audio input
   - translations
   - dictionary
   - daily lessons
   - voice bot UI

2. Python Backend (FastAPI)
   - translation engine
   - dictionary API
   - daily words generator
   - TTS voice generator
   - STT audio processor
   - LLM for Telugu conversation & corrections

3. Open-source Models (Free)
   - Vosk (speech-to-text)
   - Coqui TTS (Thanusri & Damon voices)
   - Indic Transformers (Hindi/English → Telugu)
   - Gemma/LLaMA small model for conversation