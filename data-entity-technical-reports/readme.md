# Run the data entity reports

These are the report scripts.

Script | Outputs
---|---
AggregateDataEntitiesReport.ps1 | AggregateDataEntities.json 
AggregateMeasuresReport.ps1 | AggregateMeasures.json
DataEntityFieldReport.ps1 | DataEntityFields.json 
DataEntityReport.ps1 | DataEntities.json 
KPIReport.ps1 | KPIs.json 
LicenseCode-ConfigKeyReport.ps1 | LicenseCodes.json<br>ConfigKeys.json<br>ConfigKeyGroups.json<br>MenuItems.json 
SSRSReport.ps1 | SSRSReports.json 
TablesReport.ps1 | Tables.json<br>This report takes awhile to run, but it produces output as it runs. 
WorkflowTypesReport.ps1 | WorkflowTypes.json 

## Helper functions

The report scripts use functions from these files:

+ GetDataEntitiesWithSources.ps1
+ MetadataProvider.ps1

Because the scripts include the function files, you need to run the reports from the folder with the .ps1 files.

## metadataPath

You might need to update the **metadataPath** parameter to your local packages folder.

## Running the script

You might see this message when you run the reports: 

```Plaintext
Run only scripts that you trust. While scripts from the internet can be useful, this script can potentially harm your computer. 
If you trust this script, use the Unblock-File cmdlet to allow the script to without this warning message. Do want to run <filename> ? 
```

Click **Run once** to run the report.

## Contributing

This project welcomes contributions and suggestions. For more information, see the [readme file](../README.md).
