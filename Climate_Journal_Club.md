## Oct 2021

### Above-anvil Cirrus Plume(AACP)

* Features:

  * AACP appears in advance of severe weather (Indicates it is not only the overshooting that cause the hail. AACP storm should form after the overshooting and before the hail)
  * Last <1h
  * Increase forecast confidence that large hail will occur

  ** bedroom cycle??

* Why care about it?
  * Forecast

* Severe thunder storm is a covariate of CAPE and bottom 6km wind shear:

  * Upper and lower shear -> updraft and downdraft
  * 

* Important knowledge:

  * Clausius-Clapeyron scaling:

    * $\frac{de_s}{e_sdT} \approx 7 \%/K$

    

### Machine learning to evaluating the models

* Processes: (Causal network)
  * Creates 20 models and observations
  * Take Pierce analysis (Put the data to risen functions and get Eigen values)
  * Choose the region of variability. (b)
  * Find the link between regions. Distinguish spurious link and the real links(c). And generate the model.
    * Some of them are intrinsic, while some of them are caused by others.
    * May based on the value of the coefficient. 
  * Compare the model by the network they made.  
