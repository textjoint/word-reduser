# Word Reduser - Lexical Compression Engine

Shorted long words to 3,4 or 5 letters while keeping them recognizable.

* now accepts input via url and updates url for convenient sharing.

## Quick Start with npx

Serve the page directly with npx:

```bash
# Using serve (recommended)
npx serve -p 8080

# OR using http-server
npx http-server -p 8080 -c-1
```

Then open `http://localhost:8080` in your browser.

## Using npm scripts

If you want to use npm scripts after installation:

```bash
npm start        # Starts the development server on port 8080
npm run serve    # Alternative using http-server
```

## What's included

- `package.json` - Project configuration with npm scripts
- `server.js` - Optional Node.js server (not required with npx)
- `index.html` - Main page with Lexical Compression Engine UI

## Requirements

- Node.js (for npx command)
- Modern web browser
