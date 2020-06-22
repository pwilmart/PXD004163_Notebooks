# PXD004163_Notebooks
Re-analysis of PXD004163 using notebooks to compare with Mascot blog.

---

There was a [recent blog](https://www.matrixscience.com/blog/using-the-quantitation-summary-to-create-reports-and-charts.html) from the [Matrix Science](http://www.matrixscience.com/) team talking about making reports and visualizations from quantitative exports from quantitation summaries. The blog used [R](https://www.r-project.org/) scripts and [Bioconductor](http://www.bioconductor.org/) packages to do some differential expression testing. The blog showed the steps using the R GUI environment. One can also use [RMarkdown](https://rmarkdown.rstudio.com/) in [RStudio](https://rstudio.com/) to create notebooks. Notebooks can also be done in [Jupyter](https://jupyter.org/) using an R kernel. Notebooks are a compelling format for telling data analysis stories.

I got the data from the original [Oncogene paper](https://www.nature.com/articles/onc2016242) from the [PXD004163 PRIDE archive](https://www.ebi.ac.uk/pride/archive/projects/PXD004163) and processed with my [PAW pipeline](https://github.com/pwilmart/PAW_pipeline). The data consisted of two experiments of 10-plex TMT labeled samples. The first dimension separation method was isoelectric focusing of the digested peptides. There were two IPG ranges used: 3-10 and 3.7-4.9. Each experiment had 72 fractions. The data was acquired on a Q Exactive using MS2 reporter ions.

The repository has the usual PAW pipeline results and log files. There are also two notebooks, one for each IPG range. GitHub will render the notebooks if you click on them (most of the time). You can also see them in your browser with these links:

[PXD004163_comparisons_3-10](https://pwilmart.github.io/PXD004163_Notebooks/PXD004163_comparisons_3-10.html)

[PXD004163_comparisons_3.7-4.9](https://pwilmart.github.io/PXD004163_Notebooks/PXD004163_comparisons_3.7-4.9.html)

---

Phil Wilmarth <br />
PSR core <br />
OHSU <br />
June 21, 2020
