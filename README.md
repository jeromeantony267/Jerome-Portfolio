# Jerome Antony — UX/UI Designer Portfolio

Personal portfolio of **Jerome Antony**, a Bangalore-based UX/UI and product designer.

**Live site:** https://jeromeantony267.github.io/Jerome-Portfolio/

## About this repo

This is a plain static website (HTML, CSS and a little JavaScript). There is nothing to install or build.

The empty `.nojekyll` file tells GitHub Pages to serve the files as they are, without running Jekyll.

## Contents

```
.
├── index.html        # The portfolio page
├── .nojekyll         # Tells GitHub Pages not to use Jekyll
├── robots.txt
├── sitemap.xml
├── README.md
└── assets/
    ├── css/main.css  # All styles (colours are variables at the top)
    ├── js/main.js    # Scroll animations + poster lightbox
    ├── files/        # Resume PDF
    └── images/       # Case studies, posters, profile photo
```

## Publish on GitHub Pages

1. Create a repository named `Jerome-Portfolio`.
2. Upload **all files and folders from this package**, including the hidden `.nojekyll` file, to the root of the repo.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute or two the site is live at `https://<username>.github.io/Jerome-Portfolio/`.

## Update the site

- **Text:** edit `index.html` directly (use GitHub's pencil icon or any code editor).
- **Colours and fonts:** edit the `:root` variables at the top of `assets/css/main.css`.
- **Images:** replace the files in `assets/images/` using the same file names, or update the paths in `index.html`.
- **Resume:** overwrite `assets/files/Jerome_Antony_UX_UI_Resume.pdf`.

### Note on file paths

Links to CSS, JS and images start with `/Jerome-Portfolio/`, which matches a repo named `Jerome-Portfolio`. If you use a different repo name, find and replace `/Jerome-Portfolio/` in `index.html`, `robots.txt` and `sitemap.xml`. If you host on a user site named `<username>.github.io`, remove that prefix.

## Contact

- Email: jeromeantony267@gmail.com
- LinkedIn: https://www.linkedin.com/in/jeromeantony
- Behance: https://www.behance.net/jeromeantony2

© Jerome Antony. Case-study and poster artwork belongs to the respective clients and projects (Mahindra First Choice, Ediig, Talview) and is shown for portfolio purposes only.
