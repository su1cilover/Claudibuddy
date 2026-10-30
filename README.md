# ClaudiBuddy

A lightweight study app for students from Kinder to Grade 12. Green, liquid-glass design that stays light on low-end phones.

- Upload photos, PDFs, or text notes, or add a YouTube link
- Flashcards you can swipe, and multiple-choice quizzes
- Chat with an AI tutor (English, Filipino, or Taglish)
- Streaks, XP, and levels
- Everything is saved on the student's own device

It is a single `index.html` with no build step. Open it in a browser, or host it with GitHub Pages.

## About the AI features

The tutor chat, quiz maker, and flashcard maker call Claude through the page host. They work inside Claude, but not on plain GitHub Pages. To use them on your own site you need a small server that holds your Anthropic API key and answers requests from the page. Never put the key in `index.html`.
