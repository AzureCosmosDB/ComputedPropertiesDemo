# Computed Properties in Azure Cosmos DB for NoSQL
This contains Python code samples for using Computed Properties in Azure Cosmos DB for NoSQL.

Computed properties in Azure Cosmos DB have values that are derived from existing item properties, but the properties aren't persisted in items themselves. Computed properties are scoped to a single item and can be referenced in queries as if they were persisted properties.

Computed properties make it easier to write complex query logic once and reference it many times. You can add a single index on these properties or use them as part of a composite index for increased performance.

To learn more about Computed Properties, you can:
- Visit the [Azure documentation](https://learn.microsoft.com/azure/cosmos-db/nosql/query/computed-properties?tabs=dotnet)
- Reach out to: cosmoscomputedprops@microsoft.com with any questions.
