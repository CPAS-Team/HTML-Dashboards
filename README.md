# Activities & Violations Dashboard

Static HTML dashboard for the CPAS team. The page loads the anonymized Excel workbook from the same directory and renders monthly KPIs, category breakdowns, and trend charts in the browser.

## Files used by the website

- `index.html` — dashboard UI and data processing
- `Violation_Activity_Data_Anonymized.xlsx` — dashboard data source
- `graph-config.js` — optional Microsoft Graph configuration; disabled while no client ID is configured

## Local preview

Serve this directory with a local web server and open `index.html`. Opening the HTML directly also supports manually selecting the workbook.
