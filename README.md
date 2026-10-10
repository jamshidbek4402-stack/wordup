# WordUp: English Speaking Words

A mobile-friendly web app for learning the most common spoken English words, built as a one-person CS project.

**Live demo:** https://jamshidbek4402-stack.github.io/wordup/

## What it does
- Flashcards with pronunciation (IPA), a short English definition, an Uzbek translation and an example sentence (translations are being added level by level)
- Words grouped by CEFR level (B1, B2, C1) and split into stages of 20 words
- You must answer at least 18 of 20 correctly to unlock the next stage
- 25-second timer per word; confetti for a correct answer, a sad face for a wrong one
- Text-to-speech for each word and a microphone check to practise pronunciation (works best in Chrome on Android)
- Statistics: accuracy, daily streak, 7-day activity, and the words you get wrong most often, with a mistakes-only review mode
- Daily goal, a 20-question placement test, and a "My words" section for your own cards

## The problem
Many learners know hundreds of words but cannot recall them quickly when speaking. This app uses short timed rounds and repeated review of mistakes to train fast recall.

## Tech
Plain HTML, CSS and JavaScript. It is a Progressive Web App (web manifest + service worker), so it can be installed on a phone home screen, opens full-screen like a native app and works offline. Progress is stored in the browser (localStorage), so there is no server or account yet.

## Roadmap
- Grow the word list to 2,000 words with translations and examples
- Spaced-repetition scheduling
- Accounts and cloud sync
- Android app

## About how it was built
I designed the features and the learning flow, and built the app with the help of an AI assistant (Claude). I review and test every change, and I am learning how the code works as the project grows.
