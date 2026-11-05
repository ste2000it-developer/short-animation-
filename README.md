# Sprite Studio

Static HTML/CSS/JavaScript cutout sprite editor. Open through GitHub Pages.

Features: image import, rectangle/polygon cutting, transparent sprite extraction, layers, transforms, per-sprite pivot editing, reference overlay, undo/redo, IndexedDB local saves and portable project JSON export.

## Development

Serve the repository root through an HTTP server (ES modules require HTTP). No build step or Firebase required.

## Notes

Project JSON embeds images as data URLs. Local autosaves are browser-specific. GitHub Pages must be configured to deploy from main / root in repository settings.
