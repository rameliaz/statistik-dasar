# Statistik Dasar dalam Penelitian Psikologi

Course slide decks for *Statistik Dasar dalam Penelitian Psikologi* (Basic Statistics in Psychological Research).

**Live site:** https://rameliaz.github.io/statistik-dasar

## Contents

14 slide decks covering:

| # | Topic |
|---|---|
| 1 | Statistik Deskriptif |
| 2 | Probabilitas |
| 3 | Estimasi Parameter Populasi |
| 4 | Uji Hipotesis (NHST) |
| 5 | Analisis Data Kategorikal |
| 6 | T-Test |
| 7 | Korelasi |
| 8 | ANOVA |
| 9 | ANOVA Faktorial |
| 10 | ANOVA Pengukuran Berulang |
| 11 | ANCOVA |
| 12 | Regresi Linear (OLS) |
| 13 | Analisis Moderasi |
| 14 | Analisis Mediasi |

Statistical analysis is demonstrated using [jamovi](https://www.jamovi.org/) (v2.6.44), though all concepts are software-agnostic.

## Built with

- [Quarto](https://quarto.org/) website with RevealJS slide format
- Custom Airlangga University branding via the `rameliaz/unair` Quarto extension

## Local development

```bash
# Install Quarto: https://quarto.org/docs/get-started/

# Live preview
quarto preview

# Full build → docs/
quarto render

# Single deck
quarto render slides/korelasi.qmd
```

Output is written to `docs/` and deployed as GitHub Pages.

## License

Materials are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to reuse with attribution.
