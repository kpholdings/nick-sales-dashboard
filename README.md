# Nick Sales Dashboard

Password-gated, read-only sales dashboard published through GitHub Pages.

The sales payload in `data.enc.json` is encrypted with AES-256-GCM. The access password is never committed, transmitted to the site, or stored by GitHub Pages. Decryption happens locally in the authorized user's browser.

This repository intentionally contains no plaintext lead emails, customer names, or NetSuite order identifiers.
