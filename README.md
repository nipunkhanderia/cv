# Nipun Khanderia — Personal Portfolio

A single-page personal portfolio website built with vanilla HTML, CSS, and SVG.
No frameworks, no dependencies, no build step — just open the file and it works.

## Live Sections

- **Hero** — Animated mountain/cloud landscape with name and title
- **About** — Brief professional summary
- **Skills** — Competency pills and tools overview
- **Experience** — Role history with client/employer breakdown
- **AI & Innovation** — Key AI initiatives and highlights
- **Certifications** — 16 certifications with inline SVG badges (AWS, Azure, Google Cloud, Snowflake, GitHub)
- **Education** — M.Tech, Nirma University
- **Contact** — Email CTA and LinkedIn link

## Tech

- Pure HTML5 + CSS3 — no JavaScript frameworks
- Google Fonts (Sacramento + Raleway) via CDN
- All certification badges rendered as inline SVG — no external image dependencies
- Animated SVG clouds and mountain silhouette in the hero section

## Usage

```bash
git clone https://github.com/nipunkhanderia/<repo-name>
# Then just open index.html in a browser — no server needed
```

Or deploy directly to **GitHub Pages**, **Netlify**, or **Vercel** by pointing
to the root of the repo.

## Customisation

| What to change | Where |
|---|---|
| Profile photo | Replace `src="Nipun-pic"` in the profile section |
| Contact email | Update `href="mailto:..."` in the contact section |
| LinkedIn URL | Update `href` in the footer anchor |
| colours / fonts | CSS variables at the top of the `<style>` block |

## Deployment (GitHub Pages)

1. Push the file as `index.html` to your repo root
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://nipunkhanderia.github.io/<repo-name>`

## License

Feel free to use this as a template. Attribution appreciated but not required.
