11 June 2020

Here we have collected the code to accompany the NeurIPS submission
"Individually Fair Gradient Boosting"  

* FOR AN EXAMPLE OF BuDRO, SEE THE NOTEBOOK `german/01_german_run.ipynb`
* FOR A SIMPLE EXAMPLE OF BuDRO ON SYNTHETIC DATA, SEE THE SCRIPT
  `synthetic/sim_tf_test.py` - THE RESULTS CAN BE PLOTTED IN 
  `synthetic/simulated-plots.ipynb` TO PRODUCE AN EQUIVALENT TO FIGURE 1
  IN THE SUPPLEMENT

The packages used in the conda environment for the notebooks and scripts are
in the file `py37fair.yml`.  You also need to install the AIF360 package (from
"https://github.com/IBM/AIF360") and probably the SenSR package (from
"https://github.com/IBM/sensitive-subspace-robustness).

In most files, all paths have been removed and need to be replaced with your
own paths.

Other directories:

`german` contains specific scripts and notebooks used in the experiements on
the German credit data set(predict good or bad for credit).

`adult` contains specific scripts and Jupyter notebooks used in the
experiments on the Adult data set(predict whether income exceeds $50k/yr based on Census data).  

`compas` contains specific scripts and notebooks used in the experiments on
the COMPAS data set(predicts criminal recidivism rates).

`scripts` contains the files needed for running BuDRO, as well as a few
other scripts used in data processing.

`synthetic` contains the scripts needed to generate the synthetic plots from
the appendix of the submission.  To plot the data generated in this directory,
see the notebook `simulated-plots.ipynb`.

