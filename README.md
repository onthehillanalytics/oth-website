# On The Hill Analytics – Website

Personal website for [onthehillanalytics.com](https://onthehillanalytics.com), hosted on **Squarespace**.

## Overview

Since the site is hosted on Squarespace, there's no traditional codebase to deploy. Instead, this repo serves as a home for:

- **Content drafts** – blog posts, page copy, and other written content before it goes live
- **Custom code** – any CSS or JavaScript injected via Squarespace's Code Injection or Code Block features
- **Assets** – images, graphics, or other media being prepped for upload
- **Design decisions** – notes and references tracking the look, feel, and direction of the site

## How It Works

Squarespace manages hosting, templates, and the CMS. Changes to the site's structure and design are made directly in the Squarespace editor. This repo complements that by version-controlling anything that *can* be tracked — primarily custom code snippets and content.

### Custom Code

Squarespace supports injecting custom code in a few places:

- **Settings > Advanced > Code Injection** – site-wide header/footer scripts and styles
- **Individual page/block code blocks** – per-page custom HTML, CSS, or JS

Any custom code used on the site lives in the `/custom-code` directory here, organized by location.

### Content

Draft blog posts and page copy can be written in Markdown here and then transferred to Squarespace when ready.

## Structure (planned)

```
/
├── custom-code/
│   ├── header-injection.html
│   ├── footer-injection.html
│   └── pages/
├── content/
│   └── posts/
└── assets/
```

## Notes

- The Squarespace template/theme itself is not version-controlled here (Squarespace manages that)
- Any API integrations or third-party embeds are documented in `/custom-code`
