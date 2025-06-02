# Customer Insight AI Agent
This is a simple AI agent workflow to help Product Manager deal with Time-consuming customer interview synthesis.

## Workflow
Audio → Transcription → Summarization/Analysis → Insight database.

## Tools Used
| Layer | Tool | Description|
|---| ---| ---|
| Audio Capturing | Zoom Audio only Recording/ iPhone Voice Notes |  Replaceable with any audio capture as only as the end file is mp3, mp4, mpeg, mpga, m4a, wav, and webm.|
| Audio Transcription | OpenAI [Whisper Model](https://openai.com/index/whisper/]) | Audio to text Transcription|
|LLM Processing | OpenAI GPT-4o mini | Faster + cheaper for summarization, sentiment |
