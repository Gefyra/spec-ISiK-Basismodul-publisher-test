# Medication Quantity - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Medication Quantity**

## Data Type Profile: Medication Quantity 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/MedicationQuantity | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:MedicationQuantity |

 
Quantity Datentyp der die Nutzung von UCUM vorgibt. Bei dimensionslosen Einheiten wie 'Tablette' wird ein code von '1' erwartet, 'Tablette' kann als String in Unit hinterlegt werden. 

**Usages:**

* Use this DataType Profile: [ISiKMedikament](StructureDefinition-ISiKMedikament.md), [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md), [ISiKMedikationsVerabreichung](StructureDefinition-ISiKMedikationsVerabreichung.md) and [ISiKMedikationsVerordnung](StructureDefinition-ISiKMedikationsVerordnung.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/MedicationQuantity)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-MedicationQuantity.csv), [Excel](StructureDefinition-MedicationQuantity.xlsx), [Schematron](StructureDefinition-MedicationQuantity.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "MedicationQuantity",
  "url" : "http://gefyra.info/training/StructureDefinition/MedicationQuantity",
  "version" : "0.1.0",
  "name" : "MedicationQuantity",
  "title" : "Medication Quantity",
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
  "description" : "Quantity Datentyp der die Nutzung von UCUM vorgibt. Bei dimensionslosen Einheiten wie 'Tablette' wird ein code von '1' erwartet, 'Tablette' kann als String in Unit hinterlegt werden.",
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
  "kind" : "complex-type",
  "abstract" : false,
  "type" : "Quantity",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/SimpleQuantity",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Quantity.value",
        "path" : "Quantity.value",
        "min" : 1,
        "mustSupport" : true
      },
      {
        "id" : "Quantity.unit",
        "path" : "Quantity.unit",
        "mustSupport" : true
      },
      {
        "id" : "Quantity.system",
        "path" : "Quantity.system",
        "min" : 1,
        "patternUri" : "http://unitsofmeasure.org",
        "mustSupport" : true
      },
      {
        "id" : "Quantity.code",
        "path" : "Quantity.code",
        "min" : 1,
        "mustSupport" : true
      }
    ]
  }
}

```
