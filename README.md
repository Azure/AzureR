<p align="center"><a href="https://github.com/Azure/AzureR"><img src="images/logo_bare.png" width=400></a></p>

AzureR is a family of packages for working with [Azure](https://microsoft.com/azure) from R. They are designed to be lightweight yet powerful by working directly with the Azure REST API, without any dependencies on other languages.

The family includes the following members. All the packages are available on [CRAN](https://cloud.r-project.org), and the individual repositories are also mirrored at the [cloudyr project](https://cloudyr.github.io).

| Package | Description |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Status&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
| :-----: | ----------- | :----: |
| [![AzureAuth](images/AzureAuth.png)](https://github.com/Azure/AzureAuth) | **[AzureAuth](https://github.com/Azure/AzureAuth)** provides [Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/index) authentication functionality. Use this package to obtain OAuth 2.0 tokens for any Azure service that uses AAD for authentication. It supports AAD v1.0 and v2.0; authenticating with certificates; and multiple authentication flows, including authorization code, device code, client credentials, on-behalf-of and resource owner grant. | [![CRAN](https://www.r-pkg.org/badges/version/AzureAuth)](https://cran.r-project.org/package=AzureAuth) <br> ![R-CMD-check](https://github.com/Azure/AzureAuth/workflows/R-CMD-check/badge.svg) |
| [![AzureGraph](images/AzureGraph.png)](https://github.com/Azure/AzureGraph) | **[AzureGraph](https://github.com/Azure/AzureGraph)** is an R6-based interface to [Microsoft Graph](https://developer.microsoft.com/graph/), focusing on Azure Active Directory. Its main functionality revolves around registered apps and service principals, with a view to supporting the other packages in the family, but it can also be used to manage other objects in Graph. | [![CRAN](https://www.r-pkg.org/badges/version/AzureGraph)](https://cran.r-project.org/package=AzureGraph) <br> ![R-CMD-check](https://github.com/Azure/AzureGraph/workflows/R-CMD-check/badge.svg) |
| [![AzureRMR](images/AzureRMR.png)](https://github.com/Azure/AzureRMR) | **[AzureRMR](https://github.com/Azure/AzureRMR)** is an R6-based interface to [Azure Resource Manager](https://azure.microsoft.com/features/resource-manager/). It enables working with subscriptions, resource groups, resources and templates: resources can be created, updated and deleted, templates can be deployed and removed, and role-based permissions assigned. Most of the other AzureR packages extend AzureRMR to provide more features specific to a given service. | [![CRAN](https://www.r-pkg.org/badges/version/AzureRMR)](https://cran.r-project.org/package=AzureRMR) <br> ![R-CMD-check](https://github.com/Azure/AzureRMR/workflows/R-CMD-check/badge.svg) |
| [![AzureKeyVault](images/AzureKeyVault.png)](https://github.com/Azure/AzureKeyVault) | **[AzureKeyVault](https://github.com/Azure/AzureKeyVault)** provides a Resource Manager and client interface to [Azure Key Vault](https://azure.microsoft.com/services/key-vault/). It supports all operations with objects stored in Key Vault, such as encryption and decryption, certificate signing, and storage account key management. | [![CRAN](https://www.r-pkg.org/badges/version/AzureKeyVault)](https://cran.r-project.org/package=AzureKeyVault) <br> ![R-CMD-check](https://github.com/Azure/AzureKeyVault/workflows/R-CMD-check/badge.svg) |
| [![AzureStor](images/AzureStor.png)](https://github.com/Azure/AzureStor) | **[AzureStor](https://github.com/Azure/AzureStor)** provides a Resource Manager and client interface to [storage accounts](https://azure.microsoft.com/Services/Storage). The client interface currently supports blob, file and Data Lake Gen2 storage. Features include parallel file transfers, retry on error, and an interface to the AzCopy v10 utility. | [![CRAN](https://www.r-pkg.org/badges/version/AzureStor)](https://cran.r-project.org/package=AzureStor) <br> ![R-CMD-check](https://github.com/Azure/AzureStor/workflows/R-CMD-check/badge.svg) |
| [![AzureContainers](images/AzureContainers.png)](https://github.com/Azure/AzureContainers) | **[AzureContainers](https://github.com/Azure/AzureContainers)** provides a Resource Manager and client interface to containers: [Azure Container Instances](https://azure.microsoft.com/services/container-instances/), [Azure Container Registry](https://azure.microsoft.com/services/container-registry/), and [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/). Build a Docker image and push it to ACR; deploy it to ACI; or create a service on AKS. As a bonus, AzureContainers can talk to any Docker registry or Kubernetes cluster, not just those in Azure. | [![CRAN](https://www.r-pkg.org/badges/version/AzureContainers)](https://cran.r-project.org/package=AzureContainers) <br> ![R-CMD-check](https://github.com/Azure/AzureContainers/workflows/R-CMD-check/badge.svg) |
| [![AzureVM](images/AzureVM.png)](https://github.com/Azure/AzureVM) | **[AzureVM](https://github.com/Azure/AzureVM)** is a package for deploying and interacting with [virtual machines](https://azure.microsoft.com/services/virtual-machines/) and [virtual machine scalesets](https://azure.microsoft.com/services/virtual-machine-scale-sets/). It provides a flexible, powerful interface that lets you customise nearly all aspects of the deployment, including reusing existing resources. A selection of predefined configurations is also included to allow easy deployment of commonly used Linux and Windows images. | [![CRAN](https://www.r-pkg.org/badges/version/AzureVM)](https://cran.r-project.org/package=AzureVM) <br> ![R-CMD-check](https://github.com/Azure/AzureVM/workflows/R-CMD-check/badge.svg) |
| [![AzureKusto](images/AzureKusto.png)](https://github.com/Azure/AzureKusto) | **[AzureKusto](https://github.com/Azure/AzureKusto)** provides a Resource Manager and client interface to [Azure Data Explorer](https://azure.microsoft.com/services/data-explorer), also known as Kusto. Its features include dplyr and DBI interfaces to Kusto, as well as the ability to manage clusters and database principals. | [![CRAN](https://www.r-pkg.org/badges/version/AzureKusto)](https://cran.r-project.org/package=AzureKusto) <br> ![R-CMD-check](https://github.com/Azure/AzureKusto/workflows/R-CMD-check/badge.svg) |
| [![AzureVMmetadata](images/AzureVMmetadata.png)](https://github.com/Azure/AzureVMmetadata) | **[AzureVMmetadata](https://github.com/Azure/AzureVMmetadata)** is a simple interface to the [instance metadata service](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/instance-metadata-service) in an Azure virtual machine. This provides information on the VM's configuration, such as the number of processors, memory, storage, networking, Azure resource details, and so on. | [![CRAN](https://www.r-pkg.org/badges/version/AzureVMmetadata)](https://cran.r-project.org/package=AzureVMmetadata) <br> ![R-CMD-check](https://github.com/Azure/AzureVMmetadata/workflows/R-CMD-check/badge.svg) |
| [![AzureCognitive](images/AzureCognitive.png)](https://github.com/Azure/AzureCognitive) | **[AzureCognitive](https://github.com/Azure/AzureCognitive)** implements basic functionality for communicating with [Azure Cognitive Services](https://azure.microsoft.com/services/cognitive-services/).  Both a Resource Manager interface, extending AzureRMR, and a client interface to the REST APIs are provided. While it can be called by the end-user, it is meant to provide a foundation for other packages that will support specific services, like Computer Vision, LUIS (language understanding), etc. | [![CRAN](https://www.r-pkg.org/badges/version/AzureCognitive)](https://cran.r-project.org/package=AzureCognitive) <br> ![R-CMD-check](https://github.com/Azure/AzureCognitive/workflows/R-CMD-check/badge.svg) |
| [![AzureVision](images/AzureVision.png)](https://github.com/Azure/AzureVision) | **[AzureVision](https://github.com/Azure/AzureVision)** is an interface to [Azure Computer Vision](https://azure.microsoft.com/services/cognitive-services/computer-vision/) and [Azure Custom Vision](https://azure.microsoft.com/services/cognitive-services/custom-vision-service/), building on the low-level functionality provided by the AzureCognitive package. These services let you leverage the cloud to carry out visual recognition tasks using advanced image processing models, without needing powerful hardware of your own. | [![CRAN](https://www.r-pkg.org/badges/version/AzureVision)](https://cran.r-project.org/package=AzureVision) <br> ![R-CMD-check](https://github.com/Azure/AzureVision/workflows/R-CMD-check/badge.svg) |
| [![AzureQstor](images/AzureQstor.png)](https://github.com/Azure/AzureQstor) | **[AzureQstor](https://github.com/Azure/AzureQstor)** is a lightweight, R6-based interface to [Azure Queue Storage](https://azure.microsoft.com/services/storage/queues/), building on the functionality provided by the AzureStor package. | [![CRAN](https://www.r-pkg.org/badges/version/AzureQstor)](https://cran.r-project.org/package=AzureQstor) <br> ![R-CMD-check](https://github.com/Azure/AzureQstor/workflows/R-CMD-check/badge.svg) |
| [![AzureTableStor](images/AzureTableStor.png)](https://github.com/Azure/AzureTableStor) | **[AzureTableStor](https://github.com/Azure/AzureTableStor)** is a lightweight interface to [Azure Table Storage](https://azure.microsoft.com/services/storage/tables/), building on the functionality provided by the AzureStor package. Both tables in storage accounts and in Azure Cosmos DB are supported. | [![CRAN](https://www.r-pkg.org/badges/version/AzureTableStor)](https://cran.r-project.org/package=AzureTableStor) <br> ![R-CMD-check](https://github.com/Azure/AzureTableStor/workflows/R-CMD-check/badge.svg) |
| [![AzureCosmosR](images/AzureCosmosR.png)](https://github.com/Azure/AzureCosmosR) | **[AzureCosmosR](https://github.com/Azure/AzureCosmosR)** is a frontend to the [Azure Cosmos DB](https://azure.microsoft.com/en-us/services/cosmos-db/), NoSQL database service. It provides both a Resource Manager interface extending AzureRMR, and a comprehensive client interface to the core/SQL API. | [![CRAN](https://www.r-pkg.org/badges/version/AzureCosmosR)](https://cran.r-project.org/package=AzureCosmosR) <br> ![R-CMD-check](https://github.com/Azure/AzureCosmosR/workflows/R-CMD-check/badge.svg) |
| [![Microsoft365R](images/Microsoft365R.png)](https://github.com/Azure/Microsoft365R) | **[Microsoft365R](https://github.com/Azure/Microsoft365R)** is an interface to the [Microsoft 365](https://www.microsoft.com/en-us/microsoft-365) (formerly known as Office 365) suite of cloud services, extending the framework supplied by AzureGraph. Currently it allows access to data in [SharePoint Online](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration) and [OneDrive](https://www.microsoft.com/en-us/microsoft-365/onedrive/online-cloud-storage) (both personal OneDrive and OneDrive for Business). Future versions may add support for other Microsoft 365 services. | [![CRAN](https://www.r-pkg.org/badges/version/Microsoft365R)](https://cran.r-project.org/package=Microsoft365R) <br> ![R-CMD-check](https://github.com/Azure/Microsoft365R/workflows/R-CMD-check/badge.svg) |



Currently, AzureR is not intended to support all of Azure; its focus is mainly on the Azure services that are most likely to be relevant to R users.

