# binderscience

JupyterLab: [![binder badge][binder_badge]][binder_lab]

RStudio: [![binder badge][binder_badge]][binder_studio]

Reproducible science integrated with mybinder.
Click launch binder above to explore this project and run the code.

Project Organization
--------------------

    .
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md
    ├── bin
    ├── config
    ├── data
    │   ├── external
    │   ├── interim
    │   ├── processed
    │   └── raw
    ├── docs
    ├── notebooks
    ├── reports
    │   └── figures
    ├── src
    │   ├── data
    │   ├── external
    │   ├── models
    │   ├── tools
    │   └── visualization
    └── binder
        ├── requirements.txt <- Python requirements
        ├── postBuild <- Additional setup such as adding jupyterlab extensions
        ├── runtime.txt <- Specifiy R version or change to python2 with `python-2.7`
        └── install.R <- R requirements


<!-- Badges -->
[binder_badge]: https://mybinder.org/badge.svg
[binder_lab]: https://mybinder.org/v2/gh/leukgen/binderscience/master?urlpath=lab
[binder_studio]: https://mybinder.org/v2/gh/leukgen/binderscience/master?urlpath=rstudio
