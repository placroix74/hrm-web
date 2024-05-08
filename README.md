# HRM-WEB
An interactive, browser-based [Human Resource Machine](https://tomorrowcorporation.com/humanresourcemachine) simulator.

## Why?
The game did not come with [a level editor](https://steamcommunity.com/app/375820/discussions/0/351659808488235380/).

## Prior Art
- https://github.com/ymizushi/hrm-js : non-interactive(?), Node.js-based

## Features
- Everything on _one page_ : software and help text.
- Levels load from a JSON file.
  - Every level from the original game included. (Is this legal?)

## Installation
1) [Download the current master](https://github.com/placroix74/hrm-web/archive/refs/heads/master.zip).
1) Extract and navigate to the extraction directory.
1) Launch a basic HTTP server, e.g. if you have Python 3 installed:
   ```
   python -m http.server
   ```
1) Open a browser to `locahost:<port>`, e.g.: Python `http.server`'s default port is 8000.

## Tech
- HTML/CSS
- Javascript
- [jQuery](https://jquery.com/)

## Development
Want to contribute? Great! See [open issues](https://github.com/placroix74/hrm-web/issues).

## License

MIT

**Free Software, Hell Yeah!**
