# Powder-style artist website for GitHub Pages

This version uses the CSS details visible in the supplied Powder stylesheet: black background, white text, blue links (`#22f`), serif typography, large letter-spaced artist heading, compact left-aligned layout, and the year/tour-list structure. It includes a discography section as requested.

It is a close style/structure recreation, not a guaranteed pixel-identical clone: the original page's complete markup, exact assets, font file, flag sprite, and original runtime behavior are not bundled here. Use your own name, links, event details, and artwork.

## Customize
Edit `index.html` and replace:
- `YOUR ARTIST NAME`
- Bandcamp/SoundCloud/Discogs/Spotify URLs
- contact email
- example event dates, venue, city, country, ticket URLs and flag emoji
- release titles, years and streaming links

Add square artwork to `images/` using the filenames `release-01.jpg` through `release-04.jpg` (or update the paths in the HTML).

## Publish
1. Create a public GitHub repository, e.g. `artist-site`.
2. Upload `index.html` and `images/` to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
5. When published, visit the URL shown in Pages settings.

## Custom domain
In **Settings → Pages → Custom domain**, enter your domain and configure DNS as instructed by GitHub and your registrar. Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
