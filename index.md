# NAVBI Documentation

## Installation of BC-Connector
Please first install the NAVBI BC Connector from AppSource.

### Prerequisites
Your Office 365 user should be allowed to install Apps in Business Central.
### Steps
* Please navigate to  [Microsoft AppSource here](https://appsource.microsoft.com/en-us/product/dynamics-365-business-central/pubid.navidainformationssysteme1611067488644%7Caid.nbi_bc_pb_connector%7Cpappid.b987d68d-ab70-4b03-9ff2-157a337d8e55?tab=overview "AppSource")
* Click on "Get it now"
* Please select your environment (Sandbox/Prod etc.) when prompted. The connector will install in your selected environment.
  
## Installation of Power BI Apps
### Get App from AppSource
The installation of the Power BI Apps can either start from AppSource or from Power BI Apps area. From the Power BI Apps area select "Get Apps" and search for NAVBI. Select the required NAVBI App and click "Get Now". The App will be installed in your Power BI Tenant. 

Click on "Connect with your data" to connect with your data. 

### Set Parameters to connect with your Business Central
After clicking "Connect with your data" a window will appear where you can set the following parameters:
* Environment: name of the environment that should be used in your report
* Your Company: Name of the company. If multiple companies should be used in your reporting, combine them with \| (e.g. Company 1\|Company 2). If all companies should be combined in your report, type in "*"
* Posting date year offset: this number is used to reduce the number of years that should be loaded from the past
* Add the license key for your report that was provided by navida. No license key is required if you are testing in a Sandbox environment
* Item attributes: List those item attributes that you want to use in your reporting (optional)

### Change Parameters after installation
If e.g. another company should be included in your reporting, it might be necessary to change the parameters.
* Navigate to the workspace (e.g. NAVBI Sales) and click the three dots next to the semantic model - choose seetings
* Expand the "Parameters" section and change the parameters here. Click Apply (übernehmen)

## Update of Power BI Apps

## Change of Power BI App Parameters (e.g. new company name)

## Sharing Apps with users
Your App only needs to be installed once. It can be used by different users if access is granted to them.
To provide access to users:
* navigate to the App Workspace (e.g. named NAVBI Sales) from the list of workspaces
* click Update App (App aktualisieren)
* switch to the section Permissions (Berechtigungen)
* add users or groups by selecting "Certain users and groups" (Bestimmte Benutzer oder Gruppen); check the option "Automatically install this App" (Hiermit wird die App automatisch installiert)
* click on the Update App Button (App aktualisieren)
* for the Sales App (VK-App) additionally users need to get access to the Row Level Security Groups of the model. To do so select "Security" (Sicherheit) from the Semantic Model overview (three dots - security)
* for group all add users that should have access to all data; if certain users should only be able to see data according to their Salesperson assignment, add them to the group User as Salesperson (Document) or User as Salesperson (Customer); click "Save"

## Change Refresh frequency of App
If you app should be updated more frequently or at other times, you can change this in the settings of the semantic model.
* Navigate to the workspace (e.g. NAVBI Sales)
* Click the three dots while hovering over the name of the semantic model - select Settings
* Expand the section "Refresh" (Aktualisieren"). Change or add times when the model should be refreshed automatically.

## Manually refresh App
