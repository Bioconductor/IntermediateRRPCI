# Workshop: Intermediate R Software Development

This is a series of meetings to enhance our understanding of R as a
programming language, and to connect with other people interested in R
software development. It is open to members of the Roswell Park and
SUNY at Buffalo communities. It is suitable for people who already
know R, and are eager to develop a deeper understanding of the
language and 'best practices' when tackling larger projects.

There are six sessions. Participants are expected to attend all
sessions. All sessions are 4-6 pm in the Gaylord Cary Meeting Room,
Research Studies Center, Roswell Park.

Applications CLOSED.

The first meeting is Wednesday, 5 October, at 4-6 pm in the Gaylord
Cary Meeting Room, Research Studies Center, Roswell Park.

## Preparation

1. Please bring a laptop with wifi capabilities. Its a 2-hour session
   so a charged battery should be ok; I'm not sure what the power
   supply situation will be.

## Schedule (Tentative)

Wednesday, 5 October

- Working with packages and github.

- Please install [R][] version 3.3.1, [RStudio][], and [git][].

- Please also install [devtools][].
   
        install.packages("devtools")

Friday, 7 October

- Classical, tidy, and rich approaches to data representation and
  analysis

- For session 2, please install [dplyr][], [data.table][],
  [reshape2][] [ggplot2][] and [SummarizedExperiment][]

        install.packages(
            c("dplyr", "data.table", "reshape2", "ggplot2"),
            repos="https://cran.r-project.org"
        )
        source("https://bioconductor.org/biocLite.R")
        biocLite("SummarizedExperiment")

- Please also download the following plain-text files:
  [ALL-expression.csv][], [ALL-phenoData.csv][]

Wednesday, 12 October

- Understanding classes and methods

Friday, 14 October

- Unit tests and other programming best practices

Wednesday, 19 October

- For session 5, please install [microbenchmark][], [memoise][], and
  optionally [inline][]
  
        install.packages(
            c("microbenchmark", "memoise", "inline")
            repos="https://cran.r-project.org"
        )

- Writing efficient code

Friday, 21 October

- For this session, please install [rmarkdown][] and [shiny][].

- Reports, shiny applications, and interactive communication

[1]: https://www.surveymonkey.com/r/ZHBSZ9H

[R]: https://cran.r-project.org/
[RStudio]: https://www.rstudio.com/products/rstudio/download3/
[git]: https://git-scm.com/downloads
[devtools]: https://cran.r-project.org/package=devtools
[dplyr]: https://cran.r-project.org/package=dplyr
[data.table]: https://cran.r-project.org/package=data.table
[reshape2]: https://cran.r-project.org/package=reshape2
[ggplot2]: https://cran.r-project.org/package=ggplot2
[microbenchmark]: https://cran.r-project.org/package=microbenchmark
[memoise]: https://cran.r-project.org/package=memoise
[inline]: https://cran.r-project.org/package=inline
[rmarkdown]: https://cran.r-project.org/package=rmarkdown
[shiny]: https://cran.r-project.org/package=shiny
[SummarizedExperiment]: https://bioconductor.org/packages/SummarizedExperiment
[ALL-expression.csv]: https://github.com/Bioconductor/BiocIntroRPCI/raw/master/inst/extdata/ALL-expression.csv
[ALL-phenoData.csv]: https://github.com/Bioconductor/BiocIntroRPCI/raw/master/inst/extdata/ALL-phenoData.csv
