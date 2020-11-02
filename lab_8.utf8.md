---
title             : "Lab 8 Group Committing to github"
shorttitle        : "pay no attention to the tibble behind the curtain"

author: 
  - name          : "Janette Avelar"
    affiliation   : "1"
    corresponding : yes    # Define only one corresponding author
    address       : "Oregon, USA"
    email         : "javelar7@uoregon.edu"
    role:         # Contributorship roles (e.g., CRediT, https://casrai.org/credit/)
      - Writing - Review & Committing
  - name          : "David Fainstein"
    affiliation   : "1"
    role:
      - Writing - Review & Committing
  - name          : "Joe Swinehart"
    affiliation   : "1"
    role:
      - Writing - Review & Committing
  - name          : "Makayla Whitney"
    affiliation   : "1"
    role:
      - Writing - Review & Committing

affiliation:
  - id            : "1"
    institution   : "University of Oregon"


authornote: |
  Janette Avelar, University of Oregon College of Education,
  David Fainstein, University of Oregon College of Education,
  Joe Swinehart, Behavioral Research & Teaching,
  Makayla Whitney, University of Oregon College of Education

  Project completed using RStudio, GitKraken, GitHub, and papaja
  
  Contact: javelar7@uoregon.edu

abstract: |
  This project aims to explore the relationship between teacher experience and student math scores, with an additional look at how free/reduced price lunch status correpsonds to that relationship.
  
  <!-- https://tinyurl.com/ybremelq -->
  
keywords          : "teacher, experience, lunch, math, scores"

bibliography      : ["r-references.bib"]

floatsintext      : yes
figurelist        : no
tablelist         : no
footnotelist      : no
linenumbers       : no
mask              : no
draft             : no

documentclass     : "apa6"
classoption       : "man"
output            : papaja::apa6_pdf
---






```
## Warning: package 'here' was built under R version 4.0.3
```

```
## Warning: package 'rio' was built under R version 4.0.3
```

```
## Warning: package 'tidyverse' was built under R version 4.0.3
```


\begin{table}[tbp]

\begin{center}
\begin{threeparttable}

\caption{\label{tab:tablecode}}

\begin{tabular}{llllll}
\toprule
sex & \multicolumn{1}{c}{frl} & \multicolumn{1}{c}{math\_mean} & \multicolumn{1}{c}{math\_sd} & \multicolumn{1}{c}{read\_mean} & \multicolumn{1}{c}{read\_ss}\\
\midrule
boy & no & 492.85 & 46.34 & 441.46 & 32.32\\
boy & yes & 469.87 & 46.09 & 425.38 & 26.63\\
girl & no & 501.21 & 45.96 & 448.54 & 34.52\\
girl & yes & 477.51 & 46.30 & 430.80 & 27.42\\
\bottomrule
\end{tabular}

\end{threeparttable}
\end{center}

\end{table}

\newpage

![ ](lab_8_files/figure-latex/graph-1.pdf) 




# Methods
We report how we determined our sample size, all data exclusions (if any), all manipulations, and all measures in the study. <!-- 21-word solution (Simmons, Nelson & Simonsohn, 2012; retrieved from http://ssrn.com/abstract=2160588) -->

## Participants

There were some people involved.

## Material

Here's some words.

## Procedure

We did things and we did them well.

## Data analysis
We used R [Version 4.0.2; @R-base] and the R-packages *}dplyr* [@}R-dplyr], *forcats* [Version 0.5.0; @R-forcats], *foreign* [Version 0.8.80; @R-foreign], *ggplot2* [Version 3.3.2; @R-ggplot2], *here* [Version 0.1; @R-here], *openxlsx* [Version 4.2.2; @R-openxlsx], *packrat* [@R-packrat], *papaja* [Version 0.1.0.9997; @R-papaja], *purrr* [Version 0.3.4; @R-purrr], *readr* [Version 1.3.1; @R-readr], *rio* [Version 0.5.16; @R-rio], *stringr* [Version 1.4.0; @R-stringr], *tibble* [Version 3.0.3; @R-tibble], *tidyr* [Version 1.1.2; @R-tidyr], and *tidyverse* [Version 1.3.0; @R-tidyverse] for all our analyses.

There was some data gathered and it was neat.

# Results

# Discussion

This fits into @oneil_weapons discussion about math stuff, we think. We didn't actually read it, but liked the name *Weapons of Math Destruction*.

Another article we didn't read investigates children's understanding of math and science, by Lehrer and Schauble [-@lehrer_children]. It seems cool.


\newpage

# References

\begingroup
\setlength{\parindent}{-0.5in}
\setlength{\leftskip}{0.5in}

<div id="refs" custom-style="Bibliography"></div>
\endgroup
