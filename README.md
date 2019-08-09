---
page_type: sample
languages: java
products: azure
services: Compute
platforms: java
author: yaohaizh
---

## Getting Started with Compute - Convert Virtual Machine To Managed Disks - in Java ##


  Azure Compute sample for managing virtual machines -
    - Create a virtual machine with un-managed OS and data disks
    - Deallocate the virtual machine
    - Migrate the virtual machine to use managed disk.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/managed-disk-java-convert-existing-virtual-machines-to-use-managed-disks.git

    cd managed-disk-java-convert-existing-virtual-machines-to-use-managed-disks

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.