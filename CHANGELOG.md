# Changelog

## v0.3.0 (2026-03-18)

### Added
- GUI onboarding wizard (7-step Tauri app)
- 11 LLM providers: Groq, Cerebras, Together, OpenRouter, Fireworks, OpenAI, Anthropic, Gemini, Ollama, LM Studio, vLLM
- 3 STT engines: Local Whisper (Metal GPU), Groq Cloud Whisper, Deepgram Nova-2
- Secure API key storage via macOS Keychain
- Transcription history with searchable UI
- Polished CLI with cliclack onboarding and indicatif status
- Context-aware LLM formatting (code editors, messaging, email)
- Command mode for voice-driven text transformation
- Personal dictionary and saved snippets
- Auto-learning from corrections
- Usage statistics tracking
- 10-minute max recording (beats Wispr Flow's 6 min)
- One-line installer script
- Security: config permissions, input sanitization, checksum verification

### Fixed
- Whisper.cpp stderr output suppressed in TUI
- Empty LLM responses fall back to raw transcript
- Clipboard restored on injection error
- VAD no longer chunks speech during push-to-talk recording

## v0.1.0 (2026-03-16)
- Initial release: core pipeline, basic CLI
