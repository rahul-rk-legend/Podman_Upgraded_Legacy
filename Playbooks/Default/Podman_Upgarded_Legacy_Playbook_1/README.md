# Podman_Upgarded_Legacy_Playbook_1




**Enabled:** True

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Case Tag_1|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Case Comment_2|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|

### Involved Blocks
|Name|Description|
|----|-----------|
|Podman_Upgarded_Legacy_Block_2|An embedded workflow that can receive inputs and return an output.|
