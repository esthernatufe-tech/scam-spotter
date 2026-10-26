# 🕵️ Scam Spotter

A free, single-file simulator that teaches kids and teenagers to spot **phishing** (email), **smishing** (text messages) and **vishing** (phone calls).

- 10 scenarios: 3 phishing emails, 3 smishing texts, 3 vishing calls, plus 1 legitimate email
- Mailbox, messages and phone-style interface
- Audio for vishing calls (uses the browser's built-in text-to-speech)
- Tap the red flags, decide "scam" or "safe", earn points and a detective badge
- No tracking, no dependencies, no data collected. Everything runs in the browser.

## Run it
Open `index.html` in any modern browser.

## Host it on GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Customise
All scenarios live in the `S` array near the top of the `<script>` in `index.html`. Each text part is `[text, explanation]`; use `0` as the explanation for harmless text. All brand names are fictional.

## License
MIT. Free to use in classrooms, workshops and community sessions.
