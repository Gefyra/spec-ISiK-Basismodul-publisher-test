# Encounter-date-start - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Encounter-date-start**

## SearchParameter: Encounter-date-start 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/SearchParameter/Encounter-date-start | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:DateStart |

 
The actual start date of the Encounter (Backport from R5). The parameter cannot repeat or have multiple values. 

## DateStart

Parameter `date-start`:`date`

The actual start date of the Encounter (Backport from R5). The parameter cannot repeat or have multiple values.

| | |
| :--- | :--- |
| Resource | [Encounter](http://hl7.org/fhir/R4/encounter.html) |
| Expression | `Encounter.period.start` |
| Multiples | * multipleAnd: It's up to the server whether the parameter may repeat in order to specify multiple values that must all be true
* multipleOr: It's up to the server whether the parameter can have multiple values (separated by comma) where at least one must be true
 |
| Comparators | Allowed: eq, ne, gt, ge, lt, le, sa, eb, ap |



## Resource Content

```json
{
  "resourceType" : "SearchParameter",
  "id" : "Encounter-date-start",
  "url" : "http://gefyra.info/training/SearchParameter/Encounter-date-start",
  "version" : "0.1.0",
  "name" : "DateStart",
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
  "description" : "The actual start date of the Encounter (Backport from R5). The parameter cannot repeat or have multiple values.",
  "code" : "date-start",
  "base" : ["Encounter"],
  "type" : "date",
  "expression" : "Encounter.period.start",
  "comparator" : [
    "eq",
    "ne",
    "gt",
    "ge",
    "lt",
    "le",
    "sa",
    "eb",
    "ap"
  ]
}

```
