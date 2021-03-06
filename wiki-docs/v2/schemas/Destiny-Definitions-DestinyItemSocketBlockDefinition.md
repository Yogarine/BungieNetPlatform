<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
If defined, the item has at least one socket.

## Schema
* **Schema Type:** Definition
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
detail | string | This was supposed to be a string that would give per-item details about sockets. In practice, it turns out that all this ever has is the localized word &quot;details&quot;. ... that's lame, but perhaps it will become something cool in the future.
socketEntries | [[DestinyItemSocketEntryDefinition|Destiny-Definitions-DestinyItemSocketEntryDefinition]]:Definition[] | Each socket on an item is defined here. Check inside for more info.
socketCategories | [[DestinyItemSocketCategoryDefinition|Destiny-Definitions-DestinyItemSocketCategoryDefinition]]:Definition[] | A convenience property, that refers to the sockets in the &quot;sockets&quot; property, pre-grouped by category and ordered in the manner that they should be grouped in the UI. You could form this yourself with the existing data, but why would you want to? Enjoy life man.

## Example
```javascript
{
    // Type: string
    "detail": "",
    // Type: [[DestinyItemSocketEntryDefinition|Destiny-Definitions-DestinyItemSocketEntryDefinition]]:Definition[]
    "socketEntries": [
       // Type: [[DestinyItemSocketEntryDefinition|Destiny-Definitions-DestinyItemSocketEntryDefinition]]:Definition
        {
            // Type: [[Destiny.Definitions.Sockets.DestinySocketTypeDefinition|Destiny-Definitions-Sockets-DestinySocketTypeDefinition]]:integer:uint32
            "socketTypeHash": 0,
            // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
            "singleInitialItemHash": 0,
            // Type: [[DestinyItemSocketEntryPlugItemDefinition|Destiny-Definitions-DestinyItemSocketEntryPlugItemDefinition]]:Definition[]
            "reusablePlugItems": [
               // Type: [[DestinyItemSocketEntryPlugItemDefinition|Destiny-Definitions-DestinyItemSocketEntryPlugItemDefinition]]:Definition
                {
                    // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
                    "plugItemHash": 0
                }
            ]
        }
    ],
    // Type: [[DestinyItemSocketCategoryDefinition|Destiny-Definitions-DestinyItemSocketCategoryDefinition]]:Definition[]
    "socketCategories": [
       // Type: [[DestinyItemSocketCategoryDefinition|Destiny-Definitions-DestinyItemSocketCategoryDefinition]]:Definition
        {
            // Type: [[Destiny.Definitions.Sockets.DestinySocketCategoryDefinition|Destiny-Definitions-Sockets-DestinySocketCategoryDefinition]]:integer:uint32
            "socketCategoryHash": 0,
            // Type: integer:int32[]
            "socketIndexes": [
               // Type: integer:int32
                0
            ]
        }
    ]
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyItemSocketBlockDefinition.html#schema_Destiny-Definitions-DestinyItemSocketBlockDefinition
