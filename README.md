# Basic recipes in Python for UCDP API
This repository contains a set of basic Python scripts to access and process data from the Uppsala Conflict Data Program (UCDP) API. The API allows you to interface directly with UCDP's systems to obtain, process, and subset UCDP data dynamically without the need to manually download data.

The main maintainer of the API is [Stina Högbladh](mailto:stina.hogbladh@pcr.uu.se). For questions about recipes and recipe requests, send an e-mail to [Mert Can Yılmaz](mailto:mertcan.yilmaz@pcr.uu.se).

## Why API? 
- Easily access, process and filter the UCDP datasets.
- Receive data in JSON format.
- Reduce the burden of data management and manual data versioning.
- Utilize built-in versioning to ensure consistency of data across time.

## Available Jupyter notebooks
- **UCDP_API2Dataframe**: This code sends a GET request to the UCDP API to retrieve data from a UCDP dataset. It extracts the data from the JSON response and converts it to a Pandas dataframe. Finally, it saves the complete dataframe to a CSV file and prints it to the console.
- **UCDP_MonthlyCandidateMap**: This code fetches the PRIO-Grids shapefile and reads it into a GeoDataFrame. Then it fetches UCDP Candidate data from the UCDP API and stores the fetched data in a Pandas dataFrame. The fetched data is then filtered and grouped by PRIO-Grids. The code merges the UCDP Candidate data with the PRIO-Grids data and uses the merged data to plot a choropleth map of organized violence at the PRIO-GRID level. The map also shows the natural logarithm of the number of fatalities caused by organized violence. Finally, the code saves the map as a PDF file.

## Documentation
For more detailed information on using the API, please refer to the official [UCDP API documentation](https://ucdp.uu.se/apidocs/).



