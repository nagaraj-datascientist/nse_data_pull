# NSE bhav data pull

## Objective:

- Download historical bhav copy data from [NSE site](https://www.nseindia.com/all-reports)

## How to execute:

- provide download folder location in DOWNLOAD_FOLDER (bhav csv file will be downloaded here)

- provide archive folder location in ARCHIVE_FOLDER (bhav csv file will be moved here once it is loaded to database)

```
No need to change anything for the next execution.  
It gets the max date of archive file (loaded to database) as start date and today as end date. 
If there is no archive file then start date as 2000 Jan 3 (20 years data).
```

