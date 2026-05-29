# Xinrui He Personal Website

Static personal academic website styled in the spirit of compact academic homepages such as AcademicPages or Minimal Mistakes profiles.

## Files

- `index.html`: homepage content and metadata
- `styles.css`: responsive styling
- `assets/research-hero.png`: generated homepage visual
- `.nojekyll`: tells GitHub Pages to serve the static files directly

## Optional Headshot

The current page uses an initials portrait. To use a real headshot, save it as `assets/profile.jpg`, then replace this line in `index.html`:

```html
<div class="portrait" aria-hidden="true">XH</div>
```

with:

```html
<img class="portrait portrait-image" src="assets/profile.jpg" alt="Xinrui He">
```

## Private Draft Status

This site is a local private draft. Do not push it to a public GitHub Pages repository until the content is fully reviewed.

When it is ready, publish it from a reviewed repository and enable GitHub Pages only after confirming that the repo visibility and page content are appropriate.
