**4 May 2021 Notice**: The MODIS instrument aboard the Terra satellite experienced a Printed Wire Assembly (PWA) failure on 5 October 2020. This has resulted in a reduction in the overall Terra daytime coverage and many of the MODIS/Terra imagery layers have a slightly jagged appearance at the poles. This issue will affect land daytime MODIS/Terra products that primarily rely on the Reflective Solar Bands (RSB) (i.e. visible bands) indefinitely. [Learn more about the issue](https://landweb.modaps.eosdis.nasa.gov/cgi-bin/QA_WWW/displayCase.cgi?esdt=MOD&caseNum=PM_MOD_20280&caseLocation=cases_data&type=C6).

---

False Color: Red = Band 3, Green = Band 6, Blue = Band 7

This combination is used to map snow and ice. Snow and ice are very reflective in the visible part of the spectrum (Band 3), and very absorbent in Bands 6 and 7 (short-wave infrared, or SWIR). This band combination is good for distinguishing liquid water from frozen water, for example, clouds over snow, ice cloud versus water cloud; or floods from dense vegetation. This band combination is only available for MODIS (Terra) because 70% of the band 6 sensors on the MODIS instrument on the Aqua satellite failed shortly after launch.

The MODIS Corrected Reflectance imagery is available only as near real-time imagery. The imagery can be visualized in Worldview and the Global Imagery Browse Services (GIBS. The sensor resolution is 500 m and 250 m (Bands 1 and 2 have a sensor resolution of 250 m, Bands 3 – 7 have a sensor resolution of 500 m, and Bands 8 - 36 are 1 km. Band 1 is used to sharpen Band 3, 4, 6, and 7), imagery resolution is 250 m, and the temporal resolution is daily.

#### Snow and Ice
Since the only visible light used in these images (Band 3) is assigned to red, snow and ice appear bright red. The more ice, the stronger the absorption in the SWIR bands, and the more red the color. Thick ice and snow appear vivid red (or red-orange), while small ice crystals in high-level clouds will appear reddish-orange or peach.

#### Vegetation
Vegetation will appear green in this band combination, as vegetation is absorbent in Bands 3 and 7, but reflective in Band 6. Bare soil and deserts will appear bright cyan in the image since it much more reflective in Band 6 and 7 than Band 3.

#### Water
Liquid water on the ground will appear very dark since it absorbs in the red and the SWIR, but small liquid water drops in clouds scatter light equally in both the visible and the SWIR, and will therefore appear white. Sediments in water appear dark red.

### MODIS Corrected Reflectance vs. MODIS Surface Reflectance

The MODIS Corrected Reflectance algorithm utilizes MODIS Level 1B data (the calibrated, geolocated radiances). It is not a standard, science quality product. The purpose of this algorithm is to provide natural-looking images by removing gross atmospheric effects, such as Rayleigh scattering, from MODIS visible bands 1-7. The algorithm was developed by the original MODIS Rapid Response team to address the needs of the fire monitoring community who want to see smoke. Corrected Reflectance shows smoke more clearly than the standard Surface Reflectance product. In contrast, the MODIS Land Surface Reflectance product (MOD09) is a more complete atmospheric correction algorithm that includes aerosol correction, and is designed to derive land surface properties. In clear atmospheric conditions the Corrected Reflectance product is very similar to the MOD09 product, but they depart from each other in presence of aerosols. If you wish to perform a complete atmospheric correction, please do not use the Corrected Reflectance algorithm. An additional difference is that the Land Surface Reflectance product is only tuned for calculating the reflectance over land surfaces.

NOTE: We are reprocessing the entire MODIS Land imagery archive to collection 6.1 but currently the imagery is a mix of collection 6 and collection 6.1. Most of the imagery from mid-May 2021 onwards is collection 6.1 and older imagery is collection 6.

References: MOD02QKM [doi:10.5067/MODIS/MOD02QKM.061](https://doi.org/10.5067/MODIS/MOD02QKM.061); MOD02HKM [doi:10.5067/MODIS/MOD02HKM.061](https://doi.org/10.5067/MODIS/MOD02HKM.061); MOD021KM [doi:10.5067/MODIS/MOD021KM.061](https://doi.org/10.5067/MODIS/MOD021KM.061); [NASA Earthdata - Creating Reprojected True Color MODIS Images: A Tutorial](https://earthdata.nasa.gov/files/MODIS_True_Color.pdf); [NASA Earthdata - LANCE FAQ](https://earthdata.nasa.gov/faq/lance-faq#ed-CRvsSR)
