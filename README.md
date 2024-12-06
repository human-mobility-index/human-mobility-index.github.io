# Human Mobility Index


The distance among villages, cities, regions, countries, and other socio-economic and political entities has long been considered an important aspect in the explanation of their comparative political and economic development. While theories abound about how geographical isolation and distances affect trade, warfare, epidemics, and colonization among many others, there is a lack of systematic historical data on communication and transportation costs, as well as geographical distances. This has led many scholars to use great circle distances as a proxy. This measure, however, is rather crude as it does not capture the large variation in the geographical and technological conditions underlying similar great circle distances in different periods.

In [Özak (2018, ](http://rdcu.be/I4YI)[2010)](http://omerozak.com/pdf/Ozak_voyage.pdf) I rectify this deficiency by introducing a novel set of measures of historical mobility: "The Human Mobility Index (HMI)" that estimates the potential minimum travel time across the globe (measured in hours) accounting for human biological constraints, as well as geographical and technological factors that determined travel time before the widespread use of steam power. In particular, the HMI indices provide a distinct measure of human mobility potential in different eras:

1. Human Mobility Index (HMI): Mobility on land without seafaring technology. Shows mobility potential on land before the widespread use of steam power.
2. Human Mobility Index with Seafaring: HMI expanded to allow mobility on a select set of seas for which historical data was available. Shows potential mobility on land and seas before the introduction of ocean-faring ships.
3. Human Mobility Index with Ocean: HMI expanded to allow mobility on all seas based on [CLIWOC]() (interpolated). Shows potential mobility on land and seas after the introduction of ocean-faring ships, but before the widespread use of steamships.

Based on these cost surfaces, researchers can find the minimum travel times between locations or construct more sophisticated statistics based on these. For example, [Ashraf, Galor and Özak (2010)](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1542-4774.2010.tb00511.x) construct measures of pre-historic geographical isolation to study the effect of isolation on development. Similarly, [Özak (2010)](http://omerozak.com/pdf/Ozak_voyage.pdf), [Depetris-Chauvin and Özak (2016, ](http://ssrn.com/abstract=2827328)[2020)](https://rdcu.be/b52Li) and  [Michalopoulus and Özak (2019)]() construct potential trade and information flow networks among countries, ethnic groups, cities, and artificial geographical units, to study the origins of the division of labor, and the effect of technological change on isolation and development. Likewise, [Depetris-Chauvin and Özak (2019)](https://ssrn.com/abstract=4405281) use these measures to construct artificial states based on Voronoi partitions.

This strategy overcomes the potential mismeasurement of distances generated by using geodesic distances [(Özak 2010)](http://omerozak.com/pdf/Ozak_voyage.pdf), for a period when travel time was the most important determinant of transportation costs. Additionally, it removes the potential concern that travel time to the frontier reflects a country's stage of development, mitigating further possible endogeneity concerns. The research validates these measures by (i) analyzing their association with actual historical travel time; (ii) examining their explanatory power for the location of historical trade routes in the Old World; and (iii) analyzing their association with genetic and cultural distances.

## Download GeoTiff Files [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14285746.svg)](https://doi.org/10.5281/zenodo.14285746)

The HMI data is available as GeoTiff files, which can be processed in any GIS software (e.g. [QGIS](https://qgis.org/), [ArcGIS](https://www.arcgis.com/) or [GeoRasters](https://github.com/ozak/georasters)). The files show data at the 1km x 1km and have a cylindrical equal-area projection to ensure correct computations. 

* [HMI](https://zenodo.org/records/14285746/files/HMI.tif?download=1)
* [HMISea](https://zenodo.org/records/14285746/files/HMISea.tif?download=1)
* [HMIOcean (Coming Soon)]()

To speed up computations, it may be useful to use coarser rasters (especially for global projects). The following files present the data at the 10km x 10km with a cylindrical equal-area projection:
* [HMI10](https://zenodo.org/records/14285746/files/HMI10.tif?download=1)
* [HMISea10](https://zenodo.org/records/14285746/files/HMISea10.tif?download=1)

You can also download [all files simultaneously here](https://zenodo.org/api/records/14285746/files-archive).

## Python Package

You can use the [`hmi`](https://pypi.org/project/hmi/0.1/) Python package to compute distances and perform other analyses using the Human Mobility Index measures. See the [GitHub repo](https://github.com/human-mobility-index/hmi) for more information and examples.

## Citation

If you use the data, please cite:

[Özak, Ömer. "Distance to the pre-industrial technological frontier and economic development." Journal of Economic Growth 23.2 (2018): 175-221.](http://rdcu.be/I4YI)

[Özak, Ömer. "The voyage of homo-economicus: Some economic measures of distance." Department of Economics, Brown University (2010).](http://omerozak.com/pdf/Ozak_voyage.pdf)

# Issues

Find a bug? Report it via GitHub issues by providing

- a link to download the smallest possible raster and vector dataset necessary to reproduce the error
- python code or command to reproduce the error
- information on your environment: versions of Python, GDAL, and Numpy and system memory

# Copyright

This data is provided under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) License](https://creativecommons.org/licenses/by-sa/4.0/). ![](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)

# More Information

Coming Soon

[<img src="https://github.com/ozak/Caloric-Suitability-Index/raw/master/pics/SMUlogowWordmarkRB.jpg" width="200">](http://omerozak.com)
