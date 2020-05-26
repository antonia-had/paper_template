# Source code for producing the results and figures

> This should be a description of all codes used.
> The following is example text you can use, taken from [this template](https://github.com/pinga-lab/paper-template)

The code is divided between Python modules in `mypackage` and Jupyter notebooks
in `notebooks`. The modules implement the methodology and code that is reused
in different applications. This code is tested using `pytest` with the test
code in `tests`. The notebooks perform the data analysis and processing and
generate the figures for the paper.

The `Makefile` automates all processes related to executing code.
Run the following to perform all actions from building the software to
generating the final figures:

    make all


## Analysis set up

> You can use this section to explain how to set up the experiment. In the Reed
> group we often submit 'jobs' (i.e., sets of model runs), which should be
> explained here.


## Generating results and figures

> You can use this area to explain how to process the outputs to generate the
> results and figures used in the paper. A makefile that automates the process
> would be ideal here. You can use text like the following:

* Generate all results files specified in the `Makefile`:

        make results

* Create all figure files specified in the `Makefile`:

        make figures
