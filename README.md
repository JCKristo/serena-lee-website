# Serena Lee Photography

One-page personal site for Serena Lee, a freelance wedding and portrait photographer.
Plain HTML and CSS, no build step.

## Structure

- `index.html` is the whole site (hero, portfolio grid, about, contact)
- `images/` holds the portfolio photos
- `vercel.json` holds the Vercel settings (static site, no build)

## Preview locally

```sh
npx serve .
```

## Deploy to Vercel

1. In Vercel, choose **Add New > Project** and import this repo.
2. Leave the framework preset as **Other**. Leave the build command and output directory empty.
3. Click **Deploy**. Every push to `main` redeploys the site.

Or from the command line:

```sh
npx vercel --prod
```

## Editing

- Replace a grey placeholder in the portfolio grid with an `<img>` that points to a file in `images/`.
- Update the email address in the contact section. It appears twice in `index.html`: the `mailto:` link and the visible text.
