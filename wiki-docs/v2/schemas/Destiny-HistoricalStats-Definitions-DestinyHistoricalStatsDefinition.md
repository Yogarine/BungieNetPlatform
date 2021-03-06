<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info

## Schema
* **Schema Type:** Manifest Definition
* **Type:** object
* **Mobile Manifest:** HistoricalStats

## Properties
Name | Type | Description
---- | ---- | -----------
statId | string | Unique programmer friendly ID for this stat
group | [[DestinyStatsGroupType|Destiny-HistoricalStats-Definitions-DestinyStatsGroupType]]:Enum | Statistic group
periodTypes | [[PeriodType|Destiny-HistoricalStats-Definitions-PeriodType]]:Enum[] | Time periods the statistic covers
modes | [[DestinyActivityModeType|Destiny-HistoricalStats-Definitions-DestinyActivityModeType]]:Enum[] | Game modes where this statistic can be reported.
category | [[DestinyStatsCategoryType|Destiny-HistoricalStats-Definitions-DestinyStatsCategoryType]]:Enum | Category for the stat.
statName | string | Display name
statNameAbbr | string | Display name abbreviated
statDescription | string | Description of a stat if applicable.
unitType | [[UnitType|Destiny-HistoricalStats-Definitions-UnitType]]:Enum | Unit, if any, for the statistic
iconImage | string | Optional URI to an icon for the statistic
mergeMethod | integer:int32:nullable | Optional icon for the statistic
unitLabel | string | Localized Unit Name for the stat.
weight | integer:int32 | Weight assigned to this stat indicating its relative impressiveness.
medalTierHash | integer:uint32:nullable | The tier associated with this medal - be it implicitly or explicitly.

## Example
```javascript
{
    // Type: string
    "statId": "",
    // Type: [[DestinyStatsGroupType|Destiny-HistoricalStats-Definitions-DestinyStatsGroupType]]:Enum
    "group": {},
    // Type: [[PeriodType|Destiny-HistoricalStats-Definitions-PeriodType]]:Enum[]
    "periodTypes": [
       // Type: [[PeriodType|Destiny-HistoricalStats-Definitions-PeriodType]]:Enum
        0
    ],
    // Type: [[DestinyActivityModeType|Destiny-HistoricalStats-Definitions-DestinyActivityModeType]]:Enum[]
    "modes": [
       // Type: [[DestinyActivityModeType|Destiny-HistoricalStats-Definitions-DestinyActivityModeType]]:Enum
        0
    ],
    // Type: [[DestinyStatsCategoryType|Destiny-HistoricalStats-Definitions-DestinyStatsCategoryType]]:Enum
    "category": {},
    // Type: string
    "statName": "",
    // Type: string
    "statNameAbbr": "",
    // Type: string
    "statDescription": "",
    // Type: [[UnitType|Destiny-HistoricalStats-Definitions-UnitType]]:Enum
    "unitType": {},
    // Type: string
    "iconImage": "",
    // Type: integer:int32:nullable
    "mergeMethod": 0,
    // Type: string
    "unitLabel": "",
    // Type: integer:int32
    "weight": 0,
    // Type: integer:uint32:nullable
    "medalTierHash": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-HistoricalStats-Definitions-DestinyHistoricalStatsDefinition.html#schema_Destiny-HistoricalStats-Definitions-DestinyHistoricalStatsDefinition
