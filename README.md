# Azure PaaS Domain Names for Private Endpoints
I am trying to maintain a list of domain names used by Azure Services so it is easier to onboard Private Endpoints at scale. Please help me do this by submitting a Pull Request when you find a new one.

| Private DNS Zone                        | Service                     |
|-----------------------------------------|-----------------------------|
| privatelink.azurecr.io                  | Container Registry    |
| privatelink.azurewebsites.net           | App Service                 |
| privatelink.blob.core.windows.net       | Storage (Blob)        |
| privatelink.database.windows.net        | Database (SQL)                   |
| privatelink.documents.azure.com         | Database (CosmosDB)                    |
| privatelink.file.core.windows.net       | Storage (File)        |
| privatelink.mariadb.database.azure.com  | Database (MariaDB)    |
| privatelink.mysql.database.azure.com    | Database (MariaDB)    |
| privatelink.postgres.database.azure.com | Database (PostgreSQL) |
| privatelink.queue.core.windows.net      | Storage (Queue)       |
| privatelink.redis.cache.windows.net     | Redis Cache           |
| privatelink.servicebus.windows.net      | Service Bus                 |
| privatelink.sql.azuresynapse.net        | Synapse (SQL)         |
| privatelink.table.core.windows.net      | Storage (Table)       |
| privatelink.vault.azure.net             | Key Vault             |
| privatelink.<region>.azmk8s.io        | Kubernetes Service (Example: privatelink.westeurope.azmk8s.io)    |
