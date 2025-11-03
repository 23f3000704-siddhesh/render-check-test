# API Response Test Web App

## Overview
This is a minimal, client-side web app used to verify that an API successfully returned a runnable web page. It provides a small diagnostics suite to validate essential browser capabilities:
- JavaScript runtime
- DOM readiness
- Web Crypto random token generation
- LocalStorage read/write
- High-resolution timer
- Basic fetch capability to the current page

The app generates a run ID and a session token for traceability and allows copying a JSON report of the results.

## Setup
No build tools are required.

Option A: Open directly
- Download index.html
- Double-click to open in your browser
- Note: Some fetch checks may be skipped in file:// contexts due to browser restrictions

Option B: Serve with any static server
- Using Node.js: npx serve .
- Using Python: python3 -m http.server 8080
- Visit http://localhost:8080

## Usage
- Open index.html in a modern browser
- The diagnostics run automatically on page load
- Click "Run Test" to re-run diagnostics
- Click "Copy Report JSON" to copy a structured report of results
- "Reset" clears the current UI state

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.