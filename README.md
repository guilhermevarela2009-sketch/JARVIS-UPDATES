# JARVIS Updates

Public update feed for the JARVIS desktop app.

- `update.json` describes the latest version, package URL, SHA-256 digest, and release notes.
- Versioned ZIP files contain only the app files needed to update an existing installation. Voice models and local settings stay on the user's computer.

The app downloads updates over HTTPS, checks the package digest, stages the files, backs up replaced files, and restarts its local Python server.