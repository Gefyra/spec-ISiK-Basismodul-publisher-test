# ISiKSubscriptionNotification - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKSubscriptionNotification**

## Resource Profile: ISiKSubscriptionNotification 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKSubscriptionNotification | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKSubscriptionNotification |

 
ISiKSubscriptionNotification 

**Usages:**

* Examples for this Profile: [Bundle/SubscriptionNotificationBundleExample](Bundle-SubscriptionNotificationBundleExample.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKSubscriptionNotification)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKSubscriptionNotification.csv), [Excel](StructureDefinition-ISiKSubscriptionNotification.xlsx), [Schematron](StructureDefinition-ISiKSubscriptionNotification.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKSubscriptionNotification",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKSubscriptionNotification",
  "version" : "0.1.0",
  "name" : "ISiKSubscriptionNotification",
  "title" : "ISiKSubscriptionNotification",
  "status" : "active",
  "experimental" : false,
  "date" : "2025-10-23",
  "publisher" : "Gefyra GmbH",
  "contact" : [
    {
      "name" : "Gefyra GmbH",
      "telecom" : [
        {
          "system" : "url",
          "value" : "https://gefyra.info/"
        }
      ]
    }
  ],
  "description" : "ISiKSubscriptionNotification",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    },
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "cda",
      "uri" : "http://hl7.org/v3/cda",
      "name" : "CDA (R2)"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Bundle",
  "baseDefinition" : "http://gefyra.info/training/StructureDefinition/BackportSubscriptionNotificationR4Fixed",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Bundle",
        "path" : "Bundle"
      }
    ]
  }
}

```
