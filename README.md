# JSON Formatter

A simple and lightweight JSON formatter and validator built with [Monaco Editor](https://microsoft.github.io/monaco-editor/).

## Features

-   **Dark Theme**: Uses the `vs-dark` theme for comfortable reading.
-   **Architecture**: Single file (`index.html`), no build step required. Uses CDN for Monaco Editor.
-   **JSON Validation**:
    -   **Real-time Validation**: Checks JSON validity as you type.
    -   **Sticky Status Bar**: Displays JSON validation status at the bottom.
-   **Auto-Formatting**:
    -   **Format Button**: Explicitly format JSON with a button click.
    -   **Auto-Format on Paste**: Automatically detects valid JSON upon pasting and formats it. Invalid JSON is left untouched to preserve error context.
-   **Word Wrap**: Toggle word wrapping on/off with a checkbox in the toolbar.

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
