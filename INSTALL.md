# Installation (Anki Desktop)

This add-on runs **only on Anki Desktop** (Windows, macOS, Linux).  
AnkiMobile (iOS) and AnkiDroid (Android) do not support add-ons.

---

## Install the add-on

1. Download the `.ankiaddon` file from this repository (Releases)
2. Open **Anki Desktop**
3. Go to **Tools → Add-ons**
4. Click **Install from file**
5. Select the downloaded `.ankiaddon`
6. Restart Anki

After restart, the add-on will appear in **Tools → Add-ons**.

---

## Set your API key

This add-on does **not** include an API key.  
Each user must provide their own key locally.

1. Open **Anki Desktop**
2. Go to **Tools → Add-ons**
3. Select **LLM Vocab Generator (Source/Target Dropdowns)**
4. Click **Config**
5. Insert your API key:
   ```json
   {
     "api_key": "YOUR_API_KEY_HERE"
   }
