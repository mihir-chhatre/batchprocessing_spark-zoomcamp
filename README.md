#### First run below commands to get the raw data for green & yellow taxi (2020,2021)
./download_data.sh yellow 2020
./download_data.sh yellow 2021
./download_data.sh green 2020
./download_data.sh green 20201

#### Convert the raw CSV files into Parquet files
csv_to_parquet

