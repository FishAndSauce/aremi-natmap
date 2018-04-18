### AREMI Changelog

This is a list of changes of the Australian Renewable Energy Mapping Infrastructure (AREMI). To use AREMI to access the dataset layers and features mentioned below please go to:

http://nationalmap.gov.au/renewables/

### Version 2018-04-18
* Updated Transmission Lines, Substations, and Power Stations from using WMS to using ArcGIS MapServer services.
* Update to [TerriaJS 5.7.0](https://github.com/TerriaJS/terriajs/blob/5.7.0/CHANGES.md).

### Version 2018-03-26
* Updated the "Renewable Energy -> Bioenergy -> Victoria" layers from Sustainability Victoria.
* Added the group of layers in "Renewables -> Bioenergy -> New South Wales -> Livestock" from the NSW Department of Primary Industries.
* Added the "Research -> Australia Upper Reservoir Locations - ANU STORES" layer from ANU 100% Renewable Energy team.
* Update to [TerriaJS 5.6.4](https://github.com/TerriaJS/terriajs/blob/5.6.4/CHANGES.md).

### Version 2018-01-30b
### Version 2018-01-30
* Remove layers from the ABS Data Service for which ABS return no data.
* Removed the layer "Renewable Energy -> Hydro -> River Regions" as the data custodian has removed the layer.
* Fixed an issue with the group "Renewable Energy -> Wave -> Australian Wave Energy Atlas -> Wave Model and Context Layers" not displaying.

### Version 2018-01-24
* Update to [TerriaJS 5.5.7](https://github.com/TerriaJS/terriajs/blob/5.5.7/CHANGES.md).
* Updated to all new layers in the "Renewable Energy -> Bioenergy -> Tasmania" group from the Department of State Growth, Tasmania.
* Removing the layer "Renewable Energy -> Bioenergy -> National -> Winery Residues -> Winery Residues by Postcode" as it is no longer available.
* Removing the old, rarely used, and not very informative layers in "Research -> NICTA Geothermal model".

### Version 2017-11-13c
* Update to [TerriaJS 5.5.4](https://github.com/TerriaJS/terriajs/blob/5.5.4/CHANGES.md) to fix IE11 functionality.

### Version 2017-11-13b
* Fix AREMI Vector Tiles server HTTPS URL issue.

### Version 2017-11-13
* Updated the Clean Energy Regulator Small Scale Installation data in the group "Electricity Infrastructure -> Generation -> Small Scale Installations - CER".
* Added the new group of layers in "Renewable Energy -> Bioenergy -> New South Wales -> Waste" from the NSW Forest Science unit, Department of Primary Industries:
    * C&D - Organic Waste (t)
    * C&I - Organic Waste (t)
    * MSW - Organic Waste (t)
    * Total MSW, C&I, C&D - Organic Waste (t)
* Added the new "Renewable Energy -> Bioenergy -> National -> National Piggery Residues" group of layers from the Department of the Premier and Cabinet, South Australia.
* Added more layers to the group "Renewable Energy -> Bioenergy -> National -> Winery Residues" from the Department of the Premier and Cabinet, South Australia:
    * Percent of National Crush by GI Region
    * Wine Processing Facilities - > 20,000 t/pa
* Updating and adding new layers in the "Renewable Energy -> Bioenergy -> Western Australia" from the Department of Primary Industries and Regional Development, Western Australia:
    * Updated:
        * Feedlot Waste Data
    * New:
        * Dairy Effluent
        * Broiler Litter Production
        * Horticulture
            * Hand Harvested Vegetables Residue Estimates
            * Mechanically Harvested Vegetable Residue
            * Olive Residue Estimate
            * Avocado Residue
            * Citrus Fruit Residue
            * Pome Fruit Residue
            * Stone Fruit Residue
* Migrated all the Landgate SLIP based layers in "Electricity Infrastructure -> Transmission -> Western Australia" to use their new services listed in data.wa.gov.au.
* Added the layer "Topography -> Aerial/Satellite Imagery -> Tasmania" from Land Information System Tasmania, Tasmanian Government.
* Added the new Carto Voyager basemap, and removed the basemaps Bing Maps Roads, Natural Earth II, and NASA Black Marble.
* Fixed the "Infrastructure -> Communications -> Broadband" layers which were failing to load.
* Migrate ancillary services to Data61 hosted infrastructure:
    * services.aremi.nationalmap.gov.au -> services.aremi.data61.io
    * gis.aremi.nationalmap.gov.au -> gis.aremi.data61.io
    * static.aremi.nationalmap.gov.au -> static.aremi.data61.io
* Removed the layer "Topograpy -> Elevation -> Land slope in percent" due to problems with the visualisation.
* Update the services from the following data providers to use HTTPS:
    * data.stategrowth.tas.gov.au
    * location.sa.gov.au
    * maps.six.nsw.gov.au
    * services.thelist.tas.gov.au
    * www.environment.gov.au
* Update to [TerriaJS 5.5.0](https://github.com/TerriaJS/terriajs/blob/5.5.0/CHANGES.md).

### Version 2017-09-22
* Added in the [2017 Network Opportunities Constraint maps](https://www.uts.edu.au/research-and-teaching/our-research/institute-sustainable-futures/our-research/energy-and-climate-2) in "Electricity Infrastructure -> Network Opportunities" from the Institute for Sustainable Futures, UTS.
* Added the new "Winery Residues" layers from RenewablesSA in the "Renewable Energy -> Bioenergy -> National" group.
* Update many layers provided by Geoscience Australia to use new NationalMap service URLs:
    * Infrastructure
        * Marine Infrastructure Points
        * Mine Areas
        * Vertical Obstructions
        * Aircraft Facilities
        * Ferry Routes
        * Railways
        * Roads layer
    * Topography
        * Contours
        * Spot Elevations
        * Cultivated Areas
        * Land Cover
        * Native Vegetation
        * Flats, remove Foreshore Flats (merged into Flats)
        * Lakes
        * Reef Areas, remove Reef points
        * Reservoirs
        * Water Course
    * Remove Infrastructure -> Fences
* Update the layer "Boundaries -> Natural Resource Management Regions" to use the up to date service from the Department and Environment and Energy.
* Added 5 new layers in the "Renewable Energy -> Bioenergy -> New South Wales -> Forestry" group from the Department of Primary Industries - New South Wales Government.
* Update to [TerriaJS 5.3.0](https://github.com/TerriaJS/terriajs/blob/5.3.0/CHANGES.md).
* The colours used to display data for the Electricity Infrastructure -> Generation -> NGERS Designated Generation Facilities have been updated to better show the diversity of low values of generation, so large generators don't overpower the signal.

### Version 2017-07-25
* Added the new group of layers in "Renewable Energy -> Bioenergy -> Queensland -> Intensive Livestock" from the Department of Science, Information Technology and Innovation of the State of Queensland Government.
* Added the new group of layers in "Electricity Infrastructure -> Network Opportunities -> New Generator Connection Capacity" from the UTS Institute of Sustainable Futures.
* Update to [TerriaJS 5.2.9](https://github.com/TerriaJS/terriajs/blob/5.2.9/CHANGES.md).
* Updated the source of the "Topography -> Land -> Land Cover" layer.
* Corrected the sources for the layers "Temperature at 5km depth" and "Thermal wells" in the group "Renewable Energy -> Geothermal".
* Many changes to the "Renewable Energy -> Bioenergy -> Victoria" group from Sustainability Victoria, with new heirarchy.
* Many changes to the "Renewable Energy -> Bioenergy -> South Australia" group from RenewablesSA:
  * Added the new layer "Agriculture -> Hay & Silage"
  * Added the new group of layers "Forestry"
  * Added the new group of layers "Urban Waste"
  * Removed the layer "Green Triangle Forestry"
* Updated source data locations for the "Renewable Energy -> Bioenergy -> New South Wales" layers.
* Updated to use the new 2016 CAPAD data for the "Environment -> Collaborative Australian Protected Areas Database (CAPAD)" layer.
* Updated the data for the "Electricity Infrastructure -> Generation -> Small Scale Installations - CER" to the most recent 01/06/2017 release on the Clean Energy Regulator website.
* Combined Landuser layers in "Renewable Energy -> Bioenergy -> South Australia" together with their respective quantity layers.
* Add Augmented Reality mode for iOS and Android devices with a compass and accelerometer.
* Added Clean Energy Regulator Emmisions Baseline Determinations data in "Electricity Infrastructure -> Generation -> Emissions Baseline Determinations - CER"

### Version 2017-06-01
* Added many new layers to the category "Renewable Energy -> Bioenergy -> South Australia" from RenewablesSA.

### Version 2017-05-30b
* Corrected the location of the Native Title Determinations layer.

### Version 2017-05-04
* Remove some bioenergy layers that are no longer required in the "Renewable Energy -> Bioenergy -> South Australia".
* Update to [TerriaJS 5.1.1](https://github.com/TerriaJS/terriajs/blob/5.1.1/CHANGES.md).

### Version 2017-04-24
* Added download links in the feature info of the "Renewable Energy -> Solar -> Solar Satellite DNI & GHI" that allows the user to download the full 25 year timeseries once they have clicked on a point.
* Defaulting to 3D Smooth globe.
* Added many new layers to the category "Renewable Energy -> Bioenergy -> South Australia" from RenewablesSA.
* Fixed some problems with the chart and download links in the feature info of the "Electricity Infrastructure -> Generation -> Current Power Generation - NEM" data.
* Added a new Gas dataset to the "Electricity Infrastructure -> Generation -> Current Power Generation - NEM".
* Added the layer "Renewable Energy -> Bioenergy -> Biogas Facilities" from the National Centre for Engineering in Agriculture, University of Southern Queensland.
* Added the layers in "Renewable Energy -> Bioenergy -> Queensland -> Urban Waste" from the Department of Science, Information Technology and Innovation of the State of Queensland Government.
* Added Feature Area in Hectares to the feature info for the "Boundaries -> Cadastre and Land Tenure -> Cadastral Parcels" data.
* Update to [TerriaJS 5.1.0](https://github.com/TerriaJS/terriajs/blob/5.1.0/CHANGES.md).
* Add more Cropping layers from NSW Department of Industry - Lands to the "Renewable Energy -> Bioenergy -> New South Wales -> Cropping" category.
* Update the CER SGU data available in "Electricity Infrastructure -> Generation -> Small Scale Installations - CER".
* Add data for the 2015-16 NGERS Designated Generation Facilities.

### Version 2017-03-14
* Update to [TerriaJS 4.10.4](https://github.com/TerriaJS/terriajs/blob/4.10.4/CHANGES.md) release to fix a problem affecting the "Electricity Infrastructure -> Generation -> Current Power Generation - NEM" layers.

### Version 2017-02-22
* Added many new layers in the category "Renewable Energy -> Bioenergy -> New South Wales" from NSW Department of Industry - Lands.
* Fixed the link to the related map "NEII viewer" when the image is clicked.
* Add GHI data to "Renewable Energy -> Solar -> Solar Satellite DNI & GHI" (-> click on map to see feature info).
* Add NGERS Designated Generation Facilities data "Renewable Energy -> Generation -> NGERS Designated Generation Facilities (2014-15)" from CER

### Version 2016-12-12
* Add WA Seeweed Wrak layer to "Renewable Energy -> Bioenergy -> Western Australia"
* Add project description to "Renewable Energy -> Bioenergy" for ABBA project
* Update to [TerriaJS 4.7.1](https://github.com/TerriaJS/terriajs/blob/4.7.1/CHANGES.md) release.
* Update to [TerriaJS-server 4.6.2](https://github.com/TerriaJS/terriajs-server/blob/2.6.2/CHANGES.md) release.

### Version 2016-10-21a
* Updated layers for Vic, Qld, Tas, NSW and WA in "Renewable Energy -> Bioenergy" ahead of Bioenergy Australia conference.
* Updated color maps used for "Renewable Energy -> Bioenergy -> Western australia" layers.
* Add Cadastral parcels for NT & ACT ("Boundaries -> Cadastre and Land Tenure -> By state -> ACT/ Northern Territory")
* Several services have been updated to point to Geoscience Australia's new services
    - "Renewable Energy -> Bio Energy -> Waste Management Facilities"
    - "Renewable Energy -> Hydro -> Australian Hydrography"
    - "Renewable Energy -> Wave -> Seabed features"
    - "Renewable Energy -> Hydro -> River Regions"
    - "Topography -> Water -> Australian Hydrography"
    - "Topography -> Water -> River Regions"
    - "Topography -> Land -> Land Cover"
    - "Topography -> Land -> Geology"

### Version 2016-08-12
* Upgrade to use latest [TerriaJS 4.2.0](https://github.com/TerriaJS/terriajs/blob/4.2.0/CHANGES.md) release.
* Migrated all services previously hosted by Data61 to Geoscience Australia hosted infrastructure.
* Migrated the "Renewable Energy -> Wave -> Bathymetry topography" layer to a new service URL on request from Geoscience Australia.
* Added the layers in "Renewable Energy -> Bioenergy -> South Australia -> Existing Waste Stream" from RenewablesSA.
* Improved the default colour ranges for the layers "Annual climatology of daily exposure" and "Monthly climatology of daily exposure" in the "Renewable Energy -> Solar" category.
* Adding a distance measuring tool accessible by clicking the measuring icon on the right side of the map.
* Added the three layers "Renewable Energy -> Geothermal -> NSW - Geothermal Temperature at depth" from the [Geological Survey of NSW, NSW Departmet of Industry](http://www.resourcesandenergy.nsw.gov.au/).
* Added the layer "Renewable Energy -> Wind -> NSW - Wind Speed at 100 metres" with data from [DNV GL](https://www.dnvgl.com/) as sourced by the [Geological Survey of NSW, NSW Departmet of Industry](http://www.resourcesandenergy.nsw.gov.au/).


### Version 2016-07-18b
* Merge in the latest [NationalMap 2016-07-20](https://github.com/NICTA/nationalmap/blob/2016-07-20/CHANGES.md) and use [TerriaJS 4.1.2](https://github.com/TerriaJS/terriajs/blob/4.1.2/CHANGES.md) releases.


### Version 2016-07-18
* The NewUI has been released!
* Added the layers "Harvest Residues Planted Softwoods Monaro" and "Harvest Residues Planted Softwoods Tumut" in the category "Renewable Energy -> Bioenergy -> New South Wales -> Forestry" from the Department of Primary Industries - New South Wales Government.
* Added the layers "Crop Estimates by District", "Green Triangle Forestry", "Intensive Animal Husbandry and Production" and "Green Triangle Region Boundary" in the category "Renewable Energy -> Bioenergy -> South Australia" from RenewablesSA.
* Merged in the latest [NationalMap 2016-07-15](https://github.com/NICTA/nationalmap/blob/2016-07-15/CHANGES.md) and [TerriaJS 4.0.2](https://github.com/TerriaJS/terriajs/blob/4.0.2/CHANGES.md) releases.
* Added the layer "Renewable Energy -> Bioenergy -> Western Australia -> Oil Mallee stems" from the Department of Agriculture and Food, Western Australia.
* Added the layer "Renewable Energy -> Wind -> ACT - Mean Wind Speed at 80 metres" from the ACT Environment and Planning Directorate.
* Added the layers "Renewable Energy -> Bioenergy -> Biomass \*" from the Rural Industries Research and Development Corporation.


### Version 2016-06-22
* Added the layers "Electricity Inf. -> Residential -> Household Energy Consumption 2010-2012" visualised from the Australian Bureau of Statistics "4670.0 - Household Energy Consumption Survey, Australia: Summary of Results, 2012".
* Added a more noticeable popup asking if the user would like to try the NewUI.
* Don't display the year on the timeseries control for the "Renewable Energy -> Solar -> Monthly climatology of daily exposure" layers.
* Added a legend for the layer "Topography -> Water -> Floods -> Queensland -> Brisbane City Council 1974 Flood".
* Changed to show only filename and not the entire URL as the link in the feature info for "Renewable Energy -> Wind -> WAsP LIB files".
* Added more downloadable data formats on the Info pages for the "Renewable Energy -> Wind" layers.


### Version 2016-05-23
* Added the layer "Renewable Energy -> Wind -> WAsP LIB files" from DNV GL.
* Updated "Electricity Inf. -> Generation -> Diesel generators - South Australia" to use data from the Data.SA CKAN server.
* Moved the layers "Renewable Energy -> Bioenergy -> Queensland -> Sugarcane" down to "Renewable Energy -> Bioenergy -> Sugarcane" as they also include NSW data.
* Added a link to the new prototype user interface so that people can try it out.
* Added the layer "Renewable Energy -> Bioenergy -> New South Wales -> Harvest Residues Planted Softwoods Bathurst" from the Department of Primary Industries - New South Wales Government.
* Updated to the latest [NationalMap version 2016-05-13c](https://github.com/NICTA/nationalmap/blob/2016-05-13c/CHANGES.md).
* Renamed "Renewable Energy -> ARENA Funded projects" to ARENA Projects because some projects listed have not received ARENA funding.
* Updated CER SGU data in the category "Electricity Inf. -> Generation -> Small Scale Installations" to be current as of May 2016.
* Added the layer "Renewable Energy -> Bioenergy -> Western Australia -> Cereal straw" from the Department of Agriculture and Food, Western Australia.


### Version 2016-05-11
* Added the layers in the category "Infrastructure -> Liquid Fuel Facilities" from Geoscience Australia.
* Added the layer "Infrastructure -> National Major Desalination Plants" from Geoscience Australia.
* Migrated the layers "Infrastructure -> Damwalls" and "Renewable Energy -> Hydro -> Dam Walls" to the new "National Major Dam Walls" service from Geoscience Australia.
* Added the layer "Renewable Energy -> Wave -> Hillshaded Bathymetry and Topography" from Geoscience Australia.
* Migrated the Roads and Railways layers in the "Infrastructure -> Transport" to a new Geosience Australia service.
* Added the layers in the category "Renewable Energy -> Bioenergy -> Victoria" from Sustainability Victoria.
* Moved the "Boundaries -> Environmental areas" to be its own "Environment" top level category.
* Added the layers in "Renewable Energy -> Bioenergy -> Queensland -> Sugarcane" from the Department of Science, Information Technology and Innovation of the State of Queensland Government.
* Added the layer "Boundaries -> Native Title Determinations" from the National Native Title Tribunal.
* Added the layer "Electricity Inf. -> Generation -> Diesel generators - South Australia" from RenewablesSA.
* Added the layer "Renewable Energy -> ARENA Funded projects" with public data from ARENA about the projects they fund.
* Added the layer "Topography -> Aerial/Satellite Imagery -> New South Wales" from Land and Property Information NSW.
* Added the layers in the category "Boundaries -> Cadastre and Land Tenure -> By State -> Queensland" from the Queensland Government - Department of Natural Resources and Mines.
* Added the layers in the category "Topography -> Water -> Floods -> Queensland" from the Queensland Government.
* Added the layer "Topography -> Aerial/Satellite Imagery -> Queensland" from the Queensland Government - Department of Natural Resources and Mines.
* Added the WPS functions and reference area for the "Renewable Energy -> Wave -> Australian Wave Energy Atlas" group.
* Added an experimental CSV export service for clicked points to the "Renewable Energy -> Solar -> Solar Satellite DNI - 2014" layer.
* Points shown for "Electricity Infrastructure -> Generation -> Current Power Generation - NEM" are now scaled by their value when it makes sense, and columns which don't make sense to choropleth by have been removed as options.


### Version 2016-04-22
* Added a new layer with Typical Meteorological Year data processed from the Bureau of Meteorology One Minute Solar observations. The layer has been added in the category "Renewable Energy -> Solar -> Typical Meteorological Year".
* Updated the service endpoints for the layers "Aspect" and "Land slope in percent" in the category "Topography -> Elevation".
* Updated the feature info template for the CER Small Scale Installation layers in "Electricity Inf. -> Generation -> Small Scale Installations - CER".
* Updated with the latest Clean Energy Regulator Small Scale Installations data for the layers in "Electricity Inf. -> Generation -> Small Scale Installations - CER".
* Correcting layer names for "Electricity Inf. -> Transmission -> Western Australia -> Forecast Remaining Capacity" to match actual forecast years of the data.
* Added feature info templates for:
    - Renewable Energy
        - Wave
            - Bathymetry topography
            - Seabed features
    - Electricity Inf.
        - Transmission
            - Western Australia
                - Distribution Lines
                - Overhead Transmission Lines
                - Substation Connection Capacity
                - Forecast Remaining Capacity layers
* Added a feature info template to the "Electricity Inf. -> Generation -> All Power Stations" layer.
* Added the Geoscience Australia layer "Population -> Buildings".
* Added the CSIRO Australian Wave Atlas group of layers to the "Renewables -> Wave" category.


### Version 2016-03-22
* Merged in the latest [NationalMap 2016-03-15](https://github.com/NICTA/nationalmap/blob/2016-03-15/CHANGES.md) and [TerriaJS jsonTreeview-2016-03-22](https://github.com/TerriaJS/terriajs/blob/jsonTreeview-2016-03-22/CHANGES.md) releases.
* Added the new experimental layer "Renewable Energy -> Solar -> Solar Satellite DNI - 2014" based on Bureau of Meteorology data.
* Added the new layer "Boundaries -> Cadastre and Land Tenure -> Cadastral Parcels" from Geoscience Australia.
* Changed the "Boundaries -> Cadastre and Land Tenure -> Northern Australia" layers into a single "Boundaries -> Cadastre and Land Tenure -> Land Tenure" layer hosted by Geoscience Australia that covers all of Australia.
* Added a check to make sure all catalog items have ids specified on build.
* Fixed missing links to GA ELVIS system in "Topography -> Elevation -> {LiDAR 5m DEM,LiDAR 25m DEM, SRTM 1 sec DEM image}".
* Added feature info templates for:
    - Elec. Inf
        - Generation
            - Live Power Generation layers
            - Small Scale Installations layers
        - Transmission
            - Transmission Lines
    - Renewable Energy
        - Bioenergy
            - Waste Management Fascilities
    - Infrastructure
        - Oil Pipelines
        - Gas Pipelines


#### Version 2016-02-23
* Small improvements to the DNV GL Wind layers.


#### Version 2016-02-22
* Migrated the layer "Boundaries -> Cadastre and Land Tenure -> Northern Australia -> All Land Tenure types" from a WMS to an ArcGIS MapServer service and added an autogenerated legend.
* Added the new "Renewable Energy -> Wind" layers with data produced by [DNV GL](https://www.dnvgl.com/)!
* Migrated layers in "Boundaries -> Protected Areas" from using the soon to be decomissioned services from Geoscience Australia to new services from the Department of Environment.
* Updated "Boundaries -> Defence restricted areas" layers to use new `services.ga.gov.au` server for WMS and legends.
* Updated the look and feel of the legends for "Electriity Inf. -> Generation -> Current Power Generation" layers.
* Added links to GA's ELVIS elevation data download service to "Topography -> Elevation -> {LiDAR 5m DEM,LiDAR 25m DEM, SRTM 1 sec DEM image}"
* Updated the "Electriity Inf. -> Generation -> Small Scale Installations" data to February 2016.
* Added the new layer "Infrastructure -> Major Ports" from Geoscience Australia.
* Updated the "Electricity Inf. -> Transmission -> Transmission Lines/Substations" and "Electricity Inf. -> Generation -> All Power Stations" layers to use the new updated Geoscience Australia services.
* Updated the "Infrastructure -> Gas/Oil Pipelines" layers to use the new updated Geoscience Australia services, and added WFS download URLs.
* Removed the "Benchmarks" and "Horizontal Control Points" from the "Topography -> Elevation" category as these have been decommissioned by the data custodian.
* Added "Contribute Data" link to the sidebar.


#### Version 2016-01-15
* Updated the "Renewable Energy -> Solar -> Solar Station Historical Observations" (also available under the "Weather" category) data and Info description to the latest from `aremi-tmy` version 0.1.1.0.
* Added the new "Topography -> Elevation -> LiDAR 5m DEM" layer from Geoscience Australia.


#### Version 2015-12-22
* Merged in the latest [NationalMap 2015-12-15@835ab11](https://github.com/NICTA/nationalmap/blob/835ab116a60048aadd6fe5e94a186090b124557a/CHANGES.md) and [TerriaJS jsonTreeview-1.0.51](https://github.com/TerriaJS/terriajs/blob/jsonTreeview-1.0.51/CHANGES.md) releases.
* Updated the "Renewables -> Geothermal -> Radiation and Geophysics" layers to the new updated service from Geoscience Australia.
* Added the new "Electricity Inf. -> Transmission -> Distance to Transmission Substations" layer from Geoscience Australia.
* Updated the "Electricity Inf. -> Transmission -> Distance to Transmission Lines" to the new better looking service from Geoscience Australia.
* Added the new "Topography -> Elevation -> LiDAR 25m DEM" from Geoscience Australia.
* Updated the "Topography -> Elevation -> SRTM 1 sec DEM Image" layer to a new version deployed by Geoscience Australia.
* Improved feature info name and layout for layers in the group "Electricity Inf. -> Generation -> Current Power Generation - NEM".
* Added the new layer "Renewable Energy -> Annual climatology of daily exposure - Direct Normal Exposure" from the Bureau of Meteorology.
* Added Zoom To boundaries for the "Electricity Inf. -> Generation" layers in "Current Power Generation - NEM", "Current Solar PV - APVI", and "Small Scale Installations - CER".
* Updated the "Population -> Population Density" layer to use the new Geoscience Australia service for it.
* Corrected the Data Custodian on the "Infrastructure -> Radio Licenses - ACMA" to be the ACMA.
* Added a WFS data URL on the info page for the "Infrastructure -> Radio Licenses - ACMA" layer.
* Added the new Department of Environment layer "Boundaries -> Environmental Areas -> Conservation Management Zones".


#### Version 2015-11-17b
* Fix legends from Landgate not loading.


#### Version 2015-11-17
* Added `ignoreUnknownTileErrors` to all WMS and ArcGIS layers in order to avoid one tile breaking the entire layer.
* Added `clipToRectangle` and specified a `rectangle` with bounds for Australia for the majority of layers where this makes sense.
* Added feature info templates for Topography -> Water -> Water Observations from Space layers to make it easier to understand the data.


#### Version 2015-11-16
* Merged in the latest [NationalMap 2015-11-16b](https://github.com/NICTA/nationalmap/blob/2015-11-16b/CHANGES.md) and [TerriaJS jsonTreeview-1.0.48](https://github.com/TerriaJS/terriajs/blob/jsonTreeview-1.0.48/CHANGES.md) releases.
* Added a number of Department of Environment layers in the Boundaries section.
* Added the Land and Property Information NSW Cadastre service to Boundaries -> Cadastre and Land Tenure.
* Made the version number in the AREMI banner link to the tagged version of the Changelog.
* Created a Boundaries -> Cadastre and Land Tenure subcategory and moved layers into it.
* Put in a simple feature info template for the Electricity Inf. -> Transmission -> Distance to Trans Lines layer to show a sentence with the distance.
* Updated the Electricity Inf. -> Generation -> Small Scale Installations data and layer info pages.
* Added the Google URL Shortener for the Share feature.
* Added the ABS 2011 Census layers to the Population category.
* Adjusted the home view for all layers in the Boundary category.
* Added the ACMA Radio Licenses layer to the Infrastructure -> Communications category.
* Added the Geoscience Australia Northern Australia Land Tenure layers to the Boundaries category.
* Renamed and reorded some entries in the catalog.
* Added the Landgate Western Australia Electricity and Cadastre layer.
* Changed to the Data61 logo.
* Added a development system disclaimer when the app detects that it is not hosted on a nationalmap.gov.au host.
* Replaced the old 'Topography -> Infrastructure -> Gas Pipelines' layer two separate new Geoscience Australia layers - Gas Pipelines and Oil Pipelines.
* Added the layer 'Solar Station Historical Observations' to the 'Renewable Energy -> Solar' and the new 'Weather' categories.
* Reordered, refactored, added Renewable layer to the Electricity -> Generation -> Live NEM category.
* Fixed Legends and info pages, set opacity=100 and ignoreUnknownTileErrors=true for Boundaries -> Defence Restricted Areas layers.
* Refactored DANCE2 info pages, fixing some problems masked by HTML-leniency.


#### Version 2015-09-25
* Added the Institute for Sustainable Futures DANCE modelling project.
* Added the Geoscience Australia hosted Department of Environment Protected Areas services.
* Switched the Tasmanian Cadastre layer to their public Esri MapServer as it has better layer metadata.
* Switch default basemap to Positron (Light) in order to have some extra definition, remove OpenStreetMap simple basemaps from basemap controls.
* Merged in the latest NationalMap [2015-09-17](https://github.com/NICTA/nationalmap/blob/2015-09-17/CHANGES.md) and Terria [1.0.43](https://github.com/TerriaJS/terriajs/blob/1.0.43/CHANGES.md) releases.
* Default to 3D-smooth mode to increase performance, and to avoid current Cesium native feature parallax issues.
* Turn off autoplaying of timeseries data (requires Terria support).
* Generate the AREMI init file using the EJS template engine.
* Moved License links when they were the only thing in Description sections to their own Licensing sections.
* Tasmania Cadastral: Removed duplicated info page Data Description text, fixed order of info blocks.


#### Version 2015-08-26
* Added Geoscience Australia Substations layer, improved metadata for Transmission Lines layer.
* Improved look and feel, legend, of the CER Small Generation Unit data.
* Tweaked the Waste Management Facilities layer further: switched back to WMS, removed info duplicated info we now harvest from the service metadata, adjusted rectangle to match home camera.


#### Version 2015-08-25
* Replaced the Geoscience Australia - Australian Solar Energy Information System (ASEIS) layers with the new Bureau of Meteorology Solar Climatology services.
* Removed missing legend messages from GA and NICTA geothermal raster layers.
* Update APVI layer look and feel now that apvi-webservice has new columns.
* Updated the Waste Management Facilities layer since the WMS version seemed broken with Terria.
* Merged in the latest changes from NationalMap tag 2015-08-18.
* Improved Tasmanian Cadastral Parcels metadata.
* Added Global Disclaimer that is optionally mandatory to accept before continuing.
* Added the Feedback Survey link to the front page.


Changes older than this were not recorded in the changelog.
