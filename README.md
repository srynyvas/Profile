# Sreenivas PN - Portfolio Website

Personal portfolio website built with Hugo and deployed via GitHub Pages.

## Live Site

[https://srynyvas.github.io/Profile/](https://srynyvas.github.io/Profile/)

## Tech Stack

- **Static Site Generator:** Hugo
- **Theme:** PaperMod (dark/light toggle)
- **Hosting:** GitHub Pages
- **CI/CD:** GitHub Actions

## Structure

```
Profile/
├── config.toml              # Hugo configuration
├── content/
│   ├── _index.md           # Home page
│   ├── about.md            # About me
│   ├── experience/         # Work experience
│   ├── skills.md           # Technical skills
│   ├── projects.md         # Projects & achievements
│   └── education.md        # Education & certifications
├── static/
│   ├── images/             # Profile photo, etc.
│   └── resume/             # Downloadable resume
├── themes/PaperMod/        # Hugo theme
└── .github/workflows/
    └── deploy.yml          # CI/CD pipeline
```

## Local Development

1. Install Hugo: `brew install hugo`
2. Clone with submodules: `git clone --recurse-submodules <repo>`
3. Run locally: `hugo server -D`
4. Open: http://localhost:1313/Profile/

## Deployment

Push to `main` branch triggers automatic build and deployment via GitHub Actions.

## Customization

- Edit markdown files in `content/` to update content
- Modify `config.toml` for site settings
- Add profile photo to `static/images/profile.jpg`
- Add resume PDF to `static/resume/`

## Author

**Sreenivas PN**
Senior Machine Learning Engineer
[LinkedIn](https://in.linkedin.com/in/srynyvas) | [Email](mailto:sreenivas.workmail@gmail.com)
