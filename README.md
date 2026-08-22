# Sharable Bible Reading Plan

A private-beta Codex plugin for personal, resumable Bible reading with contextual study and progress tracking in Google Sheets.

## What it does

- Lets each reader choose their starting passage, translation, and session length.
- Gives concise literary, historical, cultural, Hebrew, and Greek context.
- Creates a separate **My Bible Reading Journey** Google Sheet for each user.
- Continues from the user's saved stopping point without guilt or catch-up assignments.
- Keeps every user's Google Sheet and reading history private and independent.

## Install the private beta from GitHub

The repository must first be published to GitHub. Then the reader can add its marketplace in Codex:

```powershell
codex plugin marketplace add YOUR-GITHUB-USERNAME/sharable-bible-reading-plan
```

Restart the ChatGPT desktop app, open the Plugins Directory, select the **Personal** marketplace, and install **Sharable Bible Reading Plan**.

## Install the private beta from a ZIP

If Micah sends you the ZIP directly:

1. Extract the ZIP to a permanent folder.
2. Ask Codex: **"Add the plugin marketplace in this folder and install Sharable Bible Reading Plan."**
3. Attach or provide the extracted folder when Codex asks for it.
4. Restart the ChatGPT desktop app, open the Plugins Directory, select **Personal**, and install **Sharable Bible Reading Plan**.

Connect Google Drive when prompted. The plugin needs that connection only to create and update the reader's own progress Sheet.

## Start reading

Open a new task and say:

> Use Sharable Bible Reading Plan to set up my personal Bible reading plan.

The plugin will ask where to begin, whether to use ESV, and whether a 10–15 minute session works.

## Privacy

The plugin does not include Micah's progress, Sheet URL, or reading history. Each reader authorizes their own Google Drive and receives their own Sheet. See [PRIVACY.md](PRIVACY.md).
