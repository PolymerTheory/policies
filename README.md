# policies

Public privacy policies and legal pages for Tüftler Apps, served via GitHub Pages.

## Live URLs

- Landing: `https://polymertheory.github.io/policies/`
- Photo Atlas: `https://polymertheory.github.io/policies/photo-atlas/`
- Panels: `https://polymertheory.github.io/policies/panels/`

(GitHub Pages must be enabled: repo **Settings → Pages → Source: `main` branch, `/` root**.)

## Layout

```
index.html            landing page linking to each app's policy
photo-atlas/index.html
panels/index.html
```

One folder per app. Add a new app by creating `newapp/index.html`. Keep this repo to
policy/legal pages only — app data and assets belong in each app's own repo.

## Notes

- The Panels policy here is a **copy** for consistency; the original lives in
  `PolymerTheory/panels-privacy` and remains the source that Panels currently links to.
- Plain static HTML, no build step. Edit the file, commit, push.
