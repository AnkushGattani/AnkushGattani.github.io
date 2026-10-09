# Ankush Gattani: personal site

Personal website for Ankush Gattani. Plain HTML, CSS and JavaScript with no build step.

## Run locally

```bash
python -m http.server 4173
```

Then open http://localhost:4173.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New > Project** and import the repository.
3. Leave the framework preset as **Other** and the build command empty. Deploy.

`vercel.json` sets clean URLs and cache headers; nothing else is required.

## Editing

- `index.html` holds all the content.
- `styles.css` holds the design. Colours and fonts are tokens at the top of the file.
- `assets/ankush-gattani.jpg` is the portrait.
