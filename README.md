 LinkVigil AI
LinkVigil AI is a real-time URL safety analyzer that detects phishing and malicious websites using AI, heuristic rules, and a blacklist system.

Features
- Real-time URL detection (Chrome Extension)
- AI-based explanation of threats
- Risk scoring system
- Heuristic analysis (URL patterns, HTTPS, keywords)
- Blacklist checking
- History storage using SQLite

 Technologies Used
- Python (Flask, Streamlit)
- SQLite Database
- Hugging Face API (LLM)
- Chrome Extension (JavaScript)

 How It Works
1. User visits a website
2. Extension captures URL
3. URL sent to backend API
4. System analyzes using:
   - Heuristic rules
   - Blacklist
   - AI model
5. Risk score generated
6. User gets warning if unsafe
