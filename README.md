[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[27410-2020-group-project-group-2-gsm-c-glutamicum]/main)

# 27410 - Group assignment - Group 2 - Application of Genome Scale Modeling for Putrescine Production

## Project summary
The aim of this project is to design a cell factory for the production of putrescine, a four-carbon compound that is commonly used as a monomer to synthesize polymers. Putrescine is a useful chemical with a wide range of applications, ranging from the textile industry to the pharmaceutical sector. Today, putrescine is produced using chemical synthesis, but there is a rising demand for more sustainable production methods such as biobased manufacturing using living and growing cells.

The project considers the application of the following chassis: the gram-positive bacterium *Corynebacterium glutamicum* (*C. glutamicum*) and the gram-negative bacterium *Escherichia coli* (*E. coli*), which represent their respective advantages and disadvantages when applied as a cell factory. The decision was to utilize *E. coli* as the cell factory due to its more readily available GSM model.

The chassis *E. coli* is a native producer of putrescine – but it only produces the compound in very limited amounts. In order to improve the yield of putrescine in *E. coli*, we implemented two heterologous pathway consisting of two seperate one-step reaction, which required the addition of two enzymes to the GSM model.

The maximum theoretical yield of putrescine in *E. coli* was 0.9565 mmol/mmol before implementation of the heterologous pathway, and 0.9929 mmol/mmol after its implementation. Thus, the implementation of the heterologous pathway yielded a 3.8% improvement on the maximum theoretical yield.

In order to investigate the production of putrescine in *E. coli*, we used tools such as phenotypic phase plans (PPPs) and dynamic flux balance analysis (dFBA). Furthermore, in order to improve the productivity of putrescine in *E. coli*, we used algorithms such as OptKnock. All in all, there is more to be done in terms of modeling in order to make it feasible to use *E. coli* as a cell factory for the production of putrescine.

## Project overview
The project can be viewed in the [Report.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/Report.ipynb) notebook. This notebook contains an introduction to the project including a literature review of the chosen compound and the potential chassis, respectively. It also contains a selection and assessment of the existing GSMs using MEMOTE, an open-source software containing a standardized set of metabolic model tests ([0.memote.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/0.memote.ipynb)).

In the project, the compound of interest is implemented in two potential chassis, i.e. *C. glutamicum* ([1.Cglutamicum_model.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/1.Cglutamicum_model.ipynb)) and *E. coli* ([2.Ecoli_model.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/2.Ecoli_model.ipynb)). Considering the selection and assessment of the existing GSMs, the proceeding work focused on the implementation of a heterologous pathway in the GSM model for *E. coli*.

The main content of the [Report.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/Report.ipynb) notebook concerns the application of computer-aided cell factory engineering to the GSM model:

* Calculation of the maximum theoretical yield ([3.Ecoli_theoretical_yield.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/3.Ecoli_theoretical_yield.ipynb)).

* Plotting of the phenotypic phase planes using aerobic and anaerobic conditions, respectively ([4.Ecoli_phenotypic_phase_plan.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/4.Ecoli_phenotypic_phase_plan.ipynb)).

* Simulation of batch cultivations using dynamic flux balance analysis ([5.Ecoli_dynamicFBA.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/5.Ecoli_dynamicFBA.ipynb)).

For the GSM model, there have also been applied a number of strain design prediction algorithms:

* Computing gene knockout strategies using the algorithm OptKnock ([6.Ecoli_gene_KO.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/6.Ecoli_gene_KO.ipynb)).

* Application of heterologous pathways prediction ([7.Ecoli_predicting_heterologous_pathways.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/7.Ecoli_predicting_heterologous_pathways.ipynb)).

For further work with the GSM model, options for overexpression of key reactions have been explored:
* Application of overexpression of target reaction ([8.Ecoli_overexpress.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/8.Ecoli_overexpress.ipynb)).

Furthermore, the [Report.ipynb](https://github.com/27410/27410-2020-group-project-group-2-gsm-c-glutamicum/blob/main/Report.ipynb) notebook contains a discussion regarding the results of the applied computer-aided cell factory engineering, and a conclusion.