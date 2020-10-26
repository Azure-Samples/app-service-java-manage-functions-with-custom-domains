---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Appservice
  platforms: java
---

# Getting Started with Appservice - Manage Function App With Domain Ssl - in Java #


  Azure App Service sample for managing function apps.
   - app service plan, function app
     - Create 2 function apps under the same new app service plan
   - domain
     - Create a domain
   - certificate
     - Upload a self-signed wildcard certificate
     - update both function apps to use the domain and the created wildcard SSL certificate
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-functions-with-custom-domains.git

    cd app-service-java-manage-functions-with-custom-domains

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.