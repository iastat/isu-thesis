# phd-thesis

Template for ISU PhD Thesis. Blatantly stolen/adapted from @cpsievert [phd-thesis repo](https://github.com/cpsievert/phd-thesis).

## ISU Resources

- What the finished product should look like: https://www.grad-college.iastate.edu/documents/thesis/thesis_template/Latex_Thesis.pdf
- Breakdown of rules for each piece: https://www.grad-college.iastate.edu/thesis/organizing_thesis/ (click-through)
- If your thesis gets rejected, check these links first! :arrow_up: 

## Avoid headaches with these simple rules 

- Don't use underscores, spaces, or other symbols in file names (- are ok). See [here](https://github.com/rstudio/bookdown/issues/491)
- Insert images and tables using `knitr::include_graphics()` and `knitr::kable()`, respectively, inside of R code chunks. The reference tag will then be `fig:chunkname` or `tab:chunkname`, respectively. 
