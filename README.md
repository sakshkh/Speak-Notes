🎧 AI Meeting Summarizer

Transform your meeting audio recordings into concise, structured summaries with actionable items.

💡 Features

📂 Upload a meeting audio file (.mp3, .wav, etc.)

🔊 Transcribe with Faster-Whisper

📝 Summarize with Hugging Face Transformers (BART model)

📤 Export summaries as Markdown, JSON, and PDF

🧠 AI Tools Used

Hugging Face Transformers: Summarization, action extraction, and meeting classification (BART)

Faster-Whisper: Fast and accurate offline transcription

Gradio: User-friendly web interface

🚧 Challenges Faced

⚡ Long transcription times on CPU → solved using GPU + model optimization

🖋️ Formatting structured outputs (headings, bullet lists) for PDF generation

📁 Handling large audio uploads smoothly in the web interface

🔧 Future Improvements

🗣️ Speaker diarization (speaker labels)

📆 Google Calendar integration for automatic follow-ups

🌍 Multilingual transcription support

⏱️ Real-time processing
