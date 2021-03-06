### NPSP API Examples

Examples of how to use the [NPSP](https://github.com/SalesforceFoundation/Cumulus) API. 

This API is made of a number of global classes that are intentionally  exposed externally as integration points to managed and unmanaged code.

To deploy the unmanaged code to your org, you just need to have Ant and the Salesforce Ant Migration Tool installed (just drop the jar in the ant lib directory). Then checkout the [CumulusCI](https://github.com/SalesforceFoundation/CumulusCI) project at the same level as this project, and run this command from inside NPSP-API-Examples:

    ant deployCI

Once the code is deployed, you may have to give the necessary profiles access to the NPSP Examples APP. Then switch to the app, and you will see in the API Examples tab links to navigate to the other 4 tabs. These tabs display examples of how the NPSP API is being used. Look at the controllers behind the pages for details.

Clink this link to install the unmanaged version: [https://login.salesforce.com/packaging/installPackage.apexp?p0=04ti0000000gPbd](https://login.salesforce.com/packaging/installPackage.apexp?p0=04ti0000000gPbd)

Click this link to install the managed beta version: [https://login.salesforce.com/packaging/installPackage.apexp?p0=04ti0000000gQ2q](https://login.salesforce.com/packaging/installPackage.apexp?p0=04ti0000000gQ2q)

Click this link to install the managed production version: [https://login.salesforce.com/packaging/installPackage.apexp?p0=04ti0000000gQ30](https://login.salesforce.com/packaging/installPackage.apexp?p0=04ti0000000gQ30)