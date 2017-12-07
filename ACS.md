American Community Survey 2015 microdata file is `csv_pus.csv` at 

https://www2.census.gov/programs-surveys/acs/data/pums/2015/5-Year/

The four csv files were read into MonetDB with `MonetDBLite::monetdb.read.csv()`, with the `best.effort=TRUE` and `lower.case.names=TRUE` options
