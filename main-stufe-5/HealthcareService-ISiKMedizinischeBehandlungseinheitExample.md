# ISiKMedizinischeBehandlungseinheitExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKMedizinischeBehandlungseinheitExample**

## Example HealthcareService: ISiKMedizinischeBehandlungseinheitExample

Profile: [ISiKMedizinischeBehandlungseinheit](StructureDefinition-ISiKMedizinischeBehandlungseinheit.md)

**active**: true

**type**: General Practice

**specialty**: Allgemeinmedizin

**name**: Allgemeine Beratungsstelle der Fachabteilung 0100



## Resource Content

```json
{
  "resourceType" : "HealthcareService",
  "id" : "ISiKMedizinischeBehandlungseinheitExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedizinischeBehandlungseinheit"
    ]
  },
  "active" : true,
  "type" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/service-type",
          "code" : "124"
        }
      ]
    }
  ],
  "specialty" : [
    {
      "coding" : [
        {
          "system" : "http://ihe-d.de/CodeSystems/AerztlicheFachrichtungen",
          "code" : "ALLG"
        }
      ]
    }
  ],
  "name" : "Allgemeine Beratungsstelle der Fachabteilung 0100"
}

```
