This repository contains data and analysis code for the manuscript **"Societal norms of cooperation and microcredit repayment under group lending"**.

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

The decision was taken to not bring this manuscript to peer-reviewed publication. Over the years and through the input of critical reviewers at *World Development* (R&R, withdrawn) and *Oxfod Open Economics* (R&R, withdrawn), I have come to realize that with the aggregated data and relatively weak study design at hand,  it just too difficult to draw strong conclusions about an effect of societal norms on repayment behavior of microcredit clients. Multiple sources of uncontrolled confounding and selection bias could be at work. This is beside the best effort to specify rich hierarchical models that incorporate many sources of variation and predictors. Here, we simply present the research project's analysis and results for public access.
