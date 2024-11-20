# References

1) Bogdanoff, A. (2024, July 10). Through the looking-glass of the sea surface. Woods Hole Oceanographic Institution. https://www.whoi.edu/oceanus/feature/through-the-looking-glass-of-the-sea-surface/ 
> Figure 1: Photo Credit

2) Fairall, C. W., Bradley, E. F., Hare, J. E., Grachev, A. A., & Edson, J. B. (2003). Bulk Parameterization of Air–Sea Fluxes: Updates and Verification for the COARE Algorithm. Journal of Climate, 16(4), 571–591. https://doi.org/10.1175/1520-0442(2003)016<0571:BPOASF>2.0.CO;2
> Motivation: "Global 'bulk' air-sea flux parameterizations are developed using sparse observations, limiting accuracy across regions and conditions."
> Results: COARE v3.0 Bulk Parameterization

3) Busecke, J., Balwada, D., Martin`, P., Nicholas, T., Stern, C., Johnson, Z., & Abernathey, R. (2024). The Overlooked Sub-Grid Air-Sea Flux in Climate Models. https://doi.org/10.31223/X5WQ47
> Motivation: "Reliable air-sea flux parameterizations of heat and momentum are crucial to coupled atmosphere-ocean models."

4) Johnson, J. E., Febvre, Q., Gorbunova, A., Metref, S., Ballarotta, M., Sommer, J. L., & Fablet, R. (2023). OceanBench: The Sea Surface Height Edition (arXiv:2309.15599). arXiv. http://arxiv.org/abs/2309.15599
> Motivation: "Reliable air-sea flux parameterizations of heat and momentum are crucial to coupled atmosphere-ocean models."

5) Cronin, M. F., Gentemann, C. L., Edson, J., Ueki, I., Bourassa, M., Brown, S., Clayson, C. A., Fairall, C. W., Farrar, J. T., Gille, S. T., Gulev, S., Josey, S. A., Kato, S., Katsumata, M., Kent, E., Krug, M., Minnett, P. J., Parfitt, R., Pinker, R. T., … Zhang, D. (2019). Air-Sea Fluxes With a Focus on Heat and Momentum. Frontiers in Marine Science, 6, 430. https://doi.org/10.3389/fmars.2019.00430
> Motivation: "Reliable air-sea flux parameterizations of heat and momentum are crucial to coupled atmosphere-ocean models."

6) Fairall, C. W. (2010). Observations to Quantify Air-Sea Fluxes and their Role in Climate Variability and Predictability. Proceedings of OceanObs’09: Sustained Ocean Observations and Information for Society, 277–291. https://doi.org/10.5270/OceanObs09.cwp.27
> Motivation: "Reliable air-sea flux parameterizations of heat and momentum are crucial to coupled atmosphere-ocean models."

7) Palmer, M. D., & McNeall, D. J. (2014). Internal variability of Earth’s energy budget simulated by CMIP5 climate models. Environmental Research Letters, 9(3), 034016. https://doi.org/10.1088/1748-9326/9/3/034016
> Motivation: "Reliable air-sea flux parameterizations of heat and momentum are crucial to coupled atmosphere-ocean models."

8) Zanna, L., Khatiwala, S., Gregory, J. M., Ison, J., & Heimbach, P. (2019). Global reconstruction of historical ocean heat storage and transport. Proceedings of the National Academy of Sciences, 116(4), 1126–1131. https://doi.org/10.1073/pnas.1808838115  
> Motivation: "Ocean absorbed >90% of heat gained between 1971-2010"
- >"...the ocean, due to its large heat capacity, has absorbed more than 90% of the heat gained by the planet between 1971 and 2010, with around 290 ZJ (1 ZJ =1021 J) contained in the top 2,000 m (Fig. 1)" (Zanna et al 2019)

9) Tang, R., Wang, Y., Jiang, Y., Liu, M., Peng, Z., Hu, Y., Huang, L., & Li, Z.-L. (2024). A review of global products of air-sea turbulent heat flux: Accuracy, mean, variability, and trend. Earth-Science Reviews, 249, 104662. https://doi.org/10.1016/j.earscirev.2023.104662
> Motivation: "Air-sea latent heat flux accounts for 87% of global surface evapotranspiration"
- >"the ocean LHF evaporating water amount of 436.5 × 103 km3/y that accounts for ~87% of the total evapotranspiration on the Earth’s surface [Oki and Kanae, 2006]" (Tang et al 2024)

10) Oki, T., Kanae, S., 2006. Global hydrological cycles and world water resources. science 313 (5790), 1068–1072.
> Motivation: "Air-sea latent heat flux accounts for 87% of global surface evapotranspiration"
- >"the ocean LHF evaporating water amount of 436.5 × 103 km3/y that accounts for ~87% of the total evapotranspiration on the Earth’s surface [Oki and Kanae, 2006]" (Tang et al 2024)

11) NOAA-GFDL CM2-O Coupled Climate Model Simulations. LEAP Data Catalog. Columbia University. Available at: https://catalog.leap.columbia.edu/feedstock/noaagfdl-cm2o-coupled-climate-model-simulations.
Griffies, S. (2015). A handbook for the GFDL CM2-O model suite.
> Methods Step 1: Global model input features 
   
12) Clayson, Carol Anne; Brown, Jeremiah; and NOAA CDR Program (2016). NOAA Climate Data Record Ocean Surface Bundle (OSB) Climate Data Record (CDR) of Ocean Heat Fluxes, Version 2. NOAA National Center for Environmental Information. doi:doi:10.7289/V59K4885 [November 2024].
> Methods Step 1: Data to create mapping of global sensible and latent heat fluxes. ***Note that in actual research workflow, these fluxes are calculated using bulk parameterizations. Citation is for dataset used to create image on poster.***

13) NOAA Physical Sciences Laboratory. (2023). NOAA PSL FluxBase Synthesis: Ship-based flux measurements (Version 1.0) NOAA Physical Sciences Laboratory. Last modified May 24, 2023. Retrieved from https://downloads.psl.noaa.gov/psd3/cruises/PSL_FluxBase_synthesis/
> Methods and Figures 2-4: *in situ* observational dataset

14) Aerobulk: Brodeau, L., B. Barnier, S. Gulev, and C. Woods, 2016: Climatologically significant effects of some approximations in the bulk parameterizations of turbulent air-sea fluxes. J. Phys. Oceanogr., 47 (1), 5–28, 10.1175/JPO-D-16-0169.1. [ DOI ](http://dx.doi.org/10.1175/JPO-D-16-0169.1)
> Aerobulk: Code to implement the below bulk parameterizations as shown in Results figures, cited separately as follows:
> - COARE v3.0 (Fairall et al., 2003) (see Reference #2)
> - COARE v3.6 (Edson et al., 2013)
> - ECMWF (IFS (Cy40) documentation)
> - ANDREAS (Andreas et al., 2015)
> - NCAR (Large & Yeager 2004, 2009)

15) Python Wrapper: Busecke, J. J. M., Martin, P. E., & Abernathey, R. P. (2024). aerobulk-python (v0.4.2). Zenodo. https://doi.org/10.5281/zenodo.11205116
> Aerobulk Python Wrapper: Code to implement the below bulk parameterizations as shown in Results figures, cited separately as described above.

16) Edson, J. B., Jampana, V., Weller, R. A., Bigorre, S. P., Plueddemann, A. J., Fairall, C. W., Miller, S. D., Mahrt, L., Vickers, D., & Hersbach, H. (2013). On the Exchange of Momentum over the Open Ocean. Journal of Physical Oceanography, 43(8), 1589–1610. https://doi.org/10.1175/JPO-D-12-0173.1
> COARE 3.6 Bulk Parameterization

17) ECMWF, (2014). IFS documentation—Cy40r1. Operational implementation 22 November 2013. Part IV: Physical processes. ECMWF, accessed November 2024. Available online at [ECMWF IFS Documentation CY40 Part IV](https://www.ecmwf.int/en/elibrary/74322-ifs-documentation-cy40r1-part-iv-physical-processes)
> ECMWF Bulk Parameterization
  
18) Large, W. G., & Yeager, S. G. (2009). The global climatology of an interannually varying air–sea flux data set. Climate Dynamics, 33(2–3), 341–364. https://doi.org/10.1007/s00382-008-0441-3
> NCAR Bulk Parameterization

19) Andreas, E. L., Mahrt, L., & Vickers, D. (2015). An improved bulk air–sea surface flux algorithm, including spray‐mediated transfer. Quarterly Journal of the Royal Meteorological Society, 141(687), 642–654. https://doi.org/10.1002/qj.2424
> Andreas Bulk Parameterization















 





