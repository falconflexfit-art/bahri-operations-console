# Save the console with iOS Shortcuts

Grok cannot write into the iPhone Files app. Shortcuts can.

## Shortcut 1 — Save Bahri Console (one tap)

1. Open **Shortcuts** → tap **+**
2. Tap the name → rename to **Save Bahri Console**
3. Add **4 actions**, in this order:

| # | Action | Settings |
|---|---|---|
| 1 | **URL** | `https://falconflexfit-art.github.io/bahri-operations-console/Bahri-Operations-Console.html` |
| 2 | **Get Contents of URL** | Method: GET (default) |
| 3 | **Set Name** | `Bahri-Operations-Console.html` |
| 4 | **Save File** | Ask Where to Save: **Off**. Destination: **iCloud Drive**. Subpath: `Bahri/Bahri-Operations-Console.html`. Overwrite If File Exists: **On** |

4. Tap **Done**, then tap the shortcut once.
5. Allow network access if asked.
6. Open the **Files** app → **iCloud Drive** → **Bahri**.

After that, tap **Save Bahri Console** any time you want a fresh copy.

To run it from Safari or Grok later:

`shortcuts://run-shortcut?name=Save%20Bahri%20Console`

## Shortcut 2 — Open Bahri Console (no file)

1. New shortcut named **Open Bahri Console**
2. One action: **Open URLs**
3. URL: `https://falconflexfit-art.github.io/bahri-operations-console/`
4. Add to Home Screen from the shortcut’s share menu if you want a home icon.

## Shortcut 3 — Share Sheet (GitHub → Files)

Use this when a file is already on screen (GitHub, Safari, Mail).

1. New shortcut named **Save to Bahri folder**
2. Tap **i** (info) → **Show in Share Sheet** → On. Receive **Files** and **URLs**.
3. Actions:

- **If** Shortcut Input *has any* URLs  
  - **Get Contents of URL** (from that URL)  
  - **Set Name** `Bahri-Operations-Console.html`  
  - **Save File** → iCloud Drive / `Bahri/` (Ask Where: Off, Overwrite: On)
- **Otherwise**
  - **Save File** → Shortcut Input → iCloud Drive / `Bahri/` (Ask Where: Off, Overwrite: On)

Then in GitHub or Safari: **Share → Save to Bahri folder**.

## Home Screen (optional)

Open the live console in Safari:

https://falconflexfit-art.github.io/bahri-operations-console/

Share → **Add to Home Screen**. That is not a file, but it is the fastest way to open it on iPhone.
