# FREDS_Scraping

This is a simple repository for downloading time series data from FRED website.\n
The function get_data_csv(link, date) simply requires the link of the FRED website and the date required as starting date. It allows to use the timeseries as a Pandas Object or directly download it as ".csv" file.\n
As I used the script for a project to control for the expected 10 years inflation and the spread in 10 years Tnotes and TIPS, the script does also calculate those and plot them. This can be taken as an example of how to use the get_data_csv function
