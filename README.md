# Jerome Antony - Portfolio

Live site: https://jeromeantony267.github.io/Jerome-Portfolio/

Single-file HTML portfolio. Styles, scripts, images and the downloadable resume are all embedded, so there is no build step.

## Files
- `index.html` - the whole site. Must be named exactly `index.html` and sit at the repo root.
- `.nojekyll` - tells GitHub Pages to skip Jekyll so the build does not fail.
- `README.md` - this file.

## Update the live site
1. Open the repo `Jerome-Portfolio` on github.com.
2. Click **Add file > Upload files** and drag in `index.html` and `.nojekyll` (same names replace the old ones).
3. Click **Commit changes**.
4. Open the **Actions** tab and wait for "pages build and deployment" to show a green check (about 1 minute).
5. Hard refresh the live link (Ctrl+Shift+R) to see the changes.

## Pages settings (already set)
Settings > Pages > Source: Deploy from a branch > Branch: `main`, Folder: `/ (root)`.

## If you see a 404 or an old version
- Confirm `index.html` is at the top level of the repo, not inside a folder.
- Check the Actions tab for a red X and open the log.
- Hard refresh or try a private window, since browsers cache the old page.
