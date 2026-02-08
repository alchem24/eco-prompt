# Eco Prompt: High-Efficiency AI Compressor

**Winner of [Your Hackathon Name]** 
*Signal in. Noise out. Maximum efficiency.*

## 🚀 The Problem
Large Language Models (LLMs) consume massive amounts of energy. A single query uses ~0.3 Joules of energy. 
However, human prompts are inefficient—filled with 40% "fluff" (polite fillers, verbose formatting) that wastes GPU cycles, money, and time.

## 💡 The Solution
**Eco Prompt** is a Flutter-based Semantic Compressor that acts as middleware between you and the LLM. 
It uses a deterministic telegraphic algorithm to:
1.  **Compress** prompts by 30-60% without losing intent.
2.  **Verify** semantic integrity with a secondary AI check (Research Mode).
3.  **Calculate** real-time savings in Joules and USD.

## 🛠️ Tech Stack
-   **Frontend:** Flutter (Mobile + Web) with CRT Terminal styling.
-   **AI Engine:** Google Gemini 2.5 Flash-Lite (High speed, low cost).
-   **Backend:** Firebase Firestore (Global savings leaderboard).

## 📸 How to Run
1.  Clone the repo: 
    ```bash
    git clone https://github.com/YOUR_USERNAME/entropy-zero.git
    ```
2.  Install dependencies:
    ```bash
    flutter pub get
    ```
3.  Run the app:
    ```bash
    flutter run
    ```
4.  Enter your Gemini API Key in the UI (Keys are not stored, only used for the session).

## 🤖 AI Usage Disclosure
This project was built with the assistance of Generative AI for:
-   **Code Acceleration:** Boilerplate generation for Firestore and Flutter UI.
-   **Logic Generation:** The compression system prompt itself is powered by an LLM.
-   **Verification:** Core logic relies on Gemini for semantic checking.