# Snap.Metadata
![GitHub](https://img.shields.io/badge/License-MIT-brightgreen?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/DGP-Studio/Snap.Metadata?label=Issues&style=flat-square)
[![pages-build-deployment](https://github.com/DGP-Studio/Snap.Metadata/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/DGP-Studio/Snap.Metadata/actions/workflows/pages/pages-build-deployment)

# What we are emitting

## Genshin

### Achievement

|Achievement|Type|
|-|-|
|Id|AchievementId|
|Goal|AchievementGoalId|
|Order|uint|
|PreviousId|AchievementId?|
|Title|string?|
|Description|string?|
|FinishReward|IdCount?|
|IsDeleteWatcherAfterFinish|bool?|
|Progress|uint|
|Icon|string?|
|Version|string?|

|IdCount|Type|
|-|-|
|Id|MaterialId|
|Count|uint|

### AchievementGoal

|AchievementGoal|Type|
|-|-|
|Id|AchievementGoalId|
|Order|uint|
|Name|string?|
|FinishReward|IdCount?|
|Icon|string?|

### Avatar
### AvatarCurve
### AvatarPromote
### DisplayItem
### GachaEvent
### Material
### Meta
### Monster
### MonsterCurve
### ProfilePicture
### Reliquary
### ReliquaryAffixWeight
### ReliquaryMainAffix
### ReliquaryMainAffixLevel
### ReliquarySet
### ReliquarySubAffix
### TowerFloor
### TowerLevel
### TowerSchedule
### Weapon
### WeaponCurve
### WeaponPromote

## CheatTable

### AvatarAndWeapon

|AvatarAndWeapon|Type|
|-|-|
|Id|uint|
|Name|string|

### DailyTask

|DailyTask|Type|
|-|-|
|Id|uint|
|CityId|uint|
|PoolId|uint|
|QuestId|uint|
|Type|DailyTaskType|
|Rarity|uint|
|CenterPosition|string|
|Title|string|
|Description|string|
|Target|string|

### GcgDeckCard

|GcgDeckCard|Type|
|-|-|
|Id|uint|
|CardId|uint|
|ItemId|uint|
|Name|string|

### Npc

|Npc|Type|
|-|-|
|Id|uint|
|Name|string|

### Transformer

|Transformer|Type|
|-|-|
|Item|string|
|Value|uint|
|Tag1|MiriacleTag|
|Tag2|MiriacleTag|
|Tag3|MiriacleTag|
|Tag4|MiriacleTag|
|Tag5|MiriacleTag|