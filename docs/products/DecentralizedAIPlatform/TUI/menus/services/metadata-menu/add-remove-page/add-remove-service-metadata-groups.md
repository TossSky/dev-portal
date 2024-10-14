# Add/Remove Service Metadata Groups

Add or remove a group from a service's metadata

![Add/Remove Service Metadata Groups Page](/assets/images/products/AIMarketplace/TUI/Screenshot2024-08-17at6.02.40PM.png)

```bash
# Format of the commands in the SNET CLI

snet service metadata-add-group [-h] [--metadata-file METADATA_FILE]
                                GROUP_NAME

snet service metadata-remove-group [-h] [--metadata-file METADATA_FILE]
                                   GROUP_NAME
```

User Flow:

* Adding group
  * Input the group name, and local metadata file path
  * Click the "Add group" button
* Removing group
  * Input the group name, and local metadata file path
  * Click the "Remove group" button