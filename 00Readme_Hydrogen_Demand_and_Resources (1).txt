00Readme_Hydrogen_Demand_and_Resources.txt

October 2020

Consumption Potential for Hydrogen

By Mark F. Ruth, Paige Jadun, Nicholas Gilroy, Elizabeth Connelly, Richard Boardman, A.J. Simon, Amgad Elgowainy, and Jarett Zuboy

OBTAINING DATA
The data files can be obtained from the National Renewable Energy Laboratory via the Internet from OpenEI.


GENERAL
The data are provided in two file formats: GeoJSON for encoding geographic data structures and comma-separated values (CSV) files along with a metadata document, which provides a complete description of the data schema and units of measure.


DATA FILES
The GeoJSON contains a polygon feature class, the CSV file is the same data without a coordinate reference system (CRS).

Hydrogen_Demand_and_Resources: A dataset that provides estimates on hydrogen’s serviceable consumption potential for possible hydrogen applications and the technical potential for producing hydrogen from various resources.


ATTRIBUTES
Attribute Label: gid
Attribute Definition: Unique identifier.

Attribute Label: name
Attribute Definition: Name of the U.S. county where the feature is located.

Attribute Label: state_name
Attribute Definition: Name of the U.S. state where the feature is located.

Attribute Label: fips
Attribute Definition: Federal Information Processing Series (FIPS). US states are identified by a 2-digit number, while US counties are identified by a 3-digit number.
Note: The Microsoft (MS) Excel program drops the leading zero on FIPS codes. 

Attribute Label: a_sqkm
Attribute Definition: U.S. county area in square kilometers.

Attribute Label: mms_refineries_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from refineries in kilograms of hydrogen.

Attribute Label: mms_metals_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from metals in kilograms of hydrogen.

Attribute Label: mms_ammonia_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from ammonia in kilograms of hydrogen.

Attribute Label: mms_biofuels_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from biofuels in kilograms of hydrogen.

Attribute Label: mms_synfuels_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from synthetic fuels in kilograms of hydrogen.

Attribute Label: mms_ngas_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from natural gas in kilograms of hydrogen.

Attribute Label: mms_ld_fcev_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from light duty fuel cell electric vehicles (FCEVs) in kilograms of hydrogen.

Attribute Label: mms_mhd_fcev_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from medium and heavy duty fuel cell electric vehicles (FCEVs) in kilograms of hydrogen.

Attribute Label: mms_season_enrgy_strg_kg
Attribute Definition: Hydrogen’s serviceable consumption potential from seasonal energy storage in kilograms of hydrogen.

Attribute Label: tot_kg	
Attribute Definition: Total hydrogen serviceable consumption potential from all sources in kilograms of hydrogen.

Attribute Label: solar_metric_tons	
Attribute Definition: Technical potential for producing hydrogen from solar photovoltaics (PV), converted into metric tons.

Attribute Label: wind_metric_tons
Attribute Definition: Technical potential for producing hydrogen from wind, converted into metric tons.

Attribute Label: solar_kg
Attribute Definition: Technical potential for producing hydrogen from solar photovoltaics (PV), converted into kilograms.

Attribute Label: wind_kg
Attribute Definition: Technical potential for producing hydrogen from wind, converted into kilograms.

Attribute Label: total_resource_kg
Attribute Definition: Total technical potential for producing hydrogen from solar photovoltaics (PV) and wind, converted into kilograms.

Attribute Label: total_resource_minus_total_demand_kg
Attribute Definition: Total technical potential for producing hydrogen from solar photovoltaics (PV) and wind, converted into kilograms, minus total hydrogen serviceable consumption potential from all sources in kilograms of hydrogen.


Data_Dictionary: A summary of tables and fields listed in alphabetic order. The dictionary includes a short description of each field 
and the unit of measure where appropriate. The data dictionary is intended to be used with the metadata.


DISCLAIMERS
Any user who modifies the data is obligated to describe the types of modifications they perform. Data have been checked to ensure accuracy. If any errors are detected, please notify the originating office. 

The National Renewable Energy Laboratory strongly recommends that careful attention be paid to the metadata file associated with these data. Acknowledgment of the National Renewable Energy Laboratory would be appreciated in products derived from these data. User specifically agrees not to misrepresent the data, nor to imply that changes made were approved or endorsed by the National Renewable Energy Laboratory.


SUGGESTED CITATION
Ruth, Mark, Paige Jadun, Nicholas Gilroy, Elizabeth Connelly, Richard Boardman, A.J. Simon, Amgad Elgowainy, and Jarett Zuboy. 2020. The Technical and Economic Potential of the H2@Scale Concept within the United States. Golden, CO: National Renewable Energy Laboratory. NREL/TP- 6A20-77610. https://www.nrel.gov/docs/fy21osti/77610.pdf.
