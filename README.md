# readmeter

Chrome extension that tracks reading time per tab

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Highlights

- No remote calls, everything stays local
- Popup shows today's total focus time
- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
