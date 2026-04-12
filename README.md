# 🐕 Dog Theory Exam — Canton of Zurich

A web app to study and practise for the mandatory dog theory exam in the Canton of Zurich, Switzerland.

🔗 **Live app:** https://gemmagf.github.io/zurich-dog-exam/

---

## About the exam

Since **1 June 2025**, the dog theory exam is mandatory in Canton Zurich for:
- First-time dog owners
- Anyone who has not owned a dog in the last 10 years

**Format:** 25 questions · 30 minutes · Minimum passing score: **20/25 (80%)**

The exam is administered by an authorised dog trainer. The official questions are not public — this app is based on the official study booklet published by the Veterinary Office of the Canton of Zurich.

---

## Features

### 📖 Study
All exam topics summarised from the official booklet, organised into 11 expandable chapters:
- A Dog's Senses
- A Dog's Needs
- Behavioural Development
- Dog Body Language
- The 4 Fs & Ladder of Aggression
- Learning Theory
- Housing & Daily Life
- Law & Legal Requirements
- Theory Exam & Training
- AMICUS & Registration
- Travelling with Dogs

### ✏️ Quiz
- 38 practice questions across all topics
- Filter by topic or practise everything at once
- Randomised answer order every time
- Immediate feedback with explanations after each answer
- Results breakdown by topic

### 📊 Progress
- Quiz results saved automatically in the browser (localStorage)
- Overall stats: quizzes taken, average score, times passed
- Performance bar chart per topic
- Weak topics (below 80%) highlighted with direct link to study material
- Full quiz history with date and score

---

## Source material

- **Official booklet:** *Dog Training Theory* — Veterinary Office of the Canton of Zurich (August 2025)
- **Legal basis:** TSchG, TSchV (federal) · HuG, HuV (Canton Zurich)
- **AMICUS database:** https://www.amicus.ch
- **Official info:** https://www.zh.ch/de/umwelt-tiere/tiere/haustiere-heimtiere/hunde.html

---

## Tech

Single-page HTML/CSS/JS app — no frameworks, no dependencies, no backend.
Progress data stored in browser `localStorage`.
