# 🗣 Release Updates

## February 12, 2022

### Webhook support for Salesforce and HubSpot

Business users can build real-time flows with webhook support for Salesforce and HubSpot. These webhooks can track changes in an object such as Account or Opportunity in Salesforce or Lead in HubSpot and can be used to trigger a flow which can update another system and notify a Customer Success Manager or a Sales Representative who is serving that account.

### New Endpoints

With this release we are adding two new endpoints to Flows

* HubSpot
* JIRA

### Auto Data Type Conversion

SnapLogic Flows now leverages AI to suggest data type for all incoming data fields. And with a single click, you can automatically convert data from 'String' to an appropriate data type before pushing it to the target endpoint. You have an option to override these suggestions so that you are always in control.

## December 16, 2021

### Auto data type conversion

When mapping data from a source to a destination in Data Wrangler, you can see data types in the filter dropdown when selecting input data. By leveraging Iris AI, Flows can also automatically convert data types. Users can override the data types as needed.

### Other new Features

* Flows is now an asset type just like a Pipeline
* You can configure Salesforce Account with OAuth Authentication
* You can now change the number of preview records displayed in User Settings by choosing from a pre-defined list of options ranging from 1 to 2000.

## November 13, 2021

### Pipeline Extensions

With Flows, business users can automate business processes without help from IT. There are always complex integration tasks for which they will need IT's help. The Pipeline Extension feature of Flows allows a business user to read from a pipeline and then trigger downstream activities in SnapLogic Flows. This feature also enables a business user to write the output of a Flow to a pipeline so that IT experts can process data in a pipeline or connect to a system such as a database or data warehouse that is under the IT domain.

### New endpoints

With this release, we have added the following endpoints to SnapLogic Flows:&#x20;

* Microsoft Dynamics 365 Sales
* Microsoft Teams
* Microsoft Sharepoint
* ServiceNow
* SnapLogic Read/Write to Pipeline

### Unified Error Handling and more

November release for Flows now provides unified error handling in the 'Information Panel' on the right of the build screen. This consistent handling of messages and simplified errors for business users results in much more efficient troubleshooting. &#x20;

## August 14, 2021

### Launch of SnapLogic Flows

SnapLogic Flows is a user experience built specifically for business users on top of the SnapLogic Intelligent Integration Platform (IIP). SnapLogic Flows allows users to accelerate business outcomes by automating common processes.&#x20;

#### Built for Business Users

Every Flow in SnapLogic Flows has three components Source, Transformation, and Destination. SnapLogic Flows is a no-code user experience that provides following features that help business users automate common tasks without the help from IT.

* Information Panel to get contextual help at every step&#x20;
* Intelligent defaults such as commonly used objects in each endpoints
* Simplified interface to configure accounts and endpoints
* Dedicated 'Data Wrangler' interface for filtering the source data and mapping data from source to destination
* Endpoint introspection of source and destination
* Excel-like functions for data transformations&#x20;
* Data preview of raw, filtered, and mapped data
* Ability to run a Flow on demand or schedule a Flow in advance

#### Governed by IT

SnapLogic Flows is built on the SnapLogic IIP and provides governance and security features to the IT teams for a common user and asset management across Designer and SnapLogic Flows. IT teams can manage users and assets through the SnapLogic Manager and can get details on Flows execution through SnapLogic Dashboard.

#### Supported Endpoints

This first release of SnapLogic Flows focuses on Sales and Marketing endpoints. Following endpoints are available in SnapLogic Flows today: Salesforce, Marketo, Google Sheets, Slack, Box, SnapLogic Local Files, and Email.

{% hint style="info" %}
For more details on this release, read the [release notes here](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/2463662653/February+2022+4.28+Release+Notes)
{% endhint %}
