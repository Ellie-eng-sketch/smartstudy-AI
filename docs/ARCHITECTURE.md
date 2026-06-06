# SmartStudy AI Architecture

## High-Level Architecture

Student
    │
    ▼
Flutter Mobile App
    │
    ├── Authentication
    ├── Recorder
    ├── OCR
    ├── AI Tutor
    ├── Notes
    ├── Flashcards
    └── Quizzes
    │
    ▼
Firebase Backend
    │
    ├── Authentication
    ├── Firestore
    ├── Storage
    └── Cloud Functions
    │
    ▼
AI Services
    ├── Whisper
    ├── OCR Engine
    └── OpenAI Models
