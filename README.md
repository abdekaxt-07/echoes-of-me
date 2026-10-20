# MY FAV PLAYLISTE

A responsive, dark red-and-black music showcase built with plain HTML, CSS, and JavaScript. No build tools, backend, API key, or database are required.

## Files

- `index.html` — complete website (CSS and JavaScript included).
- `README.md` — these instructions.

## Open locally

1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. An internet connection is needed for YouTube links and thumbnails.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository. For a personal site, the repository can be named `my-fav-playliste`.
2. Upload `index.html` and `README.md` to the repository's root folder (not inside another nested folder).
3. Open the repository's **Settings**.
4. Select **Pages** in the sidebar.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages settings. For a project repository it commonly follows `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Troubleshooting

- **Blank page:** ensure the file is named exactly `index.html` and is in the repository root. Check the repository's **Actions** tab and the Pages deployment status.
- **Missing thumbnails:** thumbnails are loaded from YouTube's `img.youtube.com` host and require internet access. If a thumbnail fails, the card displays a built-in dark red fallback.
- **Track or playlist does not open:** check that the device has internet access. Each card opens the supplied YouTube video or playlist in a new tab.
- **Website changes are not visible:** refresh the page, wait for GitHub Pages to redeploy, or try a private browser tab.

## Notes

The site contains 19 tracks and 5 playlists. The only supplied verified track metadata is Eminem — “When I'm Gone” for video ID `1wYNFfgrXTI`; other track and playlist names are shown with neutral placeholders rather than guessed. Cards link directly to YouTube; no embedded player or visitor editing controls are included.
