# Amber Room Records GitHub Pages Notes

This site is fully static, so it can be published directly with GitHub Pages.

## Files to publish

- `index.html`
- `styles.css`
- `script.js`
- `robots.txt`
- `.nojekyll`

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Push this project to the repository's `main` branch.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Set the branch to `main` and the folder to `/ (root)`.
6. Save and wait for GitHub Pages to publish the site.

If the repository is named `amber-room-records`, the first live URL will usually be:

`https://<your-github-username>.github.io/amber-room-records/`

If you want a cleaner domain like `amberroomrecords.com`, add a custom domain in the same GitHub Pages settings after the first deploy.

## To make it searchable

1. Publish the site so it has a public URL.
2. If you use a custom domain, update the site metadata in `index.html`.
3. Add a `sitemap.xml` once the final domain is known.
4. Submit the live site to Google Search Console.

## Metadata to update after the final URL exists

Add these to `index.html` once the real public URL is known:

- canonical URL
- `og:url`
- `og:image`
- Twitter image
- structured data `url`

If you use a custom domain with GitHub Pages, also add a `CNAME` file containing only that domain.
