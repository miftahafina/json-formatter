# JSON Formatter

A simple and lightweight JSON formatter and validator built with [Monaco Editor](https://microsoft.github.io/monaco-editor/).

## Features

### Editor
-   **Monaco Editor**: Full-featured code editor with syntax highlighting, auto-completion, and bracket matching.
-   **Dark / Light Theme**: Toggle between `vs-dark` and `vs` themes with the 🌙/☀️ button.
-   **Word Wrap**: Toggle word wrapping on/off with a checkbox in the toolbar.
-   **Tab Size**: Uses 2-space indentation by default.

### Tabs
-   **Multiple Tabs**: Work with multiple JSON documents simultaneously.
-   **New Tab**: Click the "+" button to create a new tab.
-   **Close Tab**: Click the "×" button on any tab to close it. At least one tab is always kept open.
-   **Rename Tab**: Double-click on the active tab name to rename it.
-   **Persistent Tabs**: All tabs and their contents are saved to `localStorage` and restored on reload.

### JSON Tools
-   **Format JSON**: Beautify/pretty-print JSON with a single click.
-   **Minify JSON**: Compress JSON by removing all whitespace.
-   **Auto-Format on Paste**: Automatically formats valid JSON upon pasting. Invalid JSON is left untouched.
-   **Copy All**: Copy the entire editor content to clipboard with visual feedback.
-   **Undo / Redo**: Full undo/redo support per tab.
-   **Better Align**: Select text and press `Alt+A` to align by `:`, `=`, `=>`, or `->`.

### Validation & Navigation
-   **Real-time Validation**: Checks JSON validity as you type with status bar indicator.
-   **JSON Path Breadcrumb**: Shows the current cursor position in the JSON tree (e.g., `root › items › [2] › name`) with color-coded keys and array indices.
-   **Status Bar**: Displays JSON validation status at the bottom (blue for valid, red for invalid).

### Architecture
-   **Single File**: Everything in one `index.html`, no build step required.
-   **CDN-based**: Uses Monaco Editor via CDN, no local dependencies.
-   **Offline-friendly**: Works without internet after initial load (Monaco is cached by the browser).

## How to Use

Simply open the `index.html` file in any modern web browser.

```bash
# Clone the repo
git clone https://github.com/miftahafina/json-formatter.git

# Open the file
open index.html # on macOS
# or double click index.html
```

## Technologies

-   HTML5, CSS3, Vanilla JavaScript
-   Monaco Editor (via CDN)

## License

MIT
