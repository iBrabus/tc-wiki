---
title: reference_loot_template
description: 
published: true
date: 2021-08-30T09:24:17.518Z
tags: database, master, world
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/world/race_unlock_requirement" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'race_unlock_requirement'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/reputation_reward_rate" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'reputation_reward_rate'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [Entry](#Entry) | mediumint(8) | unsigned | PRI | NO | 0 |  |  |
| [Item](#Item) | mediumint(8) | unsigned | PRI | NO | 0 |  |  |
| [Reference](#Reference) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [Chance](#Chance) | float |  |  | NO | 100 |  |  |
| [QuestRequired](#QuestRequired) | tinyint(1) | signed |  | NO | 0 |  |  |
| [LootMode](#LootMode) | smallint(5) | unsigned |  | NO | 1 |  |  |
| [GroupId](#GroupId) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [MinCount](#MinCount) | tinyint(3) | unsigned |  | NO | 1 |  |  |
| [MaxCount](#MaxCount) | tinyint(3) | unsigned |  | NO | 1 |  |  |
| [Comment](#Comment) | varchar(255) | signed |  | YES | NULL |  |  |
&nbsp;
## Description of fields

### Entry
*- no description -*
&nbsp;

### Item
*- no description -*
&nbsp;

### Reference
*- no description -*
&nbsp;

### Chance
*- no description -*
&nbsp;

### QuestRequired
*- no description -*
&nbsp;

### LootMode
*- no description -*
&nbsp;

### GroupId
*- no description -*
&nbsp;

### MinCount
*- no description -*
&nbsp;

### MaxCount
*- no description -*
&nbsp;

### Comment
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/world/race_unlock_requirement" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'race_unlock_requirement'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/reputation_reward_rate" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'reputation_reward_rate'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>
