<a href="https://githubsfdeploy.herokuapp.com?owner=findocklabs&repo=findock-healthcheck-npsp&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

# FinDock Usage Dashboard

A quick description of what this repo contains:
- Reports and a Dashboard to help monitor usage of FinDock Transactions and Paylinks
- A Report folder where all these Reports are placed
- A Dashboard Folder where the Dashboard is placed
- These reports and dashboards are built to work with FinDock Contracts based on the Transaction model

# Configuration
- This project creates 2 Reports and 1 Dashboard 
- The Dashboard has 4 default filters added for "All", "Last 12 Months", "Last 6 months" and "Last Month" that filters all the Reports by the Effective Date field for the Transaction Report and Created Date field for the Paylinks Report. 
- You can choose to add more filter options as required. 
- The reference line on the usage report is dependent on your Contract. Please update the value by following the steps below
- Open the Dashboard and click on Edit. Click on the Edit on the widget called "Transaction Usage Chart" and update the value in the "Reference Line Value" to the contracted transaction monthly volume.
- If you use Paylinks, click on Edit on the widget called "Paylinks usage chart" and update the value in the "Reference Line Value" to the contract paylink monthly volume. If you do not use Paylinks yet, please feel free to delete the Report and the Chart widget along with the underlying report

## Full list of components

```text
**Reports**
reports/FinDock_Transaction_Usage_Report_KBC.report-meta.xml
reports/FinDock_Paylinks_Usage_Report_OPN.report-meta.xml

**Report Folder**
reports/FinDockUsageReports.reportFolder-meta.xml

**Dashboards**
Dashboards/YIQFPFsjEiUUkPaAgEKiMdZZcGUndY.dashboard-meta.xml

**Dashboard Folder**
Dashboards/FinDockUsage.dashboardFolder-meta.xml
```

## Contributing

When contributing to this repository, please first discuss the change you wish to make via an issue or any other method with FinDock before making a change.

## Support

FinDock Labs is a non-supported group in FinDock that releases applications. Despite the name, assistance for any of these applications is not provided by FinDock Support because they are not officially supported features. For a list of these apps, visit the FinDock Labs account on Github.

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details