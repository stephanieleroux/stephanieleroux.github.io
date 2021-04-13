---
layout: page
title: Research
permalink: /Research/
order: 2
---

### Some on-going projects at Ocean Next: 
---

#### 1. Ensemble quantification of  short-term predictability  of the ocean fine-scale dynamics
[![image]({{site.baseurl}}/img/MEDWEST60config.png)](http://stephanieleroux.github.io/research)

In this project, we investigate the predictability properties of the ocean dynamics using an ensemble of medium range numerical forecasts. This question is particularly relevant for ocean dynamics at small scales (< 30 km), where sub-mesoscale dynamics is responsible for the fast evolution of ocean properties. Relatively little is known about the predictability properties of a high resolution model, and hence about the accuracy and resolution that is needed from the observation system used to generate the initial conditions.

A kilometric-scale regional configuration of NEMO for the Western Mediterranean (MEDWEST60, at 1/60º horizontal resolution) has been developed, using boundary conditions from a larger  North Atlantic configuration at same resolution (eNATL60). This deterministic model has then been transformed into a probabilistic model by introducing innovative stochastic parameterizations of model uncertainties resulting from unresolved processes. The purpose is here primarily to generate ensembles of  model states to initialize predictability experiments. The stochastic parameterization is also applied to assess the possible impact of irreducible model uncertainties on the skill of the forecast. A set of three ensemble experiments (20 members and 2 months ) are performed, one  with the deterministic model initiated with perturbed initial conditions, and two with the stochastic model, for two different amplitudes of model uncertainty. In all three experiments, the spread of the ensemble is shown to emerge from the small scales (10 km wavelength) and progressively upscales to the largest structures. After two months, the ensemble variance saturates over most of the spectrum (except in the largest scales), whereas the small scales (< 30 km) are fully decorrelated between the different members. These ensemble simulations are thus appropriate to provide a statistical description of the dependence between initial accuracy and forecast accuracy over the full range of potentially-useful forecast time-lags (typically, between 1 and 20 days).   

The predictability properties are statistically assessed using a cross-validation algorithm (i.e. using alternatively each ensemble member as the reference truth and the remaining 19 members as the ensemble forecast) together with a specific score to characterize the initial and forecast accuracy. From the joint distribution of initial and final scores, it is then possible to quantify the probability distribution of the forecast score given the initial score, or reciprocally to derive conditions on the initial accuracy to obtain a target forecast skill. In this contribution, the misfit between ensemble members is quantified in terms of overall accuracy (CRPS score), geographical position of the ocean structures (location score), and  spatial spectral decorrelation of the Sea Surface Height 2-D fields (spectral score). For example, our results show that, in the region and period  of interest, the initial location accuracy required (necessary condition) with a perfect model (deterministic) to obtain a location accuracy of the forecast of 10 km with a 95% confidence is about 8 km for a 1-day forecast, 4 km for a 5-day forecast, 1.5 km for a 10-day forecast, and this requirement cannot be met with a 15-day or longer forecast.

* The MEDWEST60 github is here: [https://github.com/ocean-next/MEDWEST60](https://github.com/ocean-next/MEDWEST60).

* More [references to be found on this page](https://github.com/ocean-next/MEDWEST60/blob/main/01_Documents.md).



---
#### 2. Learning from large-ensemble ocean simulations to better interpret satellite and in-situ ocean data.
[![image]({{site.baseurl}}/img/occischemewebsite_hiRes.png)](http://stephanieleroux.github.io/Research/) 

Over the last decades, altimeter and other satellite and in-situ ocean observations have provided crucial information to increase our knowledge of the global oceanic state, its variability, and long-term changes.
Comparing observations to ocean numerical simulations is a routinely-used approach to either validate models,  calibrate new observation systems, or inverstigate physical processes and mechanisms.  But such comparison requires some knowledge of the different types of uncertainties attached to the compared datasets.

Given the chaotic, non-linear nature of the ocean system, ocean models in the turbulent regime are highly sensitive to initial conditions and spontaneously generate a chaotic intrinsic variability that has recently been shown to be significant even on low-frequency (interannual and longer periods) and on basin scale (e.g. Penduff et al, 2011, Serazin et al, 2015, Leroux et al 2017).

Performing ensemble simulations is a way to take into account this intrinsic uncertainty, inherent to the ocean circulation, by sampling a range of possible trajectories of equal likelihood.
In other words, it means that the most accurate collection of satellite/in-situ observations can only fit a model simulation up to a certain point, as  the observations describe the one time-evolution that the ocean state has followed in reality, randomly picked among an ensemble of possible evolutions seen as equally-likely by an ocean model.

At [Ocean Next](http://www.ocean-next.fr), in partnership with the [MEOM](https://meom-group.github.io/) group within several projects (e.g.  ANR [OCCIPUT](https://meom-group.github.io/projects/occiput/) and  PIRATE-OSTST), we develop such  probabilistic approaches, based on large-ensemble eddy-permitting ocean simulations. Our goal is to better quantify and characterize the model uncertainty related to the intrinsic variabity of the ocean, and to provide useful information to better interpret satellite and in-situ ocean data. It includes  a quantification of the chaotic variability and a better characterization of the locations, depth, temporal and spatial scales that are the most affected by a chaotic behaviour in models, and wich are thus  affected by  the largest uncertainty in any comparison with satellite or in-situ observations.


### My research background:
  - Variability of the climate system : ocean and atmosphere numerical modeling and statistical analysis. 
  - Keywords: *Eddy-permitting ocean GCMs, ocean low-frequency intrinsic variability, ensemble simulations, Atmospheric GCMs, tropical variability, convectively coupled equatorial waves, MJO, deep convection, west-african monsoon, teleconnexions.*
  - See my list of peer-reviewed publications [here](http://stephanieleroux.github.io/publications/) or on [Research Gate](http://www.researchgate.net/profile/Stephanie_Leroux).


[![image]({{site.baseurl}}/img/ensemble.png)](http://stephanieleroux.github.io/research) | [![image]({{site.baseurl}}/img/hires.png)](https://stephanieleroux.github.io)
