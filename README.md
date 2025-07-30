# Journal with LaTeX Preview

A lightweight browser-based journal app. Write entries with rich formatting and LaTeX math, and save everything locally—no backend required.

---

## Features

- **Basic formatting**  
  Bold, italic, underline, and bullet lists using a contenteditable editor.

- **Smart list behavior**
  - Type `-` and hit space to start a bullet list
  - Use `Tab` / `Shift+Tab` to indent or outdent
  - Press `Enter` on an empty bullet to outdent

- **LaTeX support**
  - Supports inline math: `$...$` or `\(...\)`
  - Display math: `$$...$$` or `\[...\]`
  - Preview rendered output using [KaTeX](https://katex.org/)

- **Local storage**
  - Save, load, and delete entries
  - All entries are saved in your browser using `localStorage`

- **Titles**
  - Auto-generates a title based on your first few lines
  - Or lets you set one manually

- **Responsive layout**
  - Works well on desktop and mobile

---

## How It Works

- Write in the editor panel.
- Click **LaTeX Preview** to render math and content.
- Click **Back to Editor** to return to editing.
- Click **Save** to store your entry.
- Click **New Entry** to clear the editor.
- View saved entries in the sidebar and click to load or delete them.

---

## Tech Stack

- HTML / CSS / JavaScript (no frameworks)
- [KaTeX](https://katex.org/) via CDN
- `localStorage` for data persistence
