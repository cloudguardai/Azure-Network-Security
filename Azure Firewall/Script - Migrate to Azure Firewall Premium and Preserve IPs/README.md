# Migrate to Azure Firewall Premium in Secured vWAN hub

This script is part of a step-by-step process to migrate Azure firewall from standard SKU to Premium SKU in Secured vWAN hub while preserving the Public IP addresses during the migration process.  

A Secured virtual hub uses an associated Firewall (Azure Firewall, third-party security as a service (SecaaS) provider, or both.) and routing policies for governance and protection. This blog looks at the steps to successfully migrate Azure Firewall in your secure virtual hub while preserving the Public IPs already assigned to the Azure Firewall during migration. A schedule down-time should be planned for this migration.  


Follow the tutorial in our [TechCommunity Blogpost](https://techcommunity.microsoft.com/t5/azure-network-security-blog/migrate-to-azure-firewall-premium-in-secured-vwan-hub-with/ba-p/2922140) for more information on how this script works and the pre-requisites
&nbsp;


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

