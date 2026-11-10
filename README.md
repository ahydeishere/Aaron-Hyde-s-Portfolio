# Aaron Hyde Data Science Portfolio

This repository contains the R and Quarto source files for my data science portfolio.

The website is published at:

<https://ahydeishere.github.io/Aaron-Hyde-s-Portfolio/>

## Local preview

Install R, RStudio, and Quarto, then run:

```bash
quarto preview
```

## Adding a project

Add the project `.qmd` file to the repository, link it from the navigation in `_quarto.yml`, and push it to the `main` branch. GitHub Actions will render and publish the website automatically.

Project data should use repository-relative paths or public URLs. For example:

```r
readr::read_csv("data/my-data.csv")
```

Do not use paths beginning with `C:/Users/` because those paths only work on one computer.
