####################################################################
The Goddard Earth Observing System - NASA Ocean Biogeochemical Model 
####################################################################

*****************************************************************************
What is the Goddard Earth Observing System - NASA Ocean Biogeochemical Model?
*****************************************************************************

The Goddard Earth Observing System - NASA Ocean Biogeochemical Model is a fully-coupled, data-assimilative model that simulates the Earth's climate while assimilating different observational datasets. The model simulates the evolution of coupled atmosphere (AGCM), ocean (MOM), sea ice (CICE), ocean biogeochemistry (NOBM), and aerosol and carbon gas (GOCART) component models.

How does GEOS-NOBM simulate ocean biogeochemistry?
==================================================
The ocean physical model is the Modular Ocean Model v6 (MOM6) which has a nominal 0.25 degree resolution and 40 vertical levels on an isopycnal coordinate system. The ocean physical model simulates surface waters to 10m depth, allowing coastal dynamics to be resolved. Physical circulation fields simulated by MOM6 advect tracers simulated by the NASA Ocean Biogeochemical Model (NOBM), producing horizontal and vertical gradients. 

NOBM consists of an ecological module which incorporates multi-nutrient co-limitation of nitrate, regenerated ammonium, silicate, and iron. The NOBM simulates six phytoplankton functional types (PFTs): diatoms, chlorophytes, cyanobacteria, coccolithophores, dinoflagellates, and *Phaeocystis*. Each PFT plays a unique role in the marine ecosystem and differ in growth rates, sinking rates, nutrient requirements, and optical properties. Additionally, the ecosystem model simulates a single generic zooplankton functional type (ZFT) with different grazing rates and half saturation constants prescribed for different PFTs (e.g., slower zooplankton grazing rates for larger phytoplankton i.e, diatoms). The NOBM represents ocean carbon cycling explicitly by simulating dissolved organic carbon (DOC) and dissolved inorganic carbon (DIC) pools. Sources of DOC include phytoplankton, zooplankton, and carbon detritus, while sources of DIC include phytoplankton, zooplankton, carbon detritus, and air-sea fluxes.

How is the GEOS-NOBM initialized?
=================================
The model is initialized from World Ocean Atlas (WOA) 2018 nitrate and silicate concentrations. Dissolved iron fields are derived from Huang et al., 2022 and Fung et al., 2000 which provide spatial fields computed from both satellite and reanalysis products. Alkalinity and dissolved inorganic carbon (DIC) are initialized using the Global Data Analysis Project v2 (GLODAPv2). Particulate inorganic carbon (PIC), dissolved organic carbon (DOC), and colored dissolved organic carbon (CDOC) are initialized to 0 $\mu$g L$^{-1}$, 0 $\mu$M, and 0 $\mu$M, respectively. All phytoplankton concentrations are initialized at 0.5 mg Chl m$^{-3}$.

Relation to other data-assimilative ocean biogeochemical models?
================================================================
Discuss that many data-assimilative ocean biogeochemical models are limited to regional studies [e.g., Verdy and Mazloff, 2017; Mattern et al., 2017] or to short time periods [e.g., Brix et al., 2015]. 
