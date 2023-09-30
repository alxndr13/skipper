# Keyvault
> This example is meant to quickly provision an Azure KeyVault used for testing the KeyVault secret driver

It will create an `apply.sh` and a `destroy.sh` script which create/destroy a resource group and a key vault.
Additionally, a `create_key.sh` is created to quickly create new keys within the keyvault.

- **Subscription:** `{{ .Inventory.azure.common.subscription_id }}`
- **Resource Group:** `{{ .Inventory.keyvault.resource_group }}`
- **KeyVault:** `{{ .Inventory.keyvault.name }}`
- **Location:** `{{ .Inventory.keyvault.location }}`
