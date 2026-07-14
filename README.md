# Bryan John — Portfolio

A single-page, dark-mode personal portfolio built with plain HTML, CSS, and
vanilla JavaScript. No frameworks, no build step — works as-is on GitHub Pages.

## Folder structure

```
portfolio/
├── index.html        # All page markup and section content
├── css/
│   └── style.css      # All styling (design tokens at the top of the file)
├── js/
│   └── script.js       # Nav toggle, scroll reveal, back-to-top, footer year
├── assets/
│   └── resume.pdf      # Placeholder — replace with your real resume
└── images/              # Put a real profile photo here if you have one
```

## Customizing

- **Colors / fonts / spacing:** edit the `:root` variables at the top of
  `css/style.css`.
- **Photo:** replace the SVG placeholder in the hero section of `index.html`
  with `<img src="images/profile.jpg" alt="Bryan John">`.
- **Resume:** replace `assets/resume.pdf` with your actual file (keep the
  same filename, or update the `href` in `index.html`).
- **Contact links:** update the email, GitHub, and LinkedIn `href` values in
  the Contact section of `index.html`.
- **Certifications:** duplicate a `.cert-card` block in the Certifications
  section and fill in the real title, issuer, and date.

## Deploying to GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repo settings, go to **Pages** → set the source to the branch and
   root folder containing `index.html`.
3. Your site will be live at `https://<username>.github.io/<repo-name>/`.
