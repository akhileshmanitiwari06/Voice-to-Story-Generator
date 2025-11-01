# Voice-to-Story-Generator
Converts podcasts or audio recordings into summarized stories or article-style content.

🎯 Goal

Speech → Text → Summarized Story with tone and context.

💡 Use Case

Journalists, YouTubers, or students can upload recorded discussions → get ready-made story content.

🧩 Architecture

Input – Audio file.

Speech-to-Text – Whisper, AssemblyAI, or Google STT.

Text Segmentation – Identify speakers + tone.

LLM Summarization – Convert dialogues into story.

Tone Detection – Sentiment + emotion scoring.

Output – Story text or narration voice.

⚙️ Tech Stack

OpenAI Whisper / SpeechRecognition (STT)

HuggingFace Transformers (NLP summarization)

TextBlob / Vader (emotion detection)

Streamlit (frontend)

🚀 Steps

Transcribe audio → text.

Use LLM prompt: “Summarize this conversation as a short story with dialogues.”

Add emotion detection to enhance story tone.

Optionally, regenerate voice with gTTS.
