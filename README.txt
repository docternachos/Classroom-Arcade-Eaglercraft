EAGLERCRAFT LAUNCHER
====================

Open index.html through a web server and select a game.

Folders:
- eaglercraft-1.8.8/
- eaglercraft-1.12.2/

The uploaded ZIP contained Git LFS pointer files in place of both game index.html files.
Those two index pages were rebuilt to load each folder's bootstrap.js and assets.epw.

IMPORTANT:
Modern browsers may block game assets if you double-click index.html and use a file:// URL.
For best results, serve this folder with a normal local/web HTTP server.

Example with Python installed:
  python -m http.server 8000

Then open:
  http://localhost:8000
