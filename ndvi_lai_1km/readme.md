### Copernicus NDVI & LAI 1km Data Process

With these notebooks, You can download NDVI and LAI 1 km data from Copernicus Global Land Service . Also,You can crete new annual base max,min or mean data with "ndvi_mean_calculatin" notebook. When you use 'mean_calculation' notebook, you should be careful at "layer_name" variable. According your data( NDVI or LAI ), you should change this value. 

##### NDVI 

The Normalized Difference Vegetation Index (NDVI) is an indicator of the greenness of the biomes. 
Even though it is not a physical property of the vegetation cover, its very simple formulation NDVI = (REF_nir – REF_red)/(REF_nir + REF_red)
where REF_nir and REF_red are the spectral reflectances measured in the near infrared and red wavebands respectively, makes it widely used for ecosystems monitoring.

##### Leaf Area Index(LAI)

The Leaf Area Index is defined as half the total area of green elements of the canopy per unit horizontal ground area. The satellite-derived value corresponds to the total green LAI of all the canopy layers, including the understory which may represent a very significant contribution, particularly for forests. Practically, the LAI quantifies the thickness of the vegetation cover.

LAI is recognized as an Essential Climate Variable (ECV) by the Global Climate Observing System (GCOS)



ndvi main page: https://land.copernicus.eu/global/products/ndvi
ndvi product page: https://land.copernicus.vgt.vito.be/PDF/datapool/Vegetation/Indicators/NDVI_1km_V2

lai main page: https://land.copernicus.eu/global/products/lai
lai prodcut page: https://land.copernicus.vgt.vito.be/PDF/datapool/Vegetation/Properties/LAI_1km_V2






