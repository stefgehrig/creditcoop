This repository contains data and analysis code for the unpublished manuscript **"Societal norms of cooperation and microcredit repayment under group lending"**.

<p align="center">
<img src="https://github.com/stefgehrig/creditcoop/blob/main/outputs/fig_params_main.png" width="500">
</p>


<p align="center">
<img src="https://github.com/stefgehrig/creditcoop/blob/main/outputs/fig_predcoop_main.png" width="500">
</p>

<p align="center">
<img src="https://github.com/stefgehrig/Creditcoop/blob/main/outputs/fig_varcomp_main.png" width="500">
</p>

The manuscript can be found in the `manuscript.pdf` file.

To reproduce the analyses, the `modeling.R` script has to be run as a first step. It imports the required data and the helper functions stored in `functions.R`, and runs all Bayesian models. The `produce_outputs.R` script uses the modeling outputs to create figures and tables. The `manuscript.Rmd` script renders the final manuscript using R Markdown.
