# Kevin Kariuki Njagi Portfolio

Single-page executive portfolio website for Kevin Kariuki Njagi, built with plain HTML and CSS.

## Files

- `index.html` - one-page portfolio structure and content
- `styles.css` - full responsive styling
- `assets/kevin-logo.svg` - monogram logo
- `assets/avatar.svg` - profile placeholder/monogram image

## How to view locally

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## How to deploy on GitHub Pages

1. Create a new GitHub repository, for example `kevin-portfolio`.
2. Upload `index.html`, `styles.css`, and the `assets` folder.
3. Go to repository `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and `/root` folder.
6. Save. GitHub will generate a public website link.

## Notes

- The phone number is intentionally not displayed.
- The portfolio uses email, LinkedIn, and GitHub as public contact points.
- The avatar is a professional placeholder. Replace `assets/avatar.svg` with a headshot later if preferred; keep the same file name or update the image path in `index.html`.
- The achievement copy is written at senior-manager level without unsupported revenue/client metrics. Add exact numbers later if available.
