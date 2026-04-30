# hugotrad-site

Personal academic site for Hugo Trad — Assistant Professor of Behavioural Science at Africa Business School (UM6P).

Built with [Quarto](https://quarto.org). Trilingual (EN / FR / AR), deployed to GitHub Pages at `hdtrad.github.io`.

## Local development

```bash
# preview live (auto-reloads on save)
quarto preview

# render statically to _site/
quarto render
```

## Structure

```
en/   English (canonical)
fr/   French
ar/   Arabic (RTL)
styles/
  custom.scss   light theme
  dark.scss     dark mode overrides
  extra.css     Arabic typography + RTL
_includes/      head metadata, lang/dir script
assets/         headshot, logos, CV PDF
```

## Design branches

Three accent-colour variants live on parallel branches for side-by-side comparison:

- `main` — deep teal `#1F4E5F` (default)
- `design-burgundy` — burgundy `#7A2E2E`
- `design-um6p-green` — UM6P institutional green

Switch with `git checkout design-burgundy && quarto preview`.

## Launch checklist

- [ ] Replace placeholder logos in `assets/logos/` with official files
- [ ] Replace placeholder `assets/cv.pdf` with current CV
- [ ] Have an Arabic-native colleague review `ar/*.qmd` (~30 min)
- [ ] Lighthouse audit (target 95+ on all four metrics)
- [ ] Make repo public + enable GitHub Pages (Settings → Pages → main branch)
- [ ] Submit `https://hdtrad.github.io/sitemap.xml` to Google Search Console
- [ ] Update Scholar / OSF / GitHub / LinkedIn bios with new URL
- [ ] Replace each Google Sites page with a single redirect link to the new URL
