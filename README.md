# Coda Task Logger Userscript

A Tampermonkey userscript that automatically copies Coda task details to your clipboard and stores a personal log every time you claim or close a task.

## Features

- Instantly logs the ISRC, artist, and title when you click **Take the task** (also works when closing the task).
- Copies the formatted entry to your clipboard so you can paste it into any text file.
- Persists a running history using Tampermonkey storage.
- Provides a floating **📄 Download Log** button that saves the full history as `CodaTaskLog.txt`.

## Installation

1. Install the [Tampermonkey](https://www.tampermonkey.net/) browser extension if you haven’t already.
2. Create a new userscript and paste the contents of [`Coda Task Logger`](./Coda%20New%20Music%20Friday%20Logger).
3. Save the userscript and ensure it is enabled.

## Usage

1. Open your shared Coda task table.
2. Click **Take the task** for any row.
3. The script copies a line like `2025-10-20 19:55:01 | USAT22504503 | Gucci Mane | Gucci Special` to your clipboard and keeps a copy in memory.
4. Press `Ctrl+V` in your local `.txt` log to paste the entry.
5. Use the floating **📄 Download Log** button at any time to export your full history.

## Troubleshooting

- If the clipboard entry is missing, ensure your browser allows Tampermonkey clipboard access on Coda.
- For highly customised tables, you may need to reload the page after changing visible columns so the script can detect the ISRC, artist, and title columns.

## License

MIT