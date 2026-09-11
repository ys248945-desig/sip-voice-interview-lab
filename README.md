# 🎙️ SIP Voice Interview Lab

A browser-based voice interview practice assistant designed for Summer Internship Project (SIP), viva, HR interviews, and placement preparation.

## Features

- 🎤 Voice-based interview practice using browser speech recognition
- 🔊 Interviewer questions spoken aloud
- 📝 Live speech captions and full interview transcript
- 🧠 Report-aware questioning from an uploaded SIP/internship report
- 🔄 Adaptive follow-up questions based on the previous answer
- 📊 Question-by-question content coverage and practice scoring
- ✍️ Conservative English correction that keeps the user's original facts and meaning
- 🎧 Communication feedback covering approximate pace, filler words, vocabulary variety, tone/volume, and answer quality
- 🛡️ Report fact-checking for numerical inconsistencies
- 📥 Transcript export
- 🌐 Designed to run in modern Chrome and Microsoft Edge

## Privacy

The application is designed as a browser-only prototype. Uploaded report text is processed in the browser by the page rather than being sent to a custom application server.

## Important limitation

This free browser-only version does not use an online LLM/API. Question selection, answer scoring, report matching, English correction, and follow-up logic are implemented with local JavaScript rules and text matching. The results should therefore be treated as interview-practice guidance rather than a professional assessment.

## Running locally

Open `index.html` in a modern Chrome or Microsoft Edge browser and allow microphone access when prompted.

## Project

**SIP Voice Interview Lab** — voice-first interview preparation for internship, viva, and placement practice.
