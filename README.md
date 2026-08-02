# Marvel Journey 2.0.1 Safari Fix

Upload all six files directly to the root of the existing GitHub repository.

This update removes reliance on automatic HTML-ID JavaScript globals and reserved names such as `import` and `export`, which prevented the application script from initializing in Safari.

Files:
- index.html
- config.js
- reading-lists.js
- manifest.webmanifest
- service-worker.js
- README.md
