# Climate and Air-Quality Benefits of a Realistic Phase-Out of Fossil Fuels

The processing and figure plotting code is in one self-contained notebook, `scenarios.ipynb`. Ancillary data used to make figures has been downloaded into the `input_data` directory and the `output_data` directory contains netCDF files of FaIR output (the simple climate model used in this study; Smith et al., 2018). The figures produced are in the `figures` directory.

To make the scenarios, this package uses below 1.5&deg;C and 1.5&deg;C low-overshoot scenarios hosted by the IAMC Scenario Explorer, v2.0 (Huppmann et al., 2019) that originally contributed to Chapter 2 of the IPCC's Special Report on Global Warming of 1.5&deg;C (Rogelj et al., 2018). 

We are grateful also to the following groups for their datasets, which are included in this notebook:
- Temperature datasets:
  - Cowtan & Way (Cowtan & Way, 2014)
  - Berkeley Earth (Rohde et al., 2013)
  - HadCRUT4 (Morice et al., 2012)
  - NOAA (Vose et al., 2012)
  - GISTEMP (Hansen et al., 2010)
- Carbon fluxes:
  - Global Carbon Project (Le Quéré et al., 2018)


## References:
Cowtan, K. & R.G. Way. Coverage bias in the HadCRUT4 temperature series and its impact on recent temperature trends. Q. J. R. Meteorol. Soc. 140, 1935-1944 (2014).

Hansen, J., R. Ruedy, M. Sato, and K. Lo. Global surface temperature change. Rev. Geophys., 48, RG4004, doi:10.1029/2010RG000345 (2010).

Huppmann, D., E. Kriegler, V. Krey, K. Riahi, J. Rogelj, K. Calvin, F. Humpenoeder, A. Popp, S.K. Rose, J. Weyant, N. Bauer, C. Bertram, V. Bosetti, J. Doelman, L. Drouet, J. Emmerling, S. Frank, S. Fujimori, D. Gernaat, A. Grubler, C. Guivarch, M. Haigh, C. Holz, G. Iyer, E. Kato, K. Keramidas, A. Kitous, F. Leblanc, J.-Y. Liu, K. Löffler, G. Luderer, A. Marcucci, D. McCollum, S. Mima, R.D. Sands, F. Sano, J. Strefler, J. Tsutsui, D. van Vuuren, Z. Vrontisi, M. Wise, and Runsen Zhang. IAMC 1.5°C Scenario Explorer and Data hosted by IIASA. Integrated Assessment Modeling Consortium & International Institute for Applied Systems Analysis, 2019. doi: 10.5281/zenodo.3363345 | url: data.ene.iiasa.ac.at/iamc-1.5c-explorer (2019)

C. Le Quéré, R.M. Andrew, P. Friedlingstein, S. Sitch, J. Hauck, J. Pongratz, P.A. Pickers, J.I. Korsbakken, G.P. Peters, J.G. Canadell, A. Arneth, V.K. Arora, L. Barbero, A. Bastos, L. Bopp, F. Chevallier, L.P. Chini, P. Ciais, S.C. Doney, T. Gkritzalis, D.S. Goll, I. Harris, V. Haverd, F.M. Hoffman, M. Hoppema, R.A. Houghton, G. Hurtt, T. Ilyina, A.K. Jain, T. Johannessen, C.D. Jones, E. Kato, R.F. Keeling, K. Klein Goldewijk, P. Landschützer, N. Lefèvre, S. Lienert, Z. Liu, D. Lombardozzi, N. Metzl, D.R. Munro, J.E.M.S. Nabel, S. Nakaoka, C. Neill, A. Olsen, T. Ono, P. Patra, A. Peregon, W. Peters, P. Peylin, B. Pfeil, D. Pierrot, B. Poulter, G. Rehder, L. Resplandy, E. Robertson, M. Rocher, C. Rödenbeck, U. Schuster, J. Schwinger, R. Séférian, I. Skjelvan, T. Steinhoff, A. Sutton, P.P. Tans, H. Tian, B. Tilbrook, F.N. Tubiello, I.T. van der Laan-Luijkx, G.R. van der Werf, N. Viovy, A.P. Walker, A.J. Wiltshire, R. Wright, S. Zaehle, and Bo Zheng. Global Carbon Budget 2018, Earth Syst. Sci. Data, 10, 2141–2194, https://doi.org/10.5194/essd-10-2141-2018 (2018)

Morice, C.P., J.J. Kennedy, N.A. Rayner and P.D. Jones. Quantifying uncertainties in global and regional temperature change using an ensemble of observational estimates: The HadCRUT4 dataset. J. Geophys. Res. 117, D08101 (2012)

Rogelj J., D. Shindell, K. Jiang, S. Fifita, P. Forster, V. Ginsburg, C. Handa, H. Kheshgi, S. Kobayashi, E. Kriegler, L. Mundaca, R. Séférian, and M. Virginia Vilariño.
Mitigation pathways compatible with 1.5°C in the context of sustainable development.
In "Global Warming of 1.5°C. An IPCC Special Report on the impacts of global warming of 1.5°C above pre-industrial levels and related global greenhouse gas emission pathways, in the context of strengthening the global response to the threat of climate change, sustainable development, and efforts to eradicate poverty".
Masson-Delmotte, V., P. Zhai, H.-O. Pörtner, D. Roberts, J. Skea, P.R. Shukla, A. Pirani, W. Moufouma-Okia, C. Péan, R. Pidcock, S. Connors, J.B.R. Matthews, Y. Chen, X. Zhou, M.I. Gomis, E. Lonnoy, T. Maycock, M. Tignor, and T. Waterfield (eds.)
Intergovernmental Panel on Climate Change, Geneva (2018)
url: http://www.ipcc.ch/report/sr15/

Rohde, R., R. Muller, R. Jacobsen, S. Perlmutter, A. Rosenfeld, J. Wurtele, J. Curry, C. Wickham and S. Mosher. Berkeley Earth temperature averaging process. Geoinfor. Geostat. An Overview, 1, https://doi.org/10.4172/2327-4581.1000103 (2013).

Smith, C.J., P.M. Forster, M. Allen, N. Leach, R.J. Millar, G.A. Passerello and L.A. Regayre. FAIR v1.3: a simple emissions-based impulse response and carbon cycle model, Geosci. Model Dev., 11, 2273-2297, https://doi.org/10.5194/gmd-11-2273-2018 (2018)

Vose, R.S., S. Applequist, M.J. Menne, C.N. Williams Jr. and P. Thorne. NOAA’s merged land–ocean surface temperature analysis. Bull. Am. Meteorol. Soc. 93, 1677–1685 (2012).

