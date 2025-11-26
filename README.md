# TASK-6
6. Scheduled Cleanup Job (Timer Trigger +  Azure SQL + Storage) 

## What it does
Runs daily at 02:00 UTC
Finds Orders older than 30 days in Azure SQL
Saves them to Azure Blob Storage as a .ndjson file
Deletes those records from SQL after saving
Logs how many records were archived
