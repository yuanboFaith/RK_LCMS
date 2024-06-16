# UHPLC-QqQ-MS/MS method development and validation with statistical analysis: Determination of raspberry ketone metabolites in mice plasma and brain

**See [original article](https://pubmed.ncbi.nlm.nih.gov/32474352/) in _J. Chroma. B._**

## Abstract

**Raspberry ketone (RK)** (4-(4-hydroxyphenyl)-2-butanone) is the major compound responsible for the characteristic aroma of red raspberries, and has long been used commercially as a flavoring agent and recently as a weight loss supplement. A targeted UHPLC-QqQ-MS/MS method was developed and validated for analysis of RK and 25 associated metabolites in mouse plasma and brain. Dispersion and projection analysis and central composite design were used for method optimization. Random effect analysis of variance was applied for validation inference and variation partition. Within this framework, repeatability, a broader sense of precision, was calculated as fraction of accuracy variance, reflecting instrumental imprecision, compound degradation and carry-over effects. Multivariate correlation analysis and principle component analysis were conducted, revealing underlying association among the manifold of method traits. R programming was engaged in streamlined statistical analysis and data visualization. Two particular phenomena, the analytes' background existence in the enzyme solution used for phase II metabolites deconjugation, and the noted lability of analytes in pure solvent at 4 ℃ vs. elevated stability in biomatrices, were found critical to method development and validation. The approach for the method development and validation provided a foundation for experiments that examine RK metabolism and bioavailability.

The repository records the R script used for data anaysis and visualization in this publication. The script and output can be accessed [here](https://yuanbofaith.github.io/RK_LCMS). 

<br>

## Script References

The R code has been developed with reference to [**R for Data Science (2e)**](https://r4ds.hadley.nz/), and the official documentation of [**tidyverse**](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- **Data visualization** with **ggplot2** ([**tutorial**](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [**data viz. gallery**](https://www.databrewer.co/R/gallery)).

- [**Data wrangling**](https://www.databrewer.co/R/data-wrangling) with the following packages:
[**tidyr**](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure; [**dplyr**](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): the basic tools to work with data frames; [**stringr**](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings; [**regular expression**](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern; [**purrr**](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns); and [**tibble**](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.

<br>

## Follow me. Stay Updated with My Latest Research

<table style="border-collapse: collapse; width: 100%; border: 0;">
  <tr>
    <td style="border: none;" align="center">
      <a href="https://medium.com/@yuanbo.faith">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Medium_%28website%29_logo.svg" alt="Medium Logo" style="max-width: 100px; height: auto; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://x.com/yuanbogeneral">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/X_logo_2023.svg" alt="X Logo" style="max-width: 100px; height: auto; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://www.databrewer.co/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Logo_of_DataBrewer.co.png" alt="DataBrewer Logo" style="max-width: 100px; height: auto; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://connects.catalyst.harvard.edu/Profiles/display/Person/193422">
        <img src="https://upload.wikimedia.org/wikipedia/en/1/18/Harvard_shield-Public_Health.png" alt="Harvard Public Health Logo" style="max-width: 100px; height: auto; margin: 10px;">
      </a>
    </td>
  </tr>
</table>


