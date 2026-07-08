# Dictation

A minimal, dark-themed web app that reads text aloud in chunks and waits for you to say **"ok"** before continuing — built for writing dictation practice.

*Making the life of students easier one step at a time.*

---

## What's in this repo

- `dictation.html` — the entire app (HTML, CSS, JS in one file). No build step, no dependencies.

## Requirements

- **Google Chrome** or **Microsoft Edge** (required for speech recognition support)
- A working microphone and speakers
- **Python** installed — check with `python3 --version` (Mac) or `python --version` (Windows). If missing, get it from [python.org](https://www.python.org/downloads/) (on Windows, check "Add to PATH" during install).

---

## Step 1: Get the files

## Step 2: Open a terminal in that folder

**Mac:** Open the folder in Finder, right-click inside it, choose **New Terminal at Folder**.

**Windows:** Open the folder in File Explorer, click the address bar, type `cmd`, press Enter.

## Step 3: Start a local server

Opening the HTML file directly (double-clicking) won't reliably grant microphone access — browsers only trust mic permissions on `http://` pages, not `file://`. Running a local server fixes this.

**Mac:**
```bash
python3 -m http.server 8000
```

**Windows:**
```bash
python -m http.server 8000
```

Leave this terminal window open — closing it stops the server.

## Step 4: Open the app

Go to **`http://localhost:8000/dictation.html`** in Chrome or Edge, and click **Allow** when prompted for microphone access.

---

## Using the app

1. Paste or type text into the text box.
2. (Optional) Click the gear icon to adjust **words per pause** or **reading speed**.
3. Click **Start**. It reads text aloud in chunks, then pauses.
4. Write what you heard, then say **"ok"** to continue.
5. Use **Pause** to stop temporarily, or **Reset** to start over.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Mic prompt never appears | Use the `http://localhost:8000/...` URL, not the file directly. Use Chrome or Edge. |
| "Microphone access denied" | Check the padlock icon in the address bar and allow mic access for `localhost`. |
| No sound | Check system volume and that the browser tab isn't muted. |
| `python3` not found | Try `python` instead, or install Python and check "Add to PATH" on Windows. |
| Port 8000 already in use | Run `python3 -m http.server 8080` and visit `http://localhost:8080/dictation.html`. |

---

To stop the server, go back to the terminal and press `Ctrl + C`.
