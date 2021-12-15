---
title: adventure_map_poi
description: 
published: true
date: 2021-11-14T19:41:35.060Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/adventure_journal_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'adventure_journal_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/adventure_map_poi_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'adventure_map_poi_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [Title](#title) | text |  |  | YES | NULL |  |  |
| [Description](#description) | text |  |  | YES | NULL |  |  |
| [WorldPositionX](#worldpositionx) | float |  |  | NO | 0 |  |  |
| [WorldPositionY](#worldpositiony) | float |  |  | NO | 0 |  |  |
| [Type](#type) | tinyint(4) | signed |  | NO | 0 |  |  |
| [PlayerConditionID](#playerconditionid) | int(10) | unsigned |  | NO | 0 |  |  |
| [QuestID](#questid) | int(10) | unsigned |  | NO | 0 |  |  |
| [LfgDungeonID](#lfgdungeonid) | int(10) | unsigned |  | NO | 0 |  |  |
| [RewardItemID](#rewarditemid) | int(11) | signed |  | NO | 0 |  |  |
| [UiTextureAtlasMemberID](#uitextureatlasmemberid) | int(10) | unsigned |  | NO | 0 |  |  |
| [UiTextureKitID](#uitexturekitid) | int(10) | unsigned |  | NO | 0 |  |  |
| [MapID](#mapid) | int(11) | signed |  | NO | 0 |  |  |
| [AreaTableID](#areatableid) | int(10) | unsigned |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### Title
*- no description -*
&nbsp;

### Description
*- no description -*
&nbsp;

### WorldPositionX
*- no description -*
&nbsp;

### WorldPositionY
*- no description -*
&nbsp;

### Type
*- no description -*
&nbsp;

### PlayerConditionID
*- no description -*
&nbsp;

### QuestID
*- no description -*
&nbsp;

### LfgDungeonID
*- no description -*
&nbsp;

### RewardItemID
*- no description -*
&nbsp;

### UiTextureAtlasMemberID
*- no description -*
&nbsp;

### UiTextureKitID
*- no description -*
&nbsp;

### MapID
*- no description -*
&nbsp;

### AreaTableID
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/adventure_journal_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'adventure_journal_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/adventure_map_poi_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'adventure_map_poi_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>
