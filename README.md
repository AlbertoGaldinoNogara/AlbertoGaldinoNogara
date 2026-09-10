## Alberto Galdino Nogara

MSc student in **Data Analytics for Business** at Università Cattolica, Milan.
Currently writing my thesis on **Neural Controlled Differential Equations** for
irregularly sampled financial time series.

Mostly R and Python. I care more about whether a result survives its own
uncertainty than about how many models were tried.

### Selected projects

| Project | What it found |
|---|---|
| [Association networks on S&P 500 returns](https://github.com/AlbertoGaldinoNogara/sp500-association-networks) | Correlation + FDR control keeps **96% of all possible edges** under market stress. The "network reorganises in a crisis" story is an artefact of the common market factor — once it is removed, the sector signal is unchanged (1.27 vs 1.29 sd) and a block bootstrap puts zero inside every calm-vs-stress interval. |
| [Butterfly image classification](https://github.com/AlbertoGaldinoNogara/Image-Classification) | An inception-style CNN built and trained from scratch — no pretrained weights — reaching **83.8%** on 11 fine-grained classes from 1,816 images. The repo also documents why the augmented-vs-original comparison in the notebook is confounded and cannot be read as an augmentation effect. |
| [Bayesian analysis of leukemia subtypes](https://github.com/AlbertoGaldinoNogara/Bayesian-Analysis-of-Leukemia-Subtypes) | A hand-written Gibbs sampler for a hierarchical multivariate normal model over 18 protein markers. Posterior means of AKT and BAD do not separate the four FAB subtypes; shrinkage towards the population mean accounts for most of what is visible. |
| [Linear models on Boston housing](https://github.com/AlbertoGaldinoNogara/Statistical-analysis-of-Boston-house-pricing) | AIC, BIC, Mallow's Cp, adjusted R² and LOOCV all select the same 11-predictor model — which ANOVA then finds statistically indistinguishable from the full one. Selection bought interpretability, not accuracy. |
| [Named entity recognition](https://github.com/MicheleGiambelli/PlotTwisters-Project) | Team NER project (contributor). |

### Interests

Statistical inference, network data, neural differential equations, and the
places where a modelling choice quietly decides the answer before the data get a
vote.
