# Add/Remove Service Metadata Assets

Add assets to metadata, valid asset types are \[hero\_image,images]. Or remove ALL assets of a given type valid asset types are \[hero\_image,images]

![Add/Remove Service Metadata Assets Page](/assets/images/products/AIMarketplace/TUI/Screenshot2024-08-17at6.03.18PM.png)

```bash
# Format of the commands in the SNET CLI

snet service metadata-add-assets [-h] [--metadata-file METADATA_FILE]
                                 asset_file_path asset_type
                                 
snet service metadata-remove-assets [-h] [--metadata-file METADATA_FILE]
                                    asset_type
```

User Flow:

* Adding asset
  * Input the media url, and local metadata file path
  * Click the "Add asset" button
* Removing all assets of type
  * Input the local metadata file path, and type of assets you want to delete
  * Click the "Remove all assets" button