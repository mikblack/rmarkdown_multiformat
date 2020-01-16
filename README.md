### R Markdown multi-format

Repo demonstrating how to produce multiple output formats from a single markdown document.

For example, use `multiformat.Rmd` to generate both markdown (github format) and html documents (run in R):

```
rmarkdown::render("multiformat.Rmd", output_format=c("html_document", "github_document"))
```

Header used in `multiformat.Rmd` 

```
---
title: 'Rmarkdown: multiformat'
author: "Mik Black"
date: "6/7/2018"
output: 
  html_document: default
  github_document: default
  pdf_document: default
  word_document: default
---
```
