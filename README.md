# focusfolio

MV3 extension playground: page reading-time estimator

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Features

- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- Manifest V3, service worker based

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── config.js
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## Known issues

- none reported yet (surprisingly)

## License

MIT. Do whatever you want.
