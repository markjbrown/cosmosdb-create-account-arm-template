# Create a Multi-Region Azure Cosmos DB account for any API Type

This template will create an Azure Cosmos DB account and provides multiple different configurations including:

- **API Type:** Select from any of the supported API types including: SQL, Cassandra, Gremlin, MongoDB, or Table.
- **Consistency Level:** Select from one of the 5 consistency levels: Strong, Bounded Staleness, Session, Consistent Prefix, Eventual.
- **Multi-Region:** Select locations for primary and secondary regions. (Note, this template lists every region in Azure, ensure regions selected are available to your subscription.)
- **Multi-Master:** Select whether to enable multi-master support. Primary and Secondary regions, fully writable.
- **Automatic Failover:** Select whether to enable automatic failover on the account (Ignored when Multi-Master is enabled).

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmarkjbrown%2Fcosmosdb-create-account-arm-template%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmarkjbrown%2Fcosmosdb-create-account-arm-template%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Issues with this ARM template can be filed here: [github.com/markjbrown/cosmosdb-create-account-arm-template](https://github.com/markjbrown/cosmosdb-create-account-arm-template)