# 🎧 AI Meeting Summarizer

Transform your meeting audio recordings into concise, structured summaries with actionable items.

---

## 💡 Features

- Upload a meeting **audio** file (`.mp3`, `.wav`, etc.)
- Transcribe with **Faster-Whisper**
- Summarize with **Hugging Face Transformers** (BART model)
- Export summaries as **Markdown**, **JSON**, and **PDF**

---

## 🧠 AI Tools Used

- **Hugging Face Transformers**: for summarization, action extraction, and meeting classification using BART.
- **Faster-Whisper**: for fast and accurate offline transcription.
- **Gradio**: for an easy-to-use web interface.

---

## 🚧 Challenges Faced

- Managing long transcription times on CPU; resolved by using GPU with model optimization.
- Formatting structured outputs (headings, bullet lists) for PDF generation.
- Ensuring smooth UX while uploading large audio files.

---

## 🔧 Future Improvements

- Add **speaker diarization** for speaker labels
- Integrate with **Google Calendar** to auto-schedule follow-ups
- Add support for **multilingual transcription**
- Real-time processing

---

## 🚀 Getting Started

1. **Clone the repository**
   ```sh
   git clone <your-repo-url>
   cd aistudio-main
   ```

2. **Create and activate a virtual environment**
   ```sh
   python -m venv .venv
   .\.venv\Scripts\activate
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the app**
   ```sh
   python app.py
   ```

---

## 📦 Requirements

See `requirements.txt` for all dependencies.

---

## 📝 License

MIT License
