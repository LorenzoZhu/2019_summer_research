A brief describution of the simulation(3).

#PACKAGES:

  -Planet population: SAG13
    Population based on Kepler radius distribution with RV-like semi-major axis distribution with exponential       decay.

-OpticalSystem: Nemati
  Optical system model based on
  Nemati, Bijan (2014) Detector selection for the WFIRST-AFTA coronagraph integral field spectrograph,   Proc. SPIE, 91430
  https://ui.adsabs.harvard.edu/abs/2014SPIE.9143E..0QN/abstract

-StarCatalog: EXOCAT-1
  EXOCAT-1 star catalog, 2347 nearby stars within 30pc from Hipparcos catalog
  Using 1985 stars for simulation after nan and binary filtering
  https://ui.adsabs.harvard.edu/abs/2015arXiv151001731T/abstract

-ZodiacalLight: Stark
  Zoducal light model based on
  Stark, C., Roberge, A., Mandell, A., and Robinson, T. D. (2014) Maximizing the ExoEarth Candidate Yield   from a Future Direct Imaging Mission, ApJ 795(2)

-PlanetPhysicalModel: Forecaster
  Planet M-R relation model based on the FORECASTER software, Chen & Kippling 2016.
  https://ui.adsabs.harvard.edu/abs/2017ApJ...834...17C/abstract

-Completness: prtotype
  Return a completness of 0.2 for every target


#ISSUES(01162020)

-For now there are just jupyter-like planets' evolutionary cooling curve extrapolated from fortney's model.
-Can't extrapolate cooling curves for lighter mass rocky planets from Linder's Model.
