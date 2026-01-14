# Anki LLM Vocabulary Add-on (Open Source EdTech)

An open-source **Education Technology (EdTech)** add-on for **Anki Desktop** that uses large language models (LLMs) to assist vocabulary flashcard creation while preserving **active recall** and **spaced repetition**.

You type a word, choose source and target languages, and click **Generate**.  
The add-on fills a concise translation and a clear example sentence.  
Anki remains responsible for review scheduling and memorization.

This project focuses on **lean learning**: reducing friction without removing the learner’s cognitive effort.

---

## Why this works

The add-on is designed around a simple principle:

> **Reduce friction, not thinking.**

- The learner decides which words to add  
- Generation is manual and intentional (no automation on review)  
- Cards remain minimal and recall-focused  

The LLM is used **only during card creation**, never during review.

---

## Features

- One-click LLM-assisted vocabulary card creation
- Two dropdowns to select **source** and **target** language
- Preserves active recall  
  - Front: word only  
  - Back: translation + example
- Supports many commonly learned languages worldwide
- Lightweight, transparent, and configurable
- Fully open-source

---

## Requirements

- **Anki Desktop** (Windows, macOS, Linux)
- An OpenAI-compatible API key (user-provided)

---

## Installation

👉 See [INSTALL.md](INSTALL.md) for step-by-step setup instructions.

---

## Distribution & installation (outside AnkiWeb)

This add-on is distributed **outside AnkiWeb**.

To support external distribution, the add-on includes a `manifest.json` file, as required by Anki.  
The manifest specifies:
- `package`: the folder name used by Anki
- `name`: the name shown in the Add-ons list

### Install from file
1. Download the `.ankiaddon` file from this repository (Releases)
2. Open **Anki Desktop**
3. Go to **Tools → Add-ons → Install from file**
4. Select the downloaded `.ankiaddon`
5. Restart Anki

---

## Mobile support

Anki add-ons run **only on Anki Desktop**.

- ❌ AnkiMobile (iOS): add-ons not supported  
- ❌ AnkiDroid (Android): add-ons not supported  

Cards generated on desktop (including Translation and Example fields) **sync normally** and can be reviewed on mobile devices.

**Recommended workflow:**
- Create and generate cards on desktop
- Review anywhere (desktop or mobile)

---

## Open source & philosophy

This project is intentionally:
- minimal
- transparent
- non-intrusive

It does **not** claim improved learning outcomes or replace teachers.  
Its contribution is practical: lowering the cost of creating high-quality flashcards while respecting evidence-based learning principles.

---

## License

This project is licensed under the **Apache License 2.0**.
