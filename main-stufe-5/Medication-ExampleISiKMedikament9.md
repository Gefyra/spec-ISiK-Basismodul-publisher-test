# ExampleISiKMedikament9 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKMedikament9**

## Example Medication: ExampleISiKMedikament9

Zytostatikum mit absoluter Wirkstärken-Angabe:



## Resource Content

```json
{
  "resourceType" : "Medication",
  "id" : "ExampleISiKMedikament9",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
    ]
  },
  "code" : {
    "text" : "Infusion bestehend aus 142 mg Paclitaxel aufgelöst zur Verabreichung in 500 ml 5-%iger (50 mg/ml) Glucose-Infusionslösung"
  },
  "status" : "active",
  "form" : {
    "coding" : [
      {
        "system" : "http://standardterms.edqm.eu",
        "code" : "11210000",
        "display" : "Solution for infusion"
      }
    ]
  },
  "ingredient" : [
    {
      "itemCodeableConcept" : {
        "coding" : [
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/atc",
            "version" : "2024",
            "code" : "L01CD01",
            "display" : "Paclitaxel"
          }
        ]
      },
      "isActive" : true,
      "strength" : {
        "numerator" : {
          "value" : 142,
          "unit" : "mg",
          "system" : "http://unitsofmeasure.org",
          "code" : "mg"
        },
        "denominator" : {
          "value" : 500,
          "unit" : "Milliliter",
          "system" : "http://unitsofmeasure.org",
          "code" : "mL"
        }
      }
    },
    {
      "itemCodeableConcept" : {
        "coding" : [
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/atc",
            "version" : "2024",
            "code" : "B05BA11",
            "display" : "Glucose"
          }
        ]
      },
      "isActive" : false,
      "strength" : {
        "numerator" : {
          "value" : 50,
          "unit" : "mg",
          "system" : "http://unitsofmeasure.org",
          "code" : "mg"
        },
        "denominator" : {
          "value" : 1,
          "unit" : "Milliliter",
          "system" : "http://unitsofmeasure.org",
          "code" : "mL"
        }
      }
    }
  ]
}

```
