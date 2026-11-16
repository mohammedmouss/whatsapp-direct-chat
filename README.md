# WA Direct — WhatsApp Direct Chat

A lightweight mobile-friendly web app to start a WhatsApp conversation with a phone number **without saving the contact**.

## Features

- Opens chats through WhatsApp's official `wa.me` links.
- Supports international phone numbers and country-code selection.
- Copy/paste phone numbers directly from the clipboard.
- Responsive dark green design.
- Progressive Web App (manifest and service worker) for home-screen access.
- Processes phone numbers in the browser; no server database is required.

## Run locally

Serve the files through an HTTP server:

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Upload the files to the document root of an HTTPS-enabled static hosting service. The service worker requires a secure context (HTTPS or localhost).

## Live website

https://whatsapp.mohammedmoussaoui.be/

_Not affiliated with WhatsApp or Meta._