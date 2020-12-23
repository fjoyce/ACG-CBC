# ACG-Santa Rosa CBC Shiny app

Shiny app for Santa Rosa Christmas Bird Count in Area Conservación Guanacaste: https://fhjoyce.shinyapps.io/ACG-CBC-Santa-Rosa/

Adapted from Sharleen W's Shiny app for Hamilton, Ontario: https://sharleenw.rbind.io/2019/03/24/hamilton-cbc-part-3/

# data

"HistoricalResultsByCount [CRSR-2011-2020].csv" is the raw csv download (taxonomic sort) from https://netapp.audubon.org/cbcobservation/historical/resultsbycount.aspx# for count code CRSR.

Start year: 111 (2010)
and
End year: 120 (2019)

Even though the filename says 2011-2020

ACG-CBC-cleaning.Rmd takes CRSR-2010-2018_cleaned.csv and outputs CRSR-CBC-cleaned.csv

# root
CRSR-CBC-cleaned.csv is the data file used by the app.

app.R is the code for the Shiny app.
