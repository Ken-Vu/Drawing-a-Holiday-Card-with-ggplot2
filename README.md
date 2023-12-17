# Drawing-a-Holiday-Card-with-ggplot2
This repository contains R code as well as .tff files needed to draw and craft a holiday card (as shown below).

A blog on how I drew this card can be found here:

![](holiday_card.png)

# Tools Used
The code was written with RStudio 2023.09.0 Build 463 and the R programming language (version 4.3.1).

The following libraries were used to in R code: 
- **[`pacman`](https://www.rdocumentation.org/packages/pacman/)** (ver. 0.5.1): a convenient package for loading and auto-updating packages all at once.
- **[`dplyr`](https://www.rdocumentation.org/packages/dplyr/)** (ver. 1.1.3): a package that is part of the [`tidyverse`](https://tidyverse.tidyverse.org/) set of packages (along with `ggplot2`) that provides advanced methods for wrangling with your data 
- **[`ggplot2`](https://www.rdocumentation.org/packages/ggplot2/)** (ver. 3.4.3): the data visualization package designed by Hadley Wickham that contains a variety of plotting functions used to construct the holiday card
- **[`extrafont`](https://www.rdocumentation.org/packages/extrafont/)** (ver. 0.19): a package for importing and loading fonts (especially the two .tff files included in this Github repository)

You can click on any of them to get the official R documentation on them in case you want to learn more about them and their features.

# References
I recommend the following resources for enhancing your exploration and experimentation with the `ggplot2` library.
-   [R for Data Science](https://www.amazon.com/Data-Science-Transform-Visualize-Model/dp/1492097403/ref=pd_lpo_sccl_1/138-1502038-2723113?pd_rd_w=jP9lJ&content-id=amzn1.sym.116f529c-aa4d-4763-b2b6-4d614ec7dc00&pf_rd_p=116f529c-aa4d-4763-b2b6-4d614ec7dc00&pf_rd_r=S48KJHVM8YGV8TK2EYRY&pd_rd_wg=tHqsa&pd_rd_r=b6716527-7844-4449-acd3-3817859f681d&pd_rd_i=1492097403&psc=1): This book (now in it's second edition) is a classic and covers some of the bare essentials needed to work with and display all kinds of data as well as strategies for writing clean code. Chapters 10-12 are relevant for those focused on data visualization in general as well as Chapters 2-9 for generally good practices for writing and maintaining clean code. You can read it online here: <https://r4ds.hadley.nz/>

-   [ggplot2: Elegant Graphics for Data Analysis](https://www.amazon.com/ggplot2-Elegant-Graphics-Data-Analysis-dp-331924275X/dp/331924275X/ref=dp_ob_title_bk): This is a good book that explains the grammar of graphics of `ggplot2` and how it works under the surface. Chapters 3-5, 8, 9, 10-14, and 17 are some chapters I recommend for understanding more of the basics of `ggplot2`'s plotting functions, the steps for making `ggplot2` graphs in general, and some of the ways in which the plot aesthetics are made and how they can be modified. You can read the work-in-progress version online here: <https://ggplot2-book.org/>

-   [Data Visualization with R by Rob](https://rkabacoff.github.io/datavis/): It's a direct guide on building plots with `ggplot2` along with best practices for data visualizations in general. Chapters 3-6, 11, and 14 directly focus on `ggplot2`, its wide array of customization for the aesthetics of its plots, and best practices for creating effective and visually sound graphs. Chapter 10 is also interesting if you'd like to explore other graphs besides the conventional 2D bar plots and scatterplots you see often in `ggplot2`, such as dumbbell plots and heat maps. Currently, it's only available as an online bookdown, but a book version is reportedly in the works of being available on Amazon soon.
