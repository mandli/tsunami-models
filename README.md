# Tsunami Models List

This list is meant to be a community effort to both list and categorize the
available tsunami models currently **maintained** and publicly (openly)
available.  This list was started based on a review paper that is currently
itself under review.  Check back soon for a draft and how to contribute.

**Citation:** 
Marras, S.; Mandli, K.T. *Modeling and Simulation of Tsunami Impact: A Short Review of
Recent Advances and Future Challenges.* **Geosciences** (2021) 11, 5.


| Model                  | SpaceDim.           | Equations | Turbul.     | Wavebreak. | FSI | MP  | SD    |
|------------------------|---------------------|-----------|-------------|------------|-----|-----|-------|
| GeoCLAW[1]             | 1D/2D/2D(1/2)       | SW        | No          | No         | No  | No  | FV    |
| NUMA2D[2][3]           | 1D/2D               | SW        | No          | No         | No  | No  | SE/DG |
| MOST[4]                | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| Cliffs[5]              | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| Tsunami-HySEA[6a,b,c]  | 1D/2D               | SW/B      | No          | Yes        | No  | No  | FV    |
| Multilayer-HySEA[7,8]  | 1D/2D(1/2)          | SW/B      | No          | Yes        | No  | Yes | FV    |
| TUNAMI[9,10]           | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| NAMI-DANCE[11]         | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| COMCOT[12]             | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| SELFE[13]              | 1D/2D               | SW        | No          | No         | No  | No  | FE    |
| TsunAWI[14]            | 1D/2D               | SW        | No          | No         | No  | No  | FE    |
| TsunaFlash[15]         | 1D/2D               | SW        | No          | No         | No  | No  | FE/DG |
| VOLNA[16,17]           | 1D/2D               | SW        | No          | No         | No  | No  | FV    |
| Delft3D[18]            | 1D/2D               | SW        | No          | No         | No  | Yes | FD    |
| Basilisk[19-21]        | 2D/3D               | SGN       | No          | Yes        | No  | Yes | FV    |
| BOSZ[22]               | 1D/2D               | B         | No          | No         | No  | No  | FV/FD |
| Celeris[23]            | 1D/2D               | B         | No          | No         | No  | No  | FV    |
| FUNWAVE[24,25]         | 1D/2D               | B         | No          | No         | No  | No  | FV/FD |
| pCOULWAVE[26,27]       | 2D/3D               | B         | Yes         | No         | No  | No  | FV    |
| NEOWAVE[28]            | 2D                  | B         | No          | No         | No  | No  | FD    |
| GPUSPH[29]             | 3D                  | SPH       | No          | Yes        | No  | No  | SPH   |
| SCHISM[30]             | 1D/2D/3D            | N-S       | RANS        | Yes        | No  | No  | FE/FV |
| COBRAS[31,32]          | 2D/3D               | N-S       | RANS        | Yes        | No  | No  | FD    |
| TSUNAMI3D[33,34]       | 2D/3D               | N-S       | RANS        | Yes        | No  | No  | FD    |
| waves2FOAM[35-37]      | 2D(tsunami)         | N-S       | RANS        | Yes        | No  | No  | FV    |
| NHWAVE[38]             | 2D/3D               | N-S       | LES         | Yes        | Yes | Yes | FV/FD |
| Alya[39,40]            | 2D/3D               | N-S       | LES/WM/RANS | Yes        | Yes | Yes | FE    |


# References
[1] Berger, M.; George, D.; LeVeque, R.; Mandli, K.  The GeoClaw software for depth-averaged flows withadaptive refinement.Adv. Water Res. 2011,34, 1195–1206.

[2] Marras, S.; Kopera, M.; Giraldo, F.X.  Simulation of Shallow Water Jets with a Unified Element-basedContinuous/Discontinuous Galerkin Model with Grid Flexibility on the Sphere.Q. J. Roy. Meteor. Soc. 2015,141, 1727–1739.

[3] Marras, S.; Kopera, M.; Constantinescu, E.; Suckale, J.; Giraldo, F.  A Residual-based Shock CapturingScheme for the Continuous/Discontinuous Spectral Element Solution of the 2D Shallow Water Equations.Adv. Water Res. 2018,114, 45–63.

[4] Titov, V.V.; Gonzalez, F. Implementation and testing of the Method Of Splitting Tsunami (MOST) model.NOAA Technical Memorandum ERL PMEL-112 1927, NOAA, Seattle, WA,USA. Technical report, 1997.

[5] Tolkova, E. Land–water boundary treatment for a tsunami model with dimensional splitting.Pure Appl.Geophys. 2014,171, 2289–2314.

[6a] Macías, J.; Castro, M.; Ortega, S.; Escalante, C.; González-Vida, J. Performance Benchmarking of
Tsunami-HySEA Model for NTHMP’s Inundation Mapping Activities. Pure Appl. Geophys. 2017,
174, 3147–3183.

[6b] Macías, J.; Castro, M.; Ortega, S.; González-Vida, J. Performance assessment of Tsunami-HySEA model for
NTHMP tsunami currents benchmarking. Field cases. Ocean Modelling 2020, 152, 101645.

[6c] Macías, J.; Castro, M.; Escalante, C. Performance assessment of the Tsunami-HySEA model for NTHMP
tsunami currents benchmarking. Laboratory data. Coastal Engineering 2020, 158, 103667.

[7] Macías, J.; Escalante, C.; Castro, M.J. Multilayer-HySEA model validation for landslide generated tsunamis.Part I Rigid slides.Natural Hazards and Earth System Sciences Discussions.  10.5194/nhess-2020-1712020, 2020, 1–33.

[8] Macías, J.; Escalante, C.; Castro, M.J. Multilayer-HySEA model validation for landslide generated tsunamis.Part II Granular slides.Natural Hazards and Earth System Sciences Discussions, 10.5194/nhess-2020-1722020, 2020, 1–34.

[9] Imamura, F.   Tsunami numerical simulation with the staggered leap-frog scheme (numerical code ofTUNAMI-N1 and N2), 1989.

[10] Imamura, F.; Yalciner, A.; Ozyurt, G. Tsunami Modelling Manual.  Technical report,  2006.

[11] Yalciner,  A.;  Pelinovsky,  E.;  Zaytsev,  A.;  Kurkin,  A.;  Ozer,  C.;  Karakus,  H.   NAMI DANCE Manual.Technical report, METU, Civil Engineering Department, Ocean Engineering Research Center, Ankara,Turkey, 2006.

[12] Wang, X. User manual for COMCOT version 1.7.  Technical report, 2009.

[13] Zhang, Y.; Baptista, A. An efficient and robust tsunami model on unstructured grids. Part I: inundationbenchmarks.Pure Appl. Geophys. 2008,165, 2229–2248.

[14] Harig, S.; Chaeroni, X.; Pranowo, W.; Behrens, J.  Tsunami simulations on several scales: comparison ofapproaches with unstructured meshes and nested grids.Ocean Dyn. 2008,58, 429–440.

[15] Pranowo,  W.;  Behrens,  J.;  Schlicht,  J.;  Ziemer,  C.Adaptive  mesh  refinement  applied  to  tsunamimodeling:  TsunaFLASH.  In Proc.  Int.  Conf.  on Tsunami Warning (ICTW) (ed.  H Adrianto).  Jakarta,Indonesia:  State Ministry of Research and Technology, Republic of Indonesia (RISTEK). Available at:http://hdl.handle.net/10013/epic.32425.d001,  2008.

[16] Dutykh, D.; Poncet, R.; Dias, F. The VOLNA code for the numerical modeling of tsunami waves: generation,propagation and inundation.Eur. J. Mech. B/Fluids 2011,30, 598–615.

[17] Reguly,  I.Z.;  Giles,  D.;  Gopinathan,  D.;  Quivy,  L.;  Beck,  J.H.;  Giles,  M.B.;  Guillas,  S.;  Dias,  F.   TheVOLNA-OP2 tsunami code (version 1.5).Geoscientific Model Development 2018, 11, 4621–4635.

[18] Roelvink,  J.;  Van  Banning,  G.Design  and  development  of  DELFT3D  and  application  to  coastalmorphodynamics.Oceanographic Lit. Review 1995,42, 925–

[19] Popinet,  S.   Basilisk:  simple abstractions for octree-adaptive scheme.SIAM conference on ParallelProcessing for Scientific Computing. April 12-15; 2016.

[20] Popinet, S.   A quadtree-adaptive multigrid solver for the Serre–Green–Naghdi equations.Journal ofComputational Physics 2015,302, 336 – 358.  doi:https://doi.org/10.1016/j.jcp.2015.09.009

[21] Popinet, S. A vertically-Lagrangian, non-hydrostatic, multilayer model for multiscale free-surface flows.Journal of Computational Physics 2020,418, 109609.  doi:https://doi.org/10.1016/j.jcp.2020.109609.

[22] Roeber, V.; Cheung, K. Boussinesq-type model for energetic breaking waves in fringing reef environment.Coast. Eng. 2012,70, 1–20.

[23] Tavakkol, S.; Lynett, P.  Celeris: A GPU-accelerated open source software with a Boussinesq-type wavesolver for real-time interactive simulation and visualization.Computer Physics Communications 2017,217, 117 – 127.

[24] Kennedy, A.; Chen, Q.; Kirby, J.; Dalrymple, R. Boussinesq modeling of wave transformation, breakingand runup, part I: 1D.J. Waterw. Port Coast. Ocean Eng. 2000,126, 39–47.

[25] Shi, F.; Kirby, J.; Harris, J.; Geiman, J.; Grilli, S.  A high-order adaptive time-stepping TVD solver forBoussinesq modeling of breaking waves and coastal inundation.Ocean Model. 2012,43-44, 36–51

[26] Lynett, P.; Wu, T.; P.L.F., L.  Modeling wave runup with depth-integrated equations.Coast.  Eng. 2002, 46:89–107.

[27] Kim, D.; Lynett, P.  Turbulent mixing and passive scalar transport in shallow flows.Phys.  Fluids 2011,23, 016603.

[28] Yamazaki, Y.; Kowalik, Z.; Cheung, K. Depth-integrated, non-hydrostatic model for wave breaking andrun-up.Int. J. Numer. Meth. Fluids 2009,61, 473–497.

[29] Wei, Z.; Dalrympl, R.; Hérault, A.; Bilotta, G.; Rustico, E.; Yeh, H.  SPH modeling of dynamic impact oftsunami bore on bridge pier.Coast. Eng. 2015,104, 26–42.

[30] Zhang, Y.; Ye, F.; Stanev, E.; Grashorn, S. Seamless cross-scale modeling with SCHISM, Ocean Modelling.Ocean Model. 2016,102, 64–81.

[31] Lin, P.; Liu, P. A numerical study of breaking waves in the surf zone.J. Fluid Mech. 1998,358, 239–264.

[32] Lin, P.; Liu, P. Turbulence transport, vorticity dynamics, and solute mixing under plunging breaking wavesin surf zone.J. Geophys. Res. 1998,103 C8

[33] Horrillo, J.; Wood, A.; Kim, G.; Parambath, A.  A simplified 3-D /Navier–Stokes numerical model forlandslide tsunami: Application to the Gulf of Mexico.J. Geophys. Res./Oceans 2013,118, 6934–6950.

[34] Horrillo, J.; Grilli, S.; Nicolsky, D.; Roeber, V.; Zhang, J. Performance benchmarking tsunami models forNTHMP’s inundation mapping activities.Pure Appl. Geophys. 2015,172, 869–884

[35] Jacobsen,  N.;  Fuhrman,  D.;  Fredsoe,  J.   A wave generation toolbox for the open-source CFD library:OpenFOAM (R).Int. J. Numer. Methods Fluids 2012,70, 1073–1088.

[36] Larsen, B.; Fuhrman, D.  Full-scale CFD simulation of tsunamis.  Part 1:  Model validation and run-up.Coastal Engineering 2019,151

[37] Larsen, B.; Fuhrman, D.  Full-scale CFD simulation of tsunamis. Part 2: Boundary layers and bed shearstresses.Coastal Engineering 2019,151.

[38] Ma, G.; Shi, F.; Kirby, J. Shock-capturing non-hydrostatic model for fully dispersive surface wave processes.Ocean Modeling 2012,43-44, 22–35

[39] Vázquez, M.; Houzeaux, G. Alya: Multiphysics Engineering Simulation Towards Exascale.J. Comput. Sci 2016.

[40] Mukherjee,  A.;  Cajas,  J.;  Houzeaux,  G.;  Lehmkuhl,  O.;  Vázquez,  M.;  Suckale,  J.;  Marras,  S.   Usingfluid-structure interaction to evaluate the energy dissipation of a tsunami run-up through idealized flexible trees. sciencesconf.org:parcfd2020:3202002020.




