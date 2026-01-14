# Installation (Anki Desktop)

This add-on runs **only on Anki Desktop** (tried on Windows 11, Version ⁨25.09.2 (3890e12c)⁩
Python 3.13.5 Qt 6.9.1 Chromium 122).  
AnkiMobile (iOS) and AnkiDroid (Android) do not support add-ons.

---

## Install the add-on

1. Download the add-on file:
anki-llm-vocabulary.ankiaddon
2. Open **Anki Desktop**
3. Go to **Tools → Add-ons**
4. Click **Install from file**
5. Select `anki-llm-vocabulary.ankiaddon`
6. Restart Anki

After restart, the add-on will appear in **Tools → Add-ons**.

---

## Import the recommended card format (recommended)

For the best user experience, import the prepared note type:

1. Download:
llm-vocab-note-type.apkg
2. Open **Anki Desktop**
3. Double-click the file (or use **File → Import**)
4. Use this note type when adding new vocabulary

---

## Set your API key

This add-on does **not** include an API key.

1. Open **Anki Desktop**
2. Go to **Tools → Add-ons**
3. Select **LLM Vocab Generator**
4. Click **Config**
5. Insert your API key:
```json
{
  "api_key": "YOUR_API_KEY_HERE"
}
Click Save

Restart Anki
