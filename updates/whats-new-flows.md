# 👀 Release Updates

## March 24, 2022

### New Release Updates Page

The page you're on right now was born today! That's right, starting on March 24th you no longer have to be surprised to see all the new features we've added, you only have to go to one place. Here! A notification on the profile icon in the header will indicate updates to this page.  Now, go get back into your workflow.&#x20;

### New Endpoints

* You can now target Jira and send some love (or data) it's way.

### Enhancements

* Immediately know who to blame if you're Flow stops flowing, introducing the “Updated By” column to the project tab! This shows the last user to edit the Flow. No hiding now, Steve!

{% hint style="info" %}
For more details on this release, read the [release notes here](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/2493054977/March+2022+Release+Notes)
{% endhint %}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

## February 12, 2022

### Webhook support for Salesforce and HubSpot

Business users can build event-driven flows with webhook support for Salesforce and HubSpot. These webhooks can track changes in an object such as Account or Opportunity in Salesforce or Lead in HubSpot and can be used to trigger a flow that can update another system and notify a Customer Success Manager or a Sales Representative who is serving that account.

### New Endpoints

With this release, we are adding two new endpoints to Flows

* HubSpot as a source and target
* JIRA as a source to pull data from

### Auto Data Type Conversion

Stay in your flow! SnapLogic Flows now suggests data types for all incoming data fields to make it even easier for you to get your data moving. With a single click, you can automatically convert data from 'String' to an appropriate data type before pushing it to the target endpoint. Don't worry though, you still have an option to override our suggestions.



{% hint style="info" %}
For more details on this release, read the [release notes here](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/2463662653/February+2022+4.28+Release+Notes)
{% endhint %}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



## December 16, 2021

### Auto data type conversion

When mapping data from a source to a destination in Data Wrangler, you can see data types in the filter dropdown when selecting input data. By leveraging Iris AI, Flows can also automatically convert data types. Users can override the data types as needed.

### Other new Features

* Flows is now an asset type just like a Pipeline
* You can configure Salesforce Account with OAuth Authentication
* You can now change the number of preview records displayed in User Settings by choosing from a pre-defined list of options ranging from 1 to 2000.

{% hint style="info" %}
For more details on this release, read the [release notes here](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/2433744901/December+2021+Release+Notes)
{% endhint %}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

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

{% hint style="info" %}
For more details on this release, read the [release notes here](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/2413298470/November+2021+4.27+Release+Notes)
{% endhint %}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

## August 14, 2021

### Launch of SnapLogic Flows

SnapLogic Flows is an application built specifically for business users on top of the core SnapLogic Intelligent Integration Platform (IIP). SnapLogic Flows allows users to accelerate business outcomes by automating common processes.&#x20;

#### Built for You! The Business Users

Every Flow in SnapLogic Flows has three components Source, Transformation, and Destination. SnapLogic Flows is a no-code user experience that provides the following features that help business users automate common tasks without help from IT.

* Information Panel to guide you every step of the way!
* Intelligent defaults such as commonly used objects in each endpoint.
* Configure accounts and endpoints in a simple interface.
* We know data can get a little wild, so we added a 'Data Wrangler' for filtering and mapping data from the source. Once it's tame, we'll get it to that destination for you.
* A nice visual of your flow from source to destination.
* For all the spreadsheet lovers out there, we added Excel-like functions for data transformations.
* See a preview of raw, filtered, and mapped data.
* Either run a Flow on-demand, or schedule it the choice is yours!

#### Governed by IT

SnapLogic Flows is built on the SnapLogic IIP and provides governance and security features to the IT teams for a common user and asset management across Designer and SnapLogic Flows. IT teams can manage users and assets through the SnapLogic Manager and can get details on Flows execution through SnapLogic Dashboard.

#### Supported Endpoints

This first release of SnapLogic Flows focuses on Sales and Marketing endpoints. Following endpoints are available in SnapLogic Flows today: Salesforce, Marketo, Google Sheets, Slack, Box, SnapLogic Local Files, and Email.

{% hint style="info" %}
For more details on this release, read the [release notes here](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/2289532940/August+2021+4.26+Release+Notes)
{% endhint %}
