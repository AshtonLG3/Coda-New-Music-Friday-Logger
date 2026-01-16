# Coda Task Logger (Navy & Gold)

A Chrome extension content script that logs Coda task activity with a draggable dock, manual counters, and TXT export.

## Features

- Logs rows based on close-task actions and network row data.
- Draggable dock with a compact Navy & Gold theme.
- Manual increment/decrement controls plus a hard wipe button for the current cycle.
- One-click TXT export for the current mission cycle.

## Installation (Extension)

1. Open `chrome://extensions`.
2. Enable **Developer mode**.
3. Click **Load unpacked** and select this repository folder.

## Files

- `content.js` — main content script injected on `coda.io`.
- `manifest.json` — Chrome extension manifest (MV3).
- `PRIVACY_POLICY.md` — privacy policy for store submission.

## Usage

1. Open your shared Coda task table on `coda.io`.
2. Click on a row to capture a snapshot, then click **Close task** to log it.
3. Use the dock controls to adjust counts or export a TXT log.

## Privacy

See [PRIVACY_POLICY.md](./PRIVACY_POLICY.md).

## License

MIT
