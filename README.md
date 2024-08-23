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
- **UCDP_Maps**: This code is designed to fetch, process, and visualize data from the Uppsala Conflict Data Program (UCDP). Specifically, it works with either the Georeferenced Event Dataset (GED) or the Candidate Events Dataset. The output is a map that shows the intensity of organized violence, measured by the number of fatalities, at the PRIO-GRID level. If you choose to visualize a GED version, you can also specify which years to cover.

## Documentation
For more detailed information on using the API, please refer to the official [UCDP API documentation](https://ucdp.uu.se/apidocs/).



