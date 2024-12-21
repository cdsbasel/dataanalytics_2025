---
layout: page
title: Installation instructions
---

You will need to bring a laptop for this course to work on data analytics practicals in R. Prior to the first session, please follow the instructions to install all necessary software.

If you cannot bring a laptop to the course please let us know asap.

## 1 - Install Base-R and RStudio on your laptops

Use the following links to install the newest versions of base-R and RStudio.

### Install Base-R
<a href="https://cran.r-project.org/bin/windows/base/R-4.3.2-win.exe">R 4.3.2 (Windows)</a>,
<a href="https://cran.r-project.org/bin/macosx/big-sur-arm64/base/R-4.3.2-arm64.pkg">R 4.3.2 (Mac)</a><br>

### Install RStudio
<a href="https://download1.rstudio.org/electron/windows/RStudio-2023.12.0-369.exe">RStudio 2023 (Windows)</a>,
<a href="https://download1.rstudio.org/electron/macos/RStudio-2023.12.0-369.dmg">RStudio 2023 (Mac)</a>

## 2 - Install necessary packages

For this course we will rely on various R packages that need to be installed. To do this run the following code within your R Console in R Studio.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
install.packages("tidyverse","ggthemes","distill","rmarkdown","lme4")
</font>

Important: to avoid problems during the installation of packages, please enter *n*, when you are asked to install a package from source.
