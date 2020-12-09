# Tsunami Models List

This list is meant to be a community effort to both list and categorize the
available tsunami models currently **maintained** and publicly (openly)
available.  This list was started based on a review paper that is currently
itself under review.  Check back soon for a draft and how to contribute.

| Model                  | SpaceDim.           | Equations | Turbul.     | Wavebreak. | FSI | MP  | SD    |
|------------------------|---------------------|-----------|-------------|------------|-----|-----|-------|
| GeoCLAW[1]             | 1D/2D/2D(1/2)       | SW        | No          | No         | No  | No  | FV    |
| NUMA2D[2][3]           | 1D/2D               | SW        | No          | No         | No  | No  | SE/DG |
| MOST[4]                | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| Cliffs[5]              | 1D/2D               | SW        | No          | No         | No  | No  | FD    |
| Tsunami-HySEA[6]       | 2D                  | SW        | No          | No         | No  | No  | FV    |
| Multilayer-HySEA[7,8]  | 2D(1/2)             | SW        | No          | No         | No  | Yes | FV    |
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
[1] Berger, M.; George, D.; LeVeque, R.; Mandli, K.  The GeoClaw software for depth-averaged flows withadaptive refinement.Adv. Water Res.2011,34, 1195–1206.\n
[2] Marras, S.; Kopera, M.; Giraldo, F.X.  Simulation of Shallow Water Jets with a Unified Element-basedContinuous/Discontinuous Galerkin Model with Grid Flexibility on the Sphere.Q. J. Roy. Meteor. Soc.2015,141, 1727–1739.\n
[3] Marras, S.; Kopera, M.; Constantinescu, E.; Suckale, J.; Giraldo, F.  A Residual-based Shock CapturingScheme for the Continuous/Discontinuous Spectral Element Solution of the 2D Shallow Water Equations.Adv. Water Res.2018,114, 45–63.\n
[4] Titov, V.V.; Gonzalez, F. Implementation and testing of the Method Of Splitting Tsunami (MOST) model.NOAA Technical Memorandum ERL PMEL-112 1927, NOAA, Seattle, WA,USA. Technical report, 1997.\n
... TBC\n


