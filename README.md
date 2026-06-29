# Power Analysis Tutorial: Fixed Effects Models

Simulation-based power analysis for fixed effects models using pilot data in R.
Covers homoscedastic (`lm`) and heteroscedastic (`nlme::gls` with `varIdent`)
approaches with pairwise contrast testing via `emmeans`.

## View the tutorial

<a href="https://marcabeer.github.io/power-analysis-fixed-effects-tutorial/" target="_blank">https://marcabeer.github.io/power-analysis-fixed-effects-tutorial/</a>

## Repository contents

- `power_analysis_fixed_effects.Rmd` — source code
- `index.html` — rendered tutorial
- `renv.lock` — package environment lockfile
- `render.R` — renders the Rmd to index.html

## Reproducing the tutorial

Restore the package environment before knitting:

```r
renv::restore()
```

Then render:

```r
source("render.R")
```
