# CC-cropclass
Cloud Computing project for crop classification over Missouri

## Background
Crop classification and the detection of crop phenological cycles is one of the many possibilities of satellite remote sensing for agricultural areas. The reflectence of different spectra changes over the course of the year, revealing information about plant growth stages and thus characteristics of different plant types. These can then be used for crop classification.
As cotton is one of the main cash crops in the world, supplying about 79% of global 23 natural fibers (Xun et al., 2021; Wang et al. 2021), an 

## Methods
Within Google Earth Engine, the xy product was used to identify crop types in 2019 in a small area of interest intersecting Missouri, United States. This area contains cotton as well as other agricultural fields, with the total area of cotton fields staying relatively constant since 2001. A simple trend analysis revealed a decrease by 1.8 km^2 over the xy km^2 area of interest.
Visualization using GIFs
Classification including Sentinel-2 spectral bands, the NDVI and BSI
Classification including furthermore Sentinel-1 VV and VH polarization.

## Results
Training and validation accuracy of the classifier that did not include Sentinel-1 data was slightly better () than that of the classifier that included the microwave data (), although cotton fields exhibited cotton spectral properties different to those of non-cotton fields.
