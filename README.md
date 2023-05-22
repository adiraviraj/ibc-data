# ibc-data
Repo for sharing tools/resources to access data related to IBC.

- [**IBC data dashboards**](https://www.notion.so/cosmos-is-expansive/Product-Wiki-0bfdb596940147cc8e9cda3bd8bdbd81?pvs=4#78906fbb905444a0b16c109bb23b1d79)

- **failed_packets.py:** Queries the selected chain for failed IBC packets based on the specified time period. Uses the [IOBScan API](https://docs.apis.iobscan.io/#tag/IOBScanTx/paths/~1ibc~1transfers~1statistics~1%7Bchain%7D~1flow/get). The script writes the data to .csv file called 'ibc-go_versions.csv'.

- **ibc-go_chain-versions.py:** Web scraping file that returns the ibc-go version of 47 IBC-enabled chains.

- **ica-enabled-chains.py:** Web scraping file that provides info on which chains have enabled the ICA-controller or host functionality. Returns data for 38 IBC-enabled chains.

