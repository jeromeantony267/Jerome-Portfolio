# Jerome Antony — Portfolio

A single-file HTML portfolio (all styles, scripts, and images are embedded — no build step needed).

## Files in this repo
- `index.html` — the entire site. **Must be named exactly `index.html`** and live at the root of the repo (or in the folder you pick as the Pages source) — this is the #1 cause of a 404 on GitHub Pages.
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing, which can otherwise fail the build on files with embedded scripts/CSS like this one.

## Deploying with GitHub Pages (step by step)

1. **Go to your existing repo** (e.g. `JeromeAntony-portfolio`) on github.com.

2. **Replace `index.html`**:
   - Click on `index.html` in the file list → click the **pencil (edit)** icon, or
   - Delete the old one and use **Add file → Upload files** to upload this new `index.html`
   - Commit the change (add a short message like "Update portfolio")

3. **Confirm `.nojekyll` exists** in the repo root:
   - If you don't see a file named `.nojekyll` in the file list, add it:
     - **Add file → Create new file** → name it exactly `.nojekyll` → leave it empty → **Commit changes**

4. **Check the build**:
   - Go to the **Actions** tab
   - Wait for the latest **"pages build and deployment"** run to finish with a green checkmark
   - If it fails (red X), click into it to read the error log

5. **View your site**:
   - Go to **Settings → Pages**
   - Your live URL will be shown at the top, typically:
     ```
     https://<your-username>.github.io/<your-repo>/
     ```

## If you get a 404
- Make sure `index.html` sits at the **top level** of the branch/folder selected in Settings → Pages (not inside a subfolder).
- Make sure the filename is exactly `index.html` (lowercase, no typos).
- Give it 1–2 minutes after commit — Pages redeploys automatically but isn't instant.
- Check the **Actions** tab for a failed build and read the specific error.

## Updating the site later
Just edit or replace `index.html` and commit again — GitHub Pages redeploys automatically within a minute or two. No other steps needed.
