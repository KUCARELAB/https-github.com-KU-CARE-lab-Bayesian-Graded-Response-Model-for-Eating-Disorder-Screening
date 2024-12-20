# https-github.com-KU-CARE-lab-Bayesian-Graded-Response-Model-for-Eating-Disorder-Screening
https://github.com/KU-CARE-lab/Bayesian-Graded-Response-Model-for-Eating-Disorder-Screening
##################### data

Our current study protocol requires a signed data use agreement prior to release. Please email the corresonding author at kforbush@ku.edu.

##################### model fit

The folder "model fit" contains R files for fitting the Bayesian-GRM, testing model fit, and performing cross-validation.

Fitting the Bayesian-GRM to training data (Section 3.1): "Bayesian_GRM_scoff.R" and "Bayesian_GRM_base.R".
Predicting individual ED risk using fitted Bayesian-GRM (Section 3.2): "ED_risk_estimate_scoff.R" and "ED_risk_estimate_base.R".
Cross-validation using out-of-sample method (Section 3.3): "cross_validation_scoff.R" and "cross_validation_base.R".
Figure 2 (posterior predictive comparison): plotted by "posterior_predictive_scoff.R" and "posterior_predictive_base.R".
Figure 3 (cross-validation results): plotted by "plot_cross_validation.R".
##################### hypotheses 1 and 2

The folder "hypothesis_1_and_2" contains R files used in Hypotheses 1 (Accuracy of ED risk estimation, Section 4.2) and 2 (Characterization of item-level discriminability, Section 4.3).

Figure 4 (posterior distributions of person parameters): plotted by "plot_theta_ED_risk_scoff.R" and "plot_theta_ED_risk_base.R".
Table 4 (mean squared errors): calculated by "MSE.R".
Figure 5 (Association between person-parameter and ED risk): plotted by "ED_diagnosis_prediction.R".
Figure 6 (posterior distributions of discrimination parameters): plotted by "plot_alpha.R".
Figure 7 (individuals with high screening scores but low ED risk estimates): plotted by "GRM_aggregation_comparison.R".
##################### bootstrap study

The folder "bootstrap" contains R code used in the bootstrap study (Section 4.4).

Performing the bootstrap: "Bayesian_GRM_scoff_boot.R" and "Bayesian_GRM_base_boot.R".
Predicting individual ED risk: "ED_risk_estimate_scoff_boot.R" and "ED_risk_estimate_base_boot.R".
Table 5 (MSE): "MSE.R".
Figure 8, and figures in Supplement 4: "Investigation2 - only_fm.R".
##################### supplemental materials

The folder "supplement" contain R code used in the Supplemental studies.
