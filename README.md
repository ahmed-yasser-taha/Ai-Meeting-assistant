# Ai-Meeting-assistant
Meeting Transcriber Summarizer with AI Agents main
This project automates the process of downloading meeting recordings, transcribing audio, summarizing discussions, extracting action items, drafting follow-up emails, and sending them automatically via Gmail SMTP.

It leverages Whisper ASR, CrewAI Agents, and Google Gemini for language understanding.


🚀 Features
🎧 Transcription: Convert meeting audio into text using OpenAI Whisper.
📝 Summarization: Generate structured meeting notes (Decisions, Discussions, Agreements, Risks, Next Steps).
✅ Action Items: Extract tasks in a strict JSON schema.
📧 Email Drafting: Compose professional follow-up emails with summary + tasks.
📤 Email Sending: Send the drafted email securely via Gmail SMTP.


📦 Installation
Clone the repository and install dependencies:

git clone https://github.com/ismaillalyaan/Meeting-Transcriber-Summarizer-with-AI-Agents/tree/main
cd meeting-transcriber

pip install -r requirements.txt
