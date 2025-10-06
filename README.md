# SHREE BALAJI COACHING CENTER — Static Website

This is a small, responsive, modern landing page built with HTML, Tailwind CSS (CDN), and vanilla JavaScript. It features a glassmorphism UI and a dark-mode toggle.

Files
- `index.html` — main site
- `assets/hanuman.svg` — small emblem used in the header

How to use
1. Open `index.html` in a browser (double-click or via "Open With" in your editor).
2. Use the "Admission Open" or "Enquire" button to access the contact form.
3. Fill the form and click "Send via Email" — this will open your default mail client with a composed message to `ankit123418@gmail.com` using a `mailto:` link.

Notes
- No backend is used. The form uses a `mailto:` link to open the user's mail client. If the user doesn't have a mail client configured, the link may do nothing or open a web mail service depending on the system.
- Tailwind is loaded from CDN for simplicity. For production, consider compiling Tailwind locally and purging unused styles.
- Feel free to replace `assets/hanuman.svg` with a higher-fidelity image or logo.

Customization ideas
- Add Google Fonts by including a `<link>` in the head.
- Add more sections (faculty, timetable, fees) as needed.

Enjoy!
