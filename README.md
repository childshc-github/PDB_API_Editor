# PDB_API_Editor
The following code takes a SASA output tsv file (from https://git.sr.ht/~nsg/DexDesign) and appends descriptors using RCSB PDB Data API.


### Installation
The install requirements are:
- python requests
- source code for Requests: HTTP for Humans. The step-by-step instructions for installation can be found here: https://requests.readthedocs.io/en/latest/user/install/#install

### API
- Information about the RCSB PDB Data GraphQL-based API can be found here: https://data.rcsb.org/index.html#data-api
- The Entry Attributes can be found here: https://data.rcsb.org/data-attributes.html

### Usage
- By altering the query_category and query_item, any Entry Attributes can be retrieved and appended to a tsv file.
- Edit the fileloc variable to designate the name and location of the SASA tsv output file
- The program will output an appended tsv file with the request information to ./Descript_API.tsv
