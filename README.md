[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[27410-2020-group-project-group-2-gsm-c-glutamicum]/main)

# 27410 - Group assignment - Group 2 - Application of Genome Scale Modelling for Putrescine Production

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([Group Number] and [TITLE]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
Describe the overall aim of your project and what you have achieved.

The aim of this project is to 

genome-scale metabolic models (GSMs).

## Project overview
Describe how your project is organized ...

The project can be viewed in the [Report.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/Report.ipynb) notebook. This notebook contains an introduction to the project including a literature review of the chosen compound and the potential chassis, respectively. It also contains a selection and assessement of the existing GSMs using MEMOTE, an open-source software containing a standardized set of metabolic model tests (see the [0.memote.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/0.memote.ipynb) notebook).

In the project, the compound of interest is implemented in two potential chassis, i.e. C. glutamicum (see the [1.Cglutamicum_model.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/1.Cglutamicum_model.ipynb) notebook) and E. coli (see the [2.Ecoli_model.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/2.Ecoli_model.ipynb) notebook). Considering the selection and assessement of the existing GSMs, the proceeding work focused on the implementation of a heterologous pathway in the GSM model for E. coli.

The main content of the [Report.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/Report.ipynb) notebook concerns the application of computer-aided cell factory engineering to the GSM model:

* Calculation of the maximum theoretical yield (see the [3.Ecoli_theoretical_yield.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/3.Ecoli_theoretical_yield.ipynb) notebook).

* Plotting of the phenotypic phase planes using aerobic and anaerobic conditions, respectively (see the [4.Ecoli_phenotypic_phase_plan.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/4.Ecoli_phenotypic_phase_plan.ipynb) notebook).

* Simulation of batch cultivations using dynamic flux balance analysis (see the [5.Ecoli_dynamicFBA.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/5.Ecoli_dynamicFBA.ipynb) notebook).

For the GSM model, there have also been applied a number of strain design prediction algorithms:

* Computing gene knockout strategies using the algorithm OptKnock (see the [6.Ecoli_gene_KO.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/6.Ecoli_gene_KO.ipynb) notebook).

* Application of heterologous pathways prediction (see the [7.Ecoli_predicting_heterologous_pathways.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/7.Ecoli_predicting_heterologous_pathways.ipynb) notebook).

Furthermore, the [Report.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/Report.ipynb) notebook contains a discussion regarding the results of the applied computer-aided cell factory engineering, and a conclusion.