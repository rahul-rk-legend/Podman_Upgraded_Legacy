# GitSync

## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|False|
|Sample Integration - Simple Connector Example|This is an example of a simple connector. It's integrated with "api.vatcomply.com" service and provides all of the main design ideas necessary to build a stable connector. Dynamic List defines what rates should be returned for a given currency and expects input in the format "EUR" etc.|False|


## Playbooks
|Name|Description|
|----|-----------|
|Podman_Upgarded_Legacy_Playbook_1||
|Podman_Upgarded_Legacy_Playbook_2||


## Visual Families
|Name|Description|
|----|-----------|
|Podman_Upgraded_Legacy_Visual_Families_1|Podman_Upgraded_Legacy_Visual_Families_1|
|Podman_Upgraded_Legacy_Visual_Families_2|Podman_Upgraded_Legacy_Visual_Families_2|


## Jobs
|Name|Description|
|----|-----------|
|Google Chronicle Alerts Creator Job|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Simple Job Example|This is an example of a simple job. It has 2 functions: if a case has a tag "Closed", it will close the case from the job, if a case has a tag "Currency", it will add a comment to the case.|

