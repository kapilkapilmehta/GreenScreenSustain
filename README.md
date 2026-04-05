# GreenScreen Sustain Website

Static marketing site for GreenScreen Sustain, designed for simple Vercel deployment.

## Project structure

- `index.html` contains the full page structure and copy.
- `style.css` contains the visual system, layout, and responsive styles.
- `assets/` contains the supplied brand and prototype imagery.
- `vercel.json` enables clean URLs on deployment.

## Local preview

Because this is a plain static site, you can preview it with any lightweight static server.

Example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

1. Create or log in to your Vercel account.
2. Import this folder as a new project.
3. Deploy the site.
4. Add the custom domain in Vercel.
5. Point the DNS records from your registrar to the values Vercel provides.

## Content basis

The current website copy and layout are based on:

- prototype imagery shared for the project
- Dr. Anjali Mehta's background and professional profile
- the layered-material PPE concept shown in the reference deck

## Launch checklist

Confirm these before going live:

- final brand name and preferred domain: `greenscreensustain.in`
- final contact email, phone number, and postal address
- approved wording for the patent and award references
- full team list and titles
- any investor, hospital, research, or press references to include

## Git workflow

Current recommended flow:

- use `main` as the default branch
- deploy from GitHub to Vercel
- prefer SSH auth for future pushes after adding the generated public key to GitHub
