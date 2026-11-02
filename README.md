# Palabra - Spanish Vocabulary PWA (100 Essential Words)

A production-ready, mobile-first Progressive Web App (PWA) designed to master 100 essential Spanish vocabulary words with emoji hints, native audio pronunciation, cheerful animal animations, confetti, and local persistence.

## ✨ Features
- **100 Curated Words**: Essential nouns, verbs, adjectives, food, animals, body parts, and places.
- **Two-Phase Interactive Learning**:
  1. *Flashcard Phase*: View Spanish word, expressive emoji clues, bilingual contextual sentence, and native speech pronunciation.
  2. *Quiz Phase*: Test recall with 4 randomized options. Correct answers trigger synthetic multi-oscillator chords, confetti showers, and animated animal bursts (`🐶 🐱 🦊 🐰 🦁 🐬 🦜 🦄`).
- **100% Offline Persistence**: Saves your mastered words, streak, current position, and settings in `localStorage`.
- **PWA Ready**: Works offline, can be installed on iOS, Android, and Desktop via manifest and auto-updating service worker (`sw.js`).
- **Direct GitHub Pages Deployment**: Includes `.nojekyll` and standalone assets.

## 🚀 Instant Deployment (GitHub Pages)
1. Unzip `palabra-spanish-pwa.zip`.
2. Push all files into a GitHub repository.
3. In repository **Settings** -> **Pages**, choose the `main` branch root (`/`) and save.
4. Your PWA will be live at `https://<username>.github.io/<repo>/`!

## 📱 Local Preview
Run any static HTTP server in the extracted folder:
```bash
python3 -m http.server 8080
```
Then visit `http://localhost:8080`.
