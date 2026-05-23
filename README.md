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
  custom.scss   theme
  extra.css     Arabic typography + RTL
_includes/      head metadata, lang/dir script
assets/         headshot, logos
```

## Launch checklist

- [ ] Arabic-native colleague review of `ar/*.qmd`
- [ ] Flip repo public + enable GitHub Pages
- [ ] Submit `https://hdtrad.github.io/sitemap.xml` to Google Search Console
- [ ] Update Scholar / GitHub / LinkedIn bios with new URL
- [ ] Replace each Google Sites page with a single redirect to the new URL
