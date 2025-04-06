# treehouse-plan (wip)
A treehouse build plan made in R

## The Site
![Treehouse Plan](figures/the-site.png)

## Notes
This project uses [`renv`](https://rstudio.github.io/renv/) for environment management.

To set up:

```r
# Install renv if needed
install.packages("renv")

# Restore the exact environment
renv::restore()

# Re-save when you add packages
renv::snapshot()
```