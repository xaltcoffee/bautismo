# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands
This is a static website. No build or installation process is required.
- Run locally: Open `index.html` in any modern web browser.
- Admin Panel: Access via the "Acceso Organizadores" link in `index.html` or by opening `admin.html`.

## Architecture and Structure
The project is a static frontend application for a Baptism invitation (Bautismo de Grettel).

- `index.html`: The main entry point. It contains:
    - The invitation landing page with animations and music.
    - An RSVP form that saves guest data to Firebase Firestore.
    - A built-in admin dashboard (accessible via password) for managing RSVPs.
- `admin.html`: A standalone admin management page (Note: references to `js/` files may be missing).
- Assets: 
    - `musicaBautismo.mp3`: Background audio.
    - `tin1.png`, `Tinker-Bell-PNG.png`: Visual assets for the "fairy" theme.
- Backend: Uses **Firebase Firestore** for storing and retrieving RSVP responses.
