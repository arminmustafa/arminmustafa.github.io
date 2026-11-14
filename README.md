# arminmustafa.github.io

Personal website of Armin Mustafa, including the N4D Lab (4D Narrative AI).
Static site: `index.html` and `assets/`. No build step.

## Publish on GitHub Pages
1. Open the `arminmustafa.github.io` repository.
2. Keep the old `docs/` folder if you want existing links to the thesis PDFs to keep working.
3. Replace the root `index.html` with this one and add the `assets/` folder, `robots.txt` and `sitemap.xml`.
4. Commit and push. The site updates at https://arminmustafa.github.io within a minute or two.

## Editing
- Papers, projects, news, team, alumni, awards and service roles are plain lists at the top of the `<script>` block in `index.html`.
- Colours and layout are in `assets/site.css` (the two tint values are `--mint` and `--mint-soft`).
- The lab section shows six looping clips, `assets/tile-*.mp4`, each with a poster image `assets/tile-*.jpg`.
- The portrait is `assets/armin.jpg`; the link-preview image is `assets/og.jpg`.

## Being found in search
- The page carries a title, description, keywords, canonical link and structured data (Person and N4D Lab) for "4D Narrative AI".
- After publishing, add the site in Google Search Console and submit `https://arminmustafa.github.io/sitemap.xml`.
- Links from other sites matter most: point your Surrey profile, Google Scholar homepage, LinkedIn and the RAEng page to https://arminmustafa.github.io.

## Analytics

Visits are counted with GoatCounter, which uses no cookies, so no consent banner is needed.
See the stats at https://arminmustafa.goatcounter.com (sign in with your GoatCounter account).
The tracking line is the `goatcounter` script just before `</body>` in `index.html`.
