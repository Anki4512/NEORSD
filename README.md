Stormwater Billing Support: QA-QC & IA Data Validation
Project Overview

This project was developed to support the Regional Stormwater Management Program by identifying billing discrepancies between central records and physical ground conditions. Using QGIS, I analyzed impervious area (IA) datasets to ensure high-accuracy spatial data for departmental decision-making.

The Problem

Municipal billing systems often rely on historical County Parcel Auditor data which may not reflect recent construction or land changes. Inaccurate data leads to revenue loss or unfair billing for residents.

Technical Workflow

Data Digitization: Performed high-accuracy digitizing of impervious surfaces (roofs, driveways, patios) from high-resolution satellite imagery.

Data Research: Collected and integrated official "Recorded IA" from Auditor sites into the Property_Parcels layer.

Spatial Analysis:

Executed a Join Attributes by Location (Summary) to calculate the total square footage of all IA features within each parcel boundary.

Developed a calculated field (Billing_Error) using the formula:

"Auditor_IA"−"GIS_Area_sum"
QA-QC Reporting: Created a visual exhibit using graduated symbology to highlight under-billed (Red) and over-billed (Green) properties.

Final Visual Exhibit

Key Skills Demonstrated

Administrative Support: Maintaining infrastructure and asset data integrity.

Cartography: Developing professional maps with legends, scale bars, and north arrows.

QA-QC: Identifying discrepancies between field-verified data and central records.

### Final Project Map
[(Stormwater_Billing_Report.jpg)](https://github.com/Anki4512/NEORSD/blob/main/Stormwater_Billing_Report.png)
