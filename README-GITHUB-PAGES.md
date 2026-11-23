# Chef Jeannica Birthday Website — GitHub Pages

A static HTML/CSS/JavaScript website. No server, build step, or framework is required.

## Files to put in the repository root

- `index.html` — website
- `adoption-certificate.png` — Jenny adoption certificate (currently a sample preview; replace with the real certificate)
- `tree-certificate.png` — 33-tree certificate (currently a sample preview; replace with the real certificate)
- `jenny.png` — Jenny's photo (**add this file yourself**)
- `yellow.mp3` — your legally obtained MP3 audio file (**add this file yourself**)
- `.nojekyll` — tells GitHub Pages to serve files as-is

Keep the filenames exactly as written. The HTML uses relative asset paths (`./...`) so it works both at a repository root and at a GitHub Pages project URL.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `chef-birthday`).
2. Upload the files listed above to the repository's **root** (not inside another folder).
3. Commit and push the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the Pages deployment to finish. Open the URL shown in **Settings → Pages**.

If you update files later, commit and push the changes; GitHub Pages will publish the new version automatically.

## Website behavior

- `Run birthday.exe` opens the birthday wishes and attempts to start `yellow.mp3`.
- Browsers require the visitor's click to start audio. If the MP3 is missing, the rest of the website still works but music will not play.
- Enter `1453` on the Morse teaser to unlock Page 4.
- The PDF button combines the two certificate PNGs into a two-page PDF. It loads jsPDF from a CDN, so the visitor needs an internet connection. If the library is unavailable, the page falls back to the browser print dialog.

## Before publishing

- Add `jenny.png` and `yellow.mp3` to the repository root.
- Replace the two sample certificate PNGs with the actual certificates if available.
- Test the public Pages URL on both desktop and mobile.
- Do not upload private information or any audio/image file you do not have permission to publish. GitHub Pages sites are public unless you configure access through a supported private publishing arrangement.
