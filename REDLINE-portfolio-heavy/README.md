# REDLINE — Heavy Cinematic Portfolio

A responsive one-page video-editing portfolio with a full-screen brutalist intro sequence, oversized hard-cut typography, red scanline, progress bar, grain texture, auto-enter after 4.8 seconds, Enter button and Escape/skip controls. The main portfolio has cinematic motion, black and blood-red colours, animated headline entrances, sweeping project-card highlights, a rotating showreel backdrop, scroll reveals, filters, and working video-preview modals.

## Run locally
Extract the ZIP and open `index.html` in a browser. No build process, package installation, or paid libraries required. Internet access is needed for Google Fonts and remote sample photography.

## Personalize before going public
Search and replace in `index.html`:
- `ADITYA ACHARYA` — your preferred display name.
- `your.email@example.com` — your real contact email.
- `href="#"` on `id="ig"` and `id="yt"` — your actual social URLs.
- `data-video=""` on each project `<article>` — a YouTube URL, Vimeo URL, or direct MP4 URL. Click the card to open the video modal.
- `data-video=""` on `id="reelButton"` — your showreel URL.
- Project names, descriptions, categories and poster imagery — replace the six demo cards with your actual work.
- Intro headline — edit `ADITYA` and `ACHARYA` inside `#introGate` to change the title sequence.
- Intro duration — change `4800` in the `setTimeout` near the intro script to adjust the automatic intro duration (milliseconds).

The current card names and photos are visual placeholders; do not present them as completed client work. Replace them with your own edits. For best performance, use compressed poster images and video embeds hosted on YouTube/Vimeo rather than uploading very large MP4s to static hosting.

## Free Netlify deployment
1. Extract the ZIP on your computer.
2. Open https://app.netlify.com/drop and sign in/create a free account if prompted.
3. Drag the extracted `REDLINE-portfolio-heavy` folder (or the files inside it) into Netlify Drop.
4. Use the generated `*.netlify.app` public URL.
5. For later updates, upload the updated folder again or connect a Git repository.

Netlify's free plan is subject to current usage limits. A custom domain is optional and typically costs extra.
