/measurements/[INT]
GET
 - INT:   count days

/measurement
POST
 - Data:    JSON (Date/Time/Temp/Hum)

/report
POST
 - Data:    JSON (
    - Auszug letzte Logfile Einträge
    - Freier Speicherplatz
    - Update Log
 )

/reports/[INT]
GET
 - INT: count latest reports

 
sasd