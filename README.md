# KTM Berhad GTFS-R History

This repository provides historical data of the KTM Berhad GTFS-R feed. You can explore the data on the [dataset](https://github.com/malaysiatrec/my-ktmb-gtfs-r-history/tree/dataset) branch.

## Update Frequency

A cron job runs daily at 12 AM UTC+8 to generate the previous day's dataset and push it to this repository's dataset branch.

## Purpose

This repository serves as an archive of the dataset, open to everyone for analyzing train service performance. We offer several API endpoints that utilize this dataset, which you can explore [here](https://documenter.getpostman.com/view/40279048/2sAYBd67bZ).

## Data Error

We experienced a [major service outage](https://webstatus.mtrec.name.my/incident/499884) on 2025-01-22 at 11:45, which caused the GTFS-R dataset to be blank and no data was recorded until 2025-01-22 at 17:45. As a result, the data for this period is not available in the respective CSV files. The GTFS-R dataset is now back in service and is being updated daily as per the usual schedule.

## Credits

1. [GTFS Realtime API Endpoint - data.gov.my](https://developer.data.gov.my/realtime-api/gtfs-realtime)

## Contact

For inquiries, please contact us at [malaysiatrec@gmail.com](mailto:malaysiatrec@gmail.com).
