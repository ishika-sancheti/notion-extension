# Notion Text Extension

A lightweight Chrome extension that improves readability in Notion by increasing text size across pages, headers, and lists.

## Overview

Notion is an excellent productivity tool, but some users may find the default text size too small for long reading or note-taking sessions.  

**Notion Text Extension** enhances the reading experience by automatically enlarging text elements within Notion pages, making content easier to read without manually adjusting browser zoom.

## Features

- Increases default Notion text size
- Enhances readability for long-form content
- Adjusts headings for better visual hierarchy
- Improves bullet and numbered list readability
- Lightweight with zero configuration
- Automatically applies when visiting Notion

## How It Works

The extension injects custom CSS into Notion pages and overrides default text styles for:

- Main page content
- Standard text blocks
- Headers
- Subheaders
- Nested headers
- Bulleted lists
- Numbered lists

## Tech Stack

- **JavaScript**
- **CSS**
- **Chrome Extension Manifest V3**

## Project Structure

```text
notion-extension/
├── manifest.json      # Chrome extension configuration
├── content.js         # Injected script for Notion pages
└── styles.css         # Custom styling overrides
```

## Installation

### Install Locally in Chrome

#### 1. Clone the Repository

```bash
git clone https://github.com/ishika-sancheti/notion-extension.git
```

#### 2. Open Chrome Extensions

Go to:

```text
chrome://extensions/
```

#### 3. Enable Developer Mode

Turn on **Developer Mode** using the toggle in the top-right corner.

#### 4. Load the Extension

Click **Load unpacked** and select the cloned project folder.

#### 5. Open Notion

Visit:

https://www.notion.so

The extension will automatically apply the styling changes.

## Example Style Changes

| Element | Updated Font Size |
|--------|------------------|
| Main Content | 20px |
| Text Blocks | 20px |
| Headers | 28px |
| Subheaders | 22px |
| Nested Headers | 20px |
| Lists | 20px |

## Permissions

This extension only runs on:

```text
https://www.notion.so/*
```

It does not:

- collect user data
- store personal information
- communicate with external servers
- require unnecessary permissions

## Future Improvements

Possible enhancements:

- Adjustable font size controls
- Extension popup UI
- Dark mode typography tuning
- Support for custom fonts
- Per-user preferences
- Support for additional Notion domains

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Author

**Ishika Sancheti**

GitHub: https://github.com/ishika-sancheti
