# QR Forge

A free QR code generator that runs entirely in the browser: no sign-up, no server, nothing you type leaves the page.

**Live:** https://usmanfiaz06.github.io/QR-code-/

## What it makes

| Type | What happens on scan |
|---|---|
| Link | Opens the website |
| Contact card | Offers **Add to contacts** (vCard 3.0: name, company, title, phones, emails, websites, socials, address, birthday, note) |
| Wi-Fi | Joins the network, no typing |
| WhatsApp | Opens a chat with your message pre-filled |
| Email | Opens a new email with recipient, subject and body |
| Call / SMS | Starts a call or an SMS |
| Location | Opens Google Maps |
| Event | Offers **Add to calendar** |
| Text | Shows the text |

## Design

- 9 one-click presets
- 7 module shapes, 4 corner frames, 5 corner centres
- Solid, linear or radial gradient fill; custom corner colours; transparent background
- Centre logo with size, white plate and clear-area options (damage tolerance locks to Max)
- Call-to-action frames ("SCAN ME", "SAVE MY CONTACT", …)
- Live scan check: contrast, quiet zone, density, logo size and minimum print size

## Export

PNG, SVG and JPG up to 4096 px, copy image to clipboard, and `.vcf` for contact cards. Designs can be saved to **My codes** (stored in your browser).

## Run locally

It's a single file: open `index.html` in any modern browser.

QR encoding uses [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) (MIT), loaded from jsDelivr.
