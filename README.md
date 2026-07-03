# psy_aru — Аружан Смагулова, практикующий психолог

Static one-page booking/landing site. Single `index.html`, all CSS inline, no build step. Hosted on GitHub Pages.

## Editing
Edit `index.html` and push to `main`. GitHub Pages redeploys in ~1–2 min.

## To finish (placeholders in the HTML, search for "Заменить" / "Добавить")
- **Photo** — add `assets/aruzhan.jpg` and replace the `.portrait` "Фото" block with `<img src="assets/aruzhan.jpg" alt="Аружан Смагулова">`.
- **Diplomas** — add scans to `assets/` and replace the `.edu-doc` placeholder frames with `<img>`.
- **Booking link** — set the `href` on the "Забронировать слот" button (`data-role="booking-link"`) to her booking tool (Calendly / form / Telegram).
- **Contacts** — add Telegram / Instagram / email in the footer.

## Domain
Custom domain via Cloudflare (buy `psyaru.com` or `psy-aru.com` — no underscores allowed in domains — plus `aruzhansmagulova.com`). Point the canonical domain at GitHub Pages; redirect the other at Cloudflare.
