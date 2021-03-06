<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Display Categories are different from &quot;categories&quot; in that these are specifically for visual grouping and display of categories in Vendor UI. The &quot;categories&quot; structure is for validation of the contained items, and can be categorized entirely separately from &quot;Display Categories&quot;, there need be and often will be no meaningful relationship between the two.

## Schema
* **Schema Type:** Definition
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
identifier | string | A string identifier for the display category.
displayProperties | [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition | 

## Example
```javascript
{
    // Type: string
    "identifier": "",
    // Type: [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition
    "displayProperties": {
        // Type: string
        "description": "",
        // Type: string
        "name": "",
        // Type: string
        "icon": "",
        // Type: boolean
        "hasIcon": false
    }
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyDisplayCategoryDefinition.html#schema_Destiny-Definitions-DestinyDisplayCategoryDefinition
