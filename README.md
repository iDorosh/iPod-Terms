# Pocket Classic website

A build-free marketing, contact, and privacy page for Pocket Classic. All fonts are system fonts, all images are local, and the site has no JavaScript, analytics, cookies, or external embeds.

## Preview locally

From this folder:

```sh
python3 -m http.server 8080
```

Open http://localhost:8080.

## Publish with GitHub Pages

1. Create a GitHub repository and push this repository's `main` branch to it. Alternatively, upload `index.html`, `styles.css`, `.nojekyll`, and the `assets` folder to the repository root.
2. In the GitHub repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main**, **/ (root)**, then **Save**.
5. GitHub will show the published URL on that page after deployment.

Use the published URL for your marketing page, append `#contact` for support, and append `#privacy` for the privacy policy. Relative asset links work with both repository Pages URLs and a custom domain.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Content

- Contact: ian.dorosh@outlook.com (in the contact section and privacy policy).
- App screenshots use fictional music and original demo artwork.
- The privacy policy is based on the current app source: MusicKit library and playback integration, local preferences, saved Solitaire progress, and a local Brick Breaker high score. Update it before shipping changes to data handling.
- Add the real App Store listing link once available. The current page does not show an unverified download button.

This repository is prepared for GitHub Pages; creating the local repository does not publish it or create a GitHub remote.
