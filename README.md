# Nova ReCall – AI-Powered Smart Study Companion  

Nova ReCall is an **AI-powered, offline-first study companion** that helps students **smart notes organization, auto-generate quizzes, and retain knowledge smarter** with gamification and personalized recall scheduling.  
Designed for India’s accessibility needs, ReCall works seamlessly even in low-connectivity areas.  

## Features  

- **Smart Note Capture** → Upload text, PDFs, or images; OCR extracts content into clean study notes.  
- **AI Summaries & Flashcards** → Get instant, concise summaries and flashcards for quick revision.  
- **Adaptive Recall Engine** → AI schedules micro-revisions based on your memory curve to boost retention.  
- **Dynamic Knowledge Graph** → Visual map of concepts auto-built from your notes for holistic learning.  
- **Peer-to-Peer Sharing** → Share quizzes & flashcards over Wi-Fi Direct.  
- **Gamification Layer** → Streaks, XP, and badges to keep students motivated and engaged.  
- **AI-Powered Exam Simulator** → Personalized mock exams from your own notes with adaptive difficulty.  
- **Privacy-First Vault** → End-to-end encrypted local storage; syncs only when internet is available.  


## Tech Stack  

- **Frontend (Web):** React.js, Vite, CSS, (PWA compatible)  
- **Mobile:** React Native 
- **Routing:** React Router DOM  
- **State & Storage:** SQLite (offline-first), LocalStorage for caching 
- **AI & NLP:** Tesseract.js (OCR), OpenAI APIs for summarization & quiz generation, Sarvam LLM for voice assitance  
- **Visualization:** Chart.js for Knowledge Graph & progress tracking  
- **Backend:** FastAPI (AI engine + sync services)  
- **Database (Cloud):** PostgreSQL (online-sync)  
- **Hosting:** Vercel (web), Firebase/AWS for sync & storage  


##  How It Works  

1. **Capture Study Material** → Upload text, PDF, image, or voice.  
2. **AI Engine Processes Notes** → OCR + Summarization → generates flashcards & quizzes.  
3. **Adaptive Recall Engine** → Schedules when to revise (smart reminders).  
4. **Knowledge Graph View** → Explore interconnected topics visually.  
5. **Offline-First Storage** → Works fully offline, syncs when internet is available.  
6. **Gamified Dashboard** → Track streaks, XP, and progress.  
7. **Peer-to-Peer Sharing** → Send/receive flashcards & quizzes.  

## Setup Instructions  

### 1. Clone the Repo  
```bash
git clone https://github.com/alurubalakarthikeya/recall.git
cd recall
```
### 2. Create .env File

Add your API key(s) inside .env:
```
OPENAI_API_KEY=your_api_key_here
GOOGLE_API_KEY=your_api_key_here
```

### 3. Frontend Setup
```
cd frontend
npm install
npm run dev
```

### 4. Backend Setup
```
cd backend
pip install -r requirements.txt  
uvicorn app:app --reload          
```

### Future Roadmap

~ Offline Collaborative Circles – Mesh network for study groups.
~ Voice Tutor – Talk to AI in English & local languages, offline-first.
~ Advanced Analytics – Predict mastery timelines & weak area focus.

## Developers:

<a href="https://github.com/ArjiJethin">@Arji Jethin Naga Sai Eswar</a><br>
<a href="https://github.com/alurubalakarthikeya">@Aluru Bala Karthikeya</a><br>
