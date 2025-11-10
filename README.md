# Leads Tracker Extension

Leads Tracker Extension is a simple Chrome extension that helps you save and manage URLs (leads) directly from your browser. You can save the current tab, add custom URLs, and delete all saved leads. All leads are stored in your browser's local storage for persistence.

## Features

- Save the current tab's URL with one click
- Add custom URLs manually
- View all saved leads as clickable links
- Delete all saved leads with a double-click
- Persistent storage using localStorage

## Usage

1. Enter a URL in the input field and click "SAVE INPUT" to add it to your leads list.
2. Click "SAVE TAB" to save the URL of your current browser tab.
3. Double-click "DELETE ALL" to remove all saved leads.
4. All saved leads are displayed as clickable links below the buttons.

## Files

- `index.html`: Main HTML structure for the extension popup
- `index.css`: Styles for the extension popup
- `index.js`: JavaScript logic for saving, displaying, and deleting leads
- `manifest.json`: Chrome extension manifest file
- `README.md`: Project documentation

## Installation

1. Clone this repository.
2. Go to `chrome://extensions/` in your browser.
3. Enable "Developer mode".
4. Click "Load unpacked" and select the project folder.
5. The extension will appear in your browser toolbar.

## License

MIT
