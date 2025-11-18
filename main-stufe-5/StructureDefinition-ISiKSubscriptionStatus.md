# ISiK Subscription Status - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Subscription Status**

## Resource Profile: ISiK Subscription Status 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKSubscriptionStatus | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKSubscriptionStatus |

 
ISiK Subscription Status 

**Usages:**

* Examples for this Profile: [Parameters/ISiKSubscriptionStatusExample](Parameters-ISiKSubscriptionStatusExample.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKSubscriptionStatus)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKSubscriptionStatus.csv), [Excel](StructureDefinition-ISiKSubscriptionStatus.xlsx), [Schematron](StructureDefinition-ISiKSubscriptionStatus.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKSubscriptionStatus",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKSubscriptionStatus",
  "version" : "0.1.0",
  "name" : "ISiKSubscriptionStatus",
  "title" : "ISiK Subscription Status",
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
  "description" : "ISiK Subscription Status",
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
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Parameters",
  "baseDefinition" : "http://gefyra.info/training/StructureDefinition/BackportSubscriptionStatusR4Fixed",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Parameters",
        "path" : "Parameters"
      }
    ]
  }
}

```
