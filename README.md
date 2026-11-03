# John Knight's professional website

Static GitHub Pages site for John Knight, covering AI platform and infrastructure engineering leadership, professional experience, research, open source, education, and writing.

Live site: [jknight137.github.io](https://jknight137.github.io/).

## Local preview

No build step or dependency installation is required. From this directory:

```sh
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). The site also works when opening `index.html` directly.

## Content and maintenance

- `index.html`: public profile, career chronology, attributed career metrics, projects, credentials, and contact links.
- `styles.css`: responsive layouts, color and typography variables, keyboard focus styles, reduced-motion support, and print layout.
- `favicon.svg`: site monogram.
- `images/`: existing product artwork.
- `_archive/`: retained historical material, excluded by the default GitHub Pages/Jekyll handling of underscore-prefixed directories. Do not enable `.nojekyll` without reviewing this content.

The November 2026 refresh uses the supplied professional resume for current roles, dates, scope, results, and education. Project descriptions reference the linked repositories. Existing writing titles, independent product, and public contact alias are retained. The personal phone number and resume file are not published.

Update visible role information, the profile-update date, page description, Open Graph metadata, and Person structured data together when employment changes. Keep the Ph.D. explicitly marked as in progress. Attribute metrics to the employer where the work occurred, and keep research descriptions distinct from claims of validated findings.

## Publishing

The existing site uses GitHub Pages. Review and merge changes into its configured publishing branch through a pull request. Preserve the existing Pages settings and the repository's archive handling.

## Checks

Check desktop and mobile layouts, keyboard navigation, the earlier-career disclosure, local assets, section anchors, and outbound link destinations. No client-side JavaScript, external fonts, analytics, or runtime services are required.

© 2026 John Knight. All rights reserved.
