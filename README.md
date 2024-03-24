# SLOPE-Adaptive-variable-selection
This project is part of the evaluation for the Guidelines in ML subject in the second year of the MSc in Mathematics and Artificial Intelligence program at Paris-Saclay University. It focuses on SLOPE, the method introduced by (Bogdan et al., 2015), for variable selection via convex optimization.

## Introduction
In this project, we aim to explain how the following convex optimization problem with a sorted $\ell_1$-penalization can be utilized for variable selection in sparse linear regression:

$$\underset{b\in\mathbb{R}^p}{\mathrm{min}}\frac{1}{2}\|Y-Xb\|^2_2+\sum_{i=1}^p\lambda_i|b|_{[i]},$$

where $\lambda_1\geq \ldots\geq \lambda_p$ and $|b|_{[1]}\geq \ldots \geq |b|_{[p]}$ .Different choices of sequences of penalty are discussed. 

## How to Run the Code

This section will guide you through the process of running the code included in this R Markdown document.

### Instructions

1. **Open the RMD file in RStudio**: To execute the code, open the `SLOPE.Rmd` file in RStudio or any other text editor you use.

2. **Running the Entire Document**: To run the entire document, click the "Knit" button in RStudio or use the command `rmarkdown::render("your_file.Rmd")` in the console. This step can take a lot of time (around 11 hours).

3. **Installing Packages**: Ensure that all required packages are installed using `install.packages("package_name")`. You can load the necessary packages with `library(package_name)`.

4. **Running Individual Code**: You can execute individual pieces of code by selecting them and pressing `Ctrl + Enter` in RStudio or by using the command `source("path_to_your_script.R")` in the console.

