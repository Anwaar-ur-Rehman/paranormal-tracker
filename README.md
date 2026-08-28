## Description
**Paranormal Tracker** is a custom web application designed for recording and exploring paranormal sightings and ghostly events. 

Built completely with **native Node.js modules** (`http`, `fs`, `path`), this project avoids heavy back-end frameworks like Express to ensure lightweight performance and raw HTTP routing mechanics. Front-end components utilize modular JavaScript, dynamic rendering, and custom light/dark theme aesthetics.

### Features
* **Native Node.js Routing:** Handled using core modules without external server frameworks.
* **REST API:** Supports GET requests to retrieve sightings and POST requests to log new entries.
* **Security & Sanitization:** Uses `sanitize-html` to clean user input and protect against XSS vulnerabilities.
* **Dynamic Content:** Form submissions append directly to JSON storage and update the UI in real-time.
