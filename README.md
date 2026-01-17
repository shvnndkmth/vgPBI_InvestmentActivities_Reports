# vgPBI_InvestmentActivities_Reports
Vanguard Portfolio tracker of investment activities using Power BI Desktop tool. The Power BI report allows to see the investment accounts summary and acitivies for personal review and research. 
The data source for the Power BI report leverages the dowload option available on actitivies on the Vanguard portfolio. 

Step-by-step guide on how to download transaction for your trades from Vanguard.

Log in to your Vanguard account via the url https://investor.vanguard.com/

Go to the Activity tab.

Click on Download Center on the top right corner.

Under Step 1 chose a spreadsheet-compatible CSV file.

Under Step 2 Choose a date range for your transactions.
	
		Custom will allow to download specific date range.	
		You can download for max last 18 months of transactions.

Step 3 choose the account(s) to download.

Click on the "Download" button. 

It will download a file on your local PC with a name OfxDownload.csv

The file has two different sets of records, one with Summary of Symbols and the second on details of transactions. 


------------------------------------------------

This Power BI report is loaded with sample data and does not represent any real transactions. 

To load the downloaded data from your account in the Power BI report perform the steps below: 

Ensure you on the Home Tab of the Power BI ribbon. 

Click on the Transform data drop down and Select Data source setting

It will open the Data source settings dialog box

Click on the Change Source.. 

Click on the Browse and find the folder where the OfxDownload.csv is saved 

Select the file and click Open  

Click OK to close the dialog box

Click Close

Click on the Refresh button on the Home ribbon. 

When the refresh is completed, the new data will reflect in Summary and Details pages.
