# Deploying cross-language in high impact projects


The materials here support a talk at the [Spatial Data Science across
Languages (SDSL)](https://spatial-data-science.github.io/2024/)
conference 2024.

See the [slides here](slides) and in the dropdown menu above.

See the source code at
[github.com/robinlovelace](https://github.com/Robinlovelace/cross_language_projects).

See the README for more information.

Based on
https://robinlovelace.github.io/reproducible-slides-repo-template/slides

To create your own “reproducible slides repo” follow the instructions in
the link above, starting by cloning this repo or creating a template
from this one:

``` bash
gh repo clone robinlovelace/cross_language_projects
code cross_language_projects
```

Or go to
https://github.com/Robinlovelace/reproducible-slides-repo-template and
click “Use this template”.

## Setup

To setup the repo the following commands were used

``` bash
gh repo create # create the repo on github
```

``` r
# Take snapshot with renv:
renv::snapshot()
```
