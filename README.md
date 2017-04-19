# HW4
Exceptions and unit tests
In HW1, you eownload3e the data from https://data.seattle.gov/resource/4xy5-26gy.csv and put it in a data directory. 
This homework asks you to extend these functions and create tests for them. Due Thursday, November 3rd 6am.

Create the function remove_data that deletes cached data, i.e. the zip file and the various csv files if any. (The idea is to save space by deleting files that aren't being used.) (1 pt)
Modify download_if_needed so that it reports an error if the URL does not exist or the server is not responding. (Hint: Try downloading the file using urllib3 instead of wget.) (1 pt)
Create a separate test file that tests download_if_needed, plot_daily_rides, and remove_data. Note that for download_if_needed there are two cases to test for (data are present and data are not present). (3 pt)
