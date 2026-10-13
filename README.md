# ModaForge Starter

ModaForge is a beginner-friendly, mobile-responsive fashion studio prototype built with plain HTML, CSS, and JavaScript. No framework or build process is required.

## Included features
- Design concept form for garment type, silhouette, colour, and notes.
- Simple illustrative concept preview.
- Measurement sheet with CSV download.
- Rule-based ReStyle / upcycling suggestions.
- Saved projects stored in the current browser using `localStorage`.
- Beginner / Advanced mode toggle.
- Responsive layout for phones, tablets, and computers.

## Important limitations
This is an early front-end prototype, not a complete production app. It does **not** yet include construction-ready sewing pattern generation, validated pattern geometry, seam allowances, AI image recognition, photo-to-pattern conversion, real 3D garment simulation, cloud accounts, or cross-device syncing.

The measurement tool records values only. Accurate pattern drafting requires garment-specific drafting rules, ease, seam allowances, and fitting tests. Verify measurements and patterns before cutting valuable fabric.

## Run the app
1. Download and unzip this folder.
2. Open `index.html` in a modern browser.
3. Alternatively, upload the files to GitHub and publish with GitHub Pages.

## Upload to GitHub
1. Sign in to GitHub and create a repository, for example `modaforge-starter`.
2. In the repository, choose **Add file → Upload files**.
3. Upload `index.html`, `style.css`, `script.js`, and `README.md` from this folder (upload the files themselves, not the ZIP).
4. Commit the files to the `main` branch.

## Publish with GitHub Pages
1. Open repository **Settings**, then **Pages**.
2. Under build/deployment, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for GitHub to publish the site; the Pages screen will show the published address.

## Data and privacy
Saved projects stay in local storage in the browser on the device you use. They do not sync automatically to another device. Clearing browser storage may remove saved projects. Avoid storing sensitive customer information in this prototype.

## Suggested next stages
1. Add project editing and garment-specific measurement templates.
2. Implement tested drafting rules for basic pattern blocks.
3. Add reference image uploads and tutorials.
4. Build a backend and account system for secure syncing.
5. Explore advanced 3D previews and garment simulation.
