# Create a Multi-Region Azure Cosmos DB account for any API Type

This template provides a great deal of flexibility to create an Azure Cosmos DB account with multiple different configurations including:

- **API Type:** Select from any of the supported API types including: SQL, Cassandra, Gremlin, MongoDB, or Table.
- **Consistency Level:** Select from any of the 5 consistency levels.
- **Multi Region:**: Select locations for two replica regions. (Note, this template lists every region in Azure, ensure regions selected are available to your subscription.)
- **Multi-Master:**: Select whether to enable multi-master support.
- **Automatic Failover:**: Select whether to enable automatic failover on the account (Ignored when Multi-Master is enabled).

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmarkjbrown%2Fcosmosdb-create-account-arm-template%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmarkjbrown%2Fcosmosdb-create-account-arm-template%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>