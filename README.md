# Brain structure-based pain predictive model
- Sensitivity to pain shows a remarkable interindividual variance that has been reported to both forecast and accompany various clinical pain conditions. Although pain thresholds have been reported to be associated to brain morphology, it is still unclear how well these findings replicate in independent data and whether they are powerful enough to provide reliable pain sensitivity predictions on the individual level.
- In this study, we constructed a predictive model of pain sensitivity (as measured with pain thresholds) using structural magnetic resonance imaging–based cortical thickness data from a multicentre data set (3 centres and 131 healthy participants).
- Cross-validated estimates revealed a statistically significant and clinically relevant predictive performance (Pearson r = 0.36, P < 0.0002, R2 = 0.13). The predictions were found to be specific to physical pain thresholds and not biased towards potential confounding effects (eg, anxiety, stress, depression, centre effects, and pain self-evaluation).
- Analysis of model coefficients suggests that the most robust cortical thickness predictors of pain sensitivity are the right rostral anterior cingulate gyrus, left parahippocampal gyrus, and left temporal pole. Cortical thickness in these regions was negatively correlated to pain sensitivity.
- Our results can be considered as a proof-of-concept for the capacity of brain morphology to predict pain sensitivity, paving the way towards future multimodal brain-based biomarkers of pain.

**_The main findings regarding model performance, learning rate, feature importance and out-of-center generalizability findings are presented below._**
![Main findings](/assets/img/main_fig.jpg)

The dockerfile for the POS is available at [DockerHub](https://hub.docker.com/r/pnilab/ctp-signature/tags). 
The dockerfile has setup for performing surface-based morphometry, and calculating individual pain sensitivity ratings based on gray matter cortical thickness measures as features for the predictive model.

# Downloads
The implementation of this pain signature is available as a [GitHub repo](https://github.com/pni-lab/ctp-signature).
