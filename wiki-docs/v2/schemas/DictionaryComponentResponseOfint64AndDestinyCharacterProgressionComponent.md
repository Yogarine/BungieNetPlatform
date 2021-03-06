<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info

## Schema
* **Schema Type:** Generic Class
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
data | Dictionary&lt;integer:int64,[[DestinyCharacterProgressionComponent|Destiny-Entities-Characters-DestinyCharacterProgressionComponent]]&gt; | 
privacy | [[ComponentPrivacySetting|Components-ComponentPrivacySetting]]:Enum | 

## Example
```javascript
{
    // Type: Dictionary&lt;integer:int64,[[DestinyCharacterProgressionComponent|Destiny-Entities-Characters-DestinyCharacterProgressionComponent]]&gt;
    "data": {
        "0": {
            // Type: Dictionary&lt;[[Destiny.Definitions.DestinyProgressionDefinition|Destiny-Definitions-DestinyProgressionDefinition]]:integer:uint32,[[DestinyProgression|Destiny-DestinyProgression]]&gt;
            "progressions": {
                "0": {
                    // Type: [[Destiny.Definitions.DestinyProgressionDefinition|Destiny-Definitions-DestinyProgressionDefinition]]:integer:uint32
                    "progressionHash": 0,
                    // Type: integer:int32
                    "dailyProgress": 0,
                    // Type: integer:int32
                    "dailyLimit": 0,
                    // Type: integer:int32
                    "weeklyProgress": 0,
                    // Type: integer:int32
                    "weeklyLimit": 0,
                    // Type: integer:int32
                    "currentProgress": 0,
                    // Type: integer:int32
                    "level": 0,
                    // Type: integer:int32
                    "levelCap": 0,
                    // Type: integer:int32
                    "stepIndex": 0,
                    // Type: integer:int32
                    "progressToNextLevel": 0,
                    // Type: integer:int32
                    "nextLevelAt": 0
                }
            },
            // Type: Dictionary&lt;[[Destiny.Definitions.DestinyFactionDefinition|Destiny-Definitions-DestinyFactionDefinition]]:integer:uint32,[[DestinyFactionProgression|Destiny-Progression-DestinyFactionProgression]]&gt;
            "factions": {
                "0": {
                    // Type: [[Destiny.Definitions.DestinyFactionDefinition|Destiny-Definitions-DestinyFactionDefinition]]:integer:uint32
                    "factionHash": 0,
                    // Type: integer:int32
                    "factionVendorIndex": 0,
                    // Type: [[Destiny.Definitions.DestinyProgressionDefinition|Destiny-Definitions-DestinyProgressionDefinition]]:integer:uint32
                    "progressionHash": 0,
                    // Type: integer:int32
                    "dailyProgress": 0,
                    // Type: integer:int32
                    "dailyLimit": 0,
                    // Type: integer:int32
                    "weeklyProgress": 0,
                    // Type: integer:int32
                    "weeklyLimit": 0,
                    // Type: integer:int32
                    "currentProgress": 0,
                    // Type: integer:int32
                    "level": 0,
                    // Type: integer:int32
                    "levelCap": 0,
                    // Type: integer:int32
                    "stepIndex": 0,
                    // Type: integer:int32
                    "progressToNextLevel": 0,
                    // Type: integer:int32
                    "nextLevelAt": 0
                }
            },
            // Type: Dictionary&lt;[[Destiny.Definitions.Milestones.DestinyMilestoneDefinition|Destiny-Definitions-Milestones-DestinyMilestoneDefinition]]:integer:uint32,[[DestinyMilestone|Destiny-Milestones-DestinyMilestone]]&gt;
            "milestones": {
                "0": {
                    // Type: [[Destiny.Definitions.Milestones.DestinyMilestoneDefinition|Destiny-Definitions-Milestones-DestinyMilestoneDefinition]]:integer:uint32
                    "milestoneHash": 0,
                    // Type: [[DestinyMilestoneQuest|Destiny-Milestones-DestinyMilestoneQuest]][]
                    "availableQuests": [
                       // Type: [[DestinyMilestoneQuest|Destiny-Milestones-DestinyMilestoneQuest]]
                        {
                            // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
                            "questItemHash": 0,
                            // Type: [[DestinyQuestStatus|Destiny-Quests-DestinyQuestStatus]]
                            "status": {},
                            // Type: [[DestinyMilestoneActivity|Destiny-Milestones-DestinyMilestoneActivity]]
                            "activity": {},
                            // Type: [[DestinyChallengeStatus|Destiny-Challenges-DestinyChallengeStatus]][]
                            "challenges": [
                               // Type: [[DestinyChallengeStatus|Destiny-Challenges-DestinyChallengeStatus]]
                                {
                                    // Type: [[DestinyObjectiveProgress|Destiny-Quests-DestinyObjectiveProgress]]
                                    "objective": {}
                                }
                            ]
                        }
                    ],
                    // Type: Dictionary&lt;string,number:float&gt;
                    "values": {
                        "{string}": 0
                    },
                    // Type: [[Destiny.Definitions.DestinyVendorDefinition|Destiny-Definitions-DestinyVendorDefinition]]:integer:uint32[]
                    "vendorHashes": [
                       // Type: integer:uint32
                        0
                    ],
                    // Type: [[DestinyMilestoneVendor|Destiny-Milestones-DestinyMilestoneVendor]][]
                    "vendors": [
                       // Type: [[DestinyMilestoneVendor|Destiny-Milestones-DestinyMilestoneVendor]]
                        {
                            // Type: [[Destiny.Definitions.DestinyVendorDefinition|Destiny-Definitions-DestinyVendorDefinition]]:integer:uint32
                            "vendorHash": 0,
                            // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32:nullable
                            "previewItemHash": 0
                        }
                    ],
                    // Type: [[DestinyMilestoneRewardCategory|Destiny-Milestones-DestinyMilestoneRewardCategory]][]
                    "rewards": [
                       // Type: [[DestinyMilestoneRewardCategory|Destiny-Milestones-DestinyMilestoneRewardCategory]]
                        {
                            // Type: integer:uint32
                            "rewardCategoryHash": 0,
                            // Type: [[DestinyMilestoneRewardEntry|Destiny-Milestones-DestinyMilestoneRewardEntry]][]
                            "entries": [
                               // Type: [[DestinyMilestoneRewardEntry|Destiny-Milestones-DestinyMilestoneRewardEntry]]
                                {
                                    // Type: integer:uint32
                                    "rewardEntryHash": 0,
                                    // Type: boolean
                                    "earned": false,
                                    // Type: boolean
                                    "redeemed": false
                                }
                            ]
                        }
                    ],
                    // Type: string:date-time:nullable
                    "startDate": "",
                    // Type: string:date-time:nullable
                    "endDate": ""
                }
            },
            // Type: [[DestinyQuestStatus|Destiny-Quests-DestinyQuestStatus]][]
            "quests": [
               // Type: [[DestinyQuestStatus|Destiny-Quests-DestinyQuestStatus]]
                {
                    // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
                    "questHash": 0,
                    // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
                    "stepHash": 0,
                    // Type: [[DestinyObjectiveProgress|Destiny-Quests-DestinyObjectiveProgress]][]
                    "stepObjectives": [
                       // Type: [[DestinyObjectiveProgress|Destiny-Quests-DestinyObjectiveProgress]]
                        {
                            // Type: [[Destiny.Definitions.DestinyObjectiveDefinition|Destiny-Definitions-DestinyObjectiveDefinition]]:integer:uint32
                            "objectiveHash": 0,
                            // Type: [[Destiny.Definitions.DestinyDestinationDefinition|Destiny-Definitions-DestinyDestinationDefinition]]:integer:uint32:nullable
                            "destinationHash": 0,
                            // Type: [[Destiny.Definitions.DestinyActivityDefinition|Destiny-Definitions-DestinyActivityDefinition]]:integer:uint32:nullable
                            "activityHash": 0,
                            // Type: integer:int32:nullable
                            "progress": 0,
                            // Type: boolean
                            "complete": false
                        }
                    ],
                    // Type: boolean
                    "tracked": false,
                    // Type: integer:int64
                    "itemInstanceId": 0,
                    // Type: boolean
                    "completed": false,
                    // Type: boolean
                    "redeemed": false,
                    // Type: boolean
                    "started": false,
                    // Type: integer:uint32:nullable
                    "vendorHash": 0
                }
            ],
            // Type: Dictionary&lt;[[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32,[[DestinyObjectiveProgress|Destiny-Quests-DestinyObjectiveProgress]][]&gt;
            "uninstancedItemObjectives": {
                "0": [
                   // Type: [[DestinyObjectiveProgress|Destiny-Quests-DestinyObjectiveProgress]]
                    {
                        // Type: [[Destiny.Definitions.DestinyObjectiveDefinition|Destiny-Definitions-DestinyObjectiveDefinition]]:integer:uint32
                        "objectiveHash": 0,
                        // Type: [[Destiny.Definitions.DestinyDestinationDefinition|Destiny-Definitions-DestinyDestinationDefinition]]:integer:uint32:nullable
                        "destinationHash": 0,
                        // Type: [[Destiny.Definitions.DestinyActivityDefinition|Destiny-Definitions-DestinyActivityDefinition]]:integer:uint32:nullable
                        "activityHash": 0,
                        // Type: integer:int32:nullable
                        "progress": 0,
                        // Type: boolean
                        "complete": false
                    }
                ]
            }
        }
    },
    // Type: [[ComponentPrivacySetting|Components-ComponentPrivacySetting]]:Enum
    "privacy": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_DictionaryComponentResponseOfint64AndDestinyCharacterProgressionComponent.html#schema_DictionaryComponentResponseOfint64AndDestinyCharacterProgressionComponent
