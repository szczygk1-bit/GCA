# Personal Website Template

A clean, professional starter template for a student or early-career academic
personal website. Students can fork this repository, replace the placeholder
content, and publish their site with GitHub Pages using their GitHub Education
account.

## What's inside

```text
.
├── index.html              # homepage
├── assets/
│   ├── css/style.css       # colors, layout, typography
│   ├── js/main.js          # small client-side helpers
│   └── images/
│       └── profile.svg     # placeholder portrait image
├── projects/
│   └── project-one.html    # example project page
├── cv/
│   └── README.md           # replace with cv.pdf
├── .nojekyll               # GitHub Pages compatibility
└── README.md               # setup instructions
```

## Quick start

### 1. Fork this repository

Create a fork in the student's GitHub account.

If the goal is to publish the site at the root GitHub Pages address, rename the
fork to:

```text
<github-username>.github.io
```

That makes the site available at:

```text
https://<github-username>.github.io
```

### 2. Enable GitHub Pages

In the forked repository:

1. Open Settings.
2. Open Pages.
3. Under Source, choose Deploy from a branch.
4. Select the main branch and the /(root) folder.
5. Save.

GitHub Pages usually publishes within a couple of minutes.

### 3. Edit the homepage

Open index.html and replace each placeholder marked with:

```html
<!-- EDIT: ... -->
```

Students should update:

- Name
- Program and institution
- Short bio
- Contact links
- Interests
- Projects
- Publications, if needed

### 4. Replace the image and CV

- Replace assets/images/profile.svg with a real photo, or update the image path
	in index.html to point to a new file such as profile.jpg.
- Add a CV as cv/cv.pdf and keep the existing homepage link, or change the link
	to a different file.

### 5. Customize the design

Open assets/css/style.css. The variables near the top control the visual theme:

```css
--color-accent: #0a6c74;
--font-serif: "Fraunces", Georgia, "Times New Roman", serif;
--font-sans: "Manrope", "Segoe UI", sans-serif;
```

Students can change colors, fonts, spacing, and layout without changing the HTML
structure.

## Adding a project

1. Copy projects/project-one.html to a new file in the same folder.
2. Edit the new project page.
3. Duplicate a project card in index.html and point it to the new page.

## Checklist before publishing

- Remove all placeholder text
- Add a real image and CV
- Test every external link
- Check the layout on mobile
- Update the browser title in each page

## Local preview

Students can open index.html directly in a browser. If they want a local server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## License

This template is free to use and modify. Credit is appreciated but not required.
