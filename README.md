### R Markdown multi-format

Repo demonstrating how to produce multiple output formats from a single markdown document.

For example, use `multiformat.Rmd` to generate both markdown (github format) and html documents (run in R):

```
rmarkdown::render("multiformat.Rmd", output_format=c("html_document", "github_document"))
```
