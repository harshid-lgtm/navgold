# navgold.co.uk

The Navgold website: static HTML, CSS and JavaScript with no build step.

## Live site

Published with GitHub Pages from the `main` branch (root folder):

https://navgold.com/

## Structure

- `index.html` - home page
- `about/`, `services/`, `solutions/`, `blog/`, `case-studies/`, `resources/`,
  `careers/`, `team/`, `contact/`, `book-audit/`, `partnerships/` - pages
- `assets/css/site.css` - stylesheet
- `assets/js/site.js` - site script
- `assets/img/` - images
- `404.html` - not-found page

## Editing

Edit the HTML and commit. Pages redeploys automatically within about a minute:

```
git add -A
git commit -m "describe the change"
git push
```

All links are relative, so the site works both at the Pages URL above and on any
domain pointed at the repository root.