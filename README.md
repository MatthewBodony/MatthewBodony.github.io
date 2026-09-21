# Portfolio site

Static site, no build step, no dependencies. Every page is plain HTML plus one stylesheet.

## Publishing to GitHub Pages

1. On GitHub, create a repository named exactly `MatthewBodony.github.io`. It must be public.
2. Upload everything in this folder to the root of that repository — `index.html` at the top level, not inside a subfolder.
3. In the repository, go to **Settings → Pages** and set the source to the `main` branch, folder `/ (root)`.
4. Wait a minute or two. The site is live at `https://matthewbodony.github.io`.

## Files

```
index.html        home page and project cards
zrc.html          UIUC / CHESS
sponges.html      Dravid Group / NUANCE
radical.html      NU RADICAL
lunabotics.html   Northwestern Lunabotics
style.css         all styling
assets/           images
```

## Making changes

- **Text**: open the relevant `.html` file and edit between the tags. The words are plain text; leave anything in angle brackets alone.
- **Images**: drop a new file into `assets/` and change the `src="assets/..."` path to match. Keep images under about 500 KB — resize before uploading.
- **A new project**: copy an existing project page, rename it, edit the contents, then add a matching `<a class="card">` block to `index.html`.

## Before you publish

- [ ] Confirm the LinkedIn URL in the header of all five pages, or remove the link.
- [ ] Replace the ParaView screenshot with a clean export — no toolbars, no window chrome, white or transparent background.
- [ ] Get release approval for the DED deposition video, thermal build footage, and equipment photographs, then replace the placeholder on `radical.html`.
- [ ] Add Lunabotics images if any become available; that page is text-only.
