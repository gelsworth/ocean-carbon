#########################################
The GEOS-NOBM Ocean Carbon State Estimate
#########################################

############################################
What is the GEOS-NOBM Carbon State Estimate?
############################################

The Goddard Earth Observing System - NASA Ocean Biogeochemical Model is a fully coupled data-assimilative model that simulates the Earth's climate while assimilating various observational datasets. The model simulates the evolution of coupled atmosphere (AGCM), ocean (MOM), sea ice (CICE), ocean biogeochemistry (NOBM), and aerosol and carbon gas component (GOCART) models.

How does GEOS-NOBM simulate ocean biogeochemistry?
==================================================
The ocean physical model is the Modular Ocean Model v6 (MOM6) which has a nominal 0.25\textdegree\ resolution and 40 vertical level on an isopycnal coordinate system. The ocean physical model simulates surface waters to 10m depth, allowing coastal dynamics to be resolved. Physical circulation fields simulated by MOM6 advect tracers simulated by the NASA Ocean Biogeochemical Model (NOBM), producing horizontal and vertical gradients. 

NOBM consists of an ecological module which incorporates multi-nutrient co-limitation of nitrate, regenerated ammonium, silicate, and iron. The NOBM simulates six phytoplankton functional types (PFTs): diatoms, chlorophytes, cyanobacteria, coccolithophores, dinoflagellates, and \emph{Phaeocystis}. Each PFT plays a unique role in the marine ecosystem and differ in growth rates, sinking rates, nutrient requirements, and optical properties. Additionally, the ecosystem model simulates a single generic zooplankton functional type (ZFT) with different grazing rates and half saturation constants prescribed for different PFTs (e.g., slower zooplankton grazing rates for larger phytoplankton i.e, diatoms). The NOBM represents ocean carbon cycling explicitly by simulating dissolved organic carbon (DOC) and dissolved inorganic carbon (DIC) pools. Sources of DOC include phytoplankton, zooplankton, and carbon detritus, while sources of DIC include phytoplankton, zooplankton, carbon detritus, and air-sea fluxes.
