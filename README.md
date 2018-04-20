# SunDAT-ParallelWorks Web Service API
Example code for accessing the SunDAT-ParallelWorks cloud computing web service

## API Key
API Key can be accessed from your ParallelWorks Account at:
https://go.parallel.works/u/settings/#key

Replace APIKEY in runCloud.py with your API Key

## Workflows
"sundat_runner_v1" - for single site design optimization

"sundat_runner_v1_multi_kmz" - for multiple site prospecting and design optimization

## Sample Inputs
`test.kmz` - KMZ file that includes one or more closed polygons (representing SunDAT regions)

`test.json` - SunDAT JSON script file

## Usage
To run "sundat_runner_v1":
`python sundat_ws.py`

To run "sundat_runner_v1_multi_kmz":
`python sundat_ws_multi_kmz.py`

## Additional Resources
Parallel Works API Documentation can be found here:
https://go.parallel.works/docs/api.html

For more information about SunDAT, please visit:
https://sundat.ftcsolar.com
