# 🛡️ Interactive Penetration Testing Checklist

An interactive, customizable penetration testing checklist designed for security professionals and enthusiasts. This tool helps you track, document, and export your testing progress with ease.

## ✅ Features

- **Interactive Checkboxes**: Mark tests as completed with real-time progress tracking.
- **Add Notes**: Attach detailed notes to each test for documentation and reference.
- **Run Locally**: No server required; works completely offline in your browser.
- **Persistent Progress**: Progress is saved using IndexedDB, persisting even across browser closes/reopens (works with file:// protocol).
- **Export Progress**: Download your current state (completed tests + notes) as a JSON file for backup or sharing.
- **Import Progress**: Upload a previously exported JSON file to restore your state.
- **Reset Option**: Clear all progress with a single button click, including unchecking tests and wiping storage.
- **200+ Predefined Tests**: Covers a wide range of security checks based on OWASP Top 10 and custom vulnerabilities.
- **Search and Filter**: Quickly find tests by keyword, status (completed/pending/critical), or category.
- **Expandable Sections**: Collapse/expand categories and individual tests for better navigation.
- **Generate Reports**: Create on-demand summaries of completion stats, pending items, and critical missing tests.
- **Copy Payloads**: One-click copy for test payloads and commands.
- **Customizable**: Easily add or modify tests by editing the JSON data in `app.js`.
- **Easy Tracking**: Clean UI with progress bars, stats, and visual indicators for efficient workflow.

## 📂 Project Structure

- **`index.html`**: The main HTML file containing the structure and UI elements. Open this in your browser to run the app.
- **`style.css`**: Stylesheet for the app's layout, colors, and responsive design.
- **`app.js`**: Core JavaScript file handling logic, rendering, persistence (IndexedDB), import/export, and event listeners. Edit this to customize tests or features.
- **`README.md`**: This file—documentation and setup guide.

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Safari—tested on versions from 2025).
- No additional software needed; the app runs directly in the browser.

### Installation
1. Download or clone the repository to your local machine.
2. Unzip
3. Open `index.html` in your browser (double-click the file or drag it into a browser tab).
   - It works even with the `file://` protocol—no local server required.

### Usage
1. Open `index.html`—the checklist loads automatically with your saved progress (if any).
2. Browse categories, check off completed tests, add notes, and use the search/filter tools.
3. Click "Export Progress" to save your state as JSON (e.g., before closing the browser).
4. On reopen, click "Import Progress" to load a saved JSON file.
5. Use "Reset Progress" to start fresh.
6. Generate reports to review stats and missing critical tests.

For customization:
- Edit the `securityTestData` object in `app.js` to add/remove tests (JSON format).
- Modify CSS in `style.css` for visual tweaks.

## 📝 License
This project is licensed under the MIT License—feel free to use, modify, and distribute.

## 🙌 Acknowledgments
- Built with inspiration from OWASP Top 10 guidelines.
- Thanks to open-source tools like IndexedDB for persistence and browser APIs for seamless functionality.

Happy testing! 🔒
