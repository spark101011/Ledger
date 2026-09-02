# Ledger

A private spend & income tracker. Works offline once installed, and everything
is saved on your own phone/browser — nothing goes to any server.

## Put it on GitHub Pages

1. Create a new GitHub repo (e.g. `ledger`).
2. Upload these 5 files to the repo root: `index.html`, `manifest.json`,
   `service-worker.js`, `icon-192.png`, `icon-512.png`.
3. In the repo, go to **Settings → Pages**, set Source to the `main` branch,
   root folder, and save.
4. GitHub gives you a link like `https://yourname.github.io/ledger/` —
   open that on your phone.
5. In your phone's browser menu, choose **Add to Home Screen**. It'll install
   like a normal app, with its own icon.

## Notes

- Your data lives only on the device you use it on (browser local storage).
  It does not sync between phone and PC automatically — they'd be separate
  ledgers unless you enter data on both.
- If you ever want to wipe it and start fresh, clearing the site's browsing
  data in your browser settings resets it.
