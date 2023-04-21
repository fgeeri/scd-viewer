# scd-viewer

The [Swiss Federal Supreme Court Dataset (SCD)](https://zenodo.org/record/7793044) is the largest open-access dataset on Swiss judgments, with 30 variables documenting all 113'367 Federal Supreme Court judgments since 2007.

With this challenge, we want to enable anyone to make their own quantitative analysis of this rich data, even if they have zero prior programming knowledge: We will build a [Shiny app](https://shiny.rstudio.com/) that lets users interact with the data on Swiss Federal Supreme Court judgments and run simple analyses themselves.

## 💡 Idea behind the challenge

The freshly released Swiss Federal Supreme Court Dataset includes all Swiss Federal Supreme Court judgments since 2007. It documents them with 30 variables, which contain case information, the area of law, information about the appealed judgment, the parties, the case outcome, or about citations and publication status.

The SCD enables high-quality quantitative insights into the jurisprudence of the highest Swiss court (see, for example, [Merane 2021](https://www.sjz.ch/de/artikel/2504-0650-2021-0169/computergestutzte-ermittlung-der-geschlechterverteilung-im) or [Geering 2021](https://doi.org/10.38023/3cebc384-e303-4e19-b5bb-a8497f448ad1)). However, using and analysing the dataset generally requires some knowledge of data science methods. The lack of quantitative methods in the current curricula of most Swiss law schools means that many lawyers, judges and jurists, as well as interested laypersons, currently can't use this data themselves.

Shiny apps such as the gorgeous [CRAN Explorer](https://shiny.rstudio.com/gallery/cran-explorer.html), the highly functional [ExPanD](https://shiny.rstudio.com/gallery/explore-panel-data.html) data explorer, or the highly intuitive [Bolivia Life of Labor](https://rosemarysu.shinyapps.io/bolivia_unpaid_labor/) app inspire us. At the [Open Legal Lab 2023](https://opendata.ch/de/events/open-legal-lab-2023/), we want to create a Shiny app that enables anyone to create their own simple analysis of the Federal Supreme Court dataset, without needing programming knowledge or Excel tricks.

## 🎯 Goal of the challenge

> *Create and release a Shiny app that enables simple quantitative analyses of the Federal Supreme Court jurisprudence documented in the SCD without any programming knowledge.*

## 🚀 Roadmap

This will have to be discussed at the hackathon.

-   [x] Collect data
-   [ ] Define main analysis types as use cases
-   [ ] Create Shiny app
-   [ ] Prepare presentation
-   [ ] Deploy Shiny app
-   [ ] ✨ Extra: Automatically integrate most recent judgments through SCD updates
-   [ ] ✨ Extra: Translate user interface to German, French, Italian, Rumantsch
