# Vorbelegung von Observations - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Vorbelegung von Observations**

## Questionnaire: Vorbelegung von Observations 

| | |
| :--- | :--- |
| *Official URL*:https://gematik.de/fhir/isik/Questionnaire/ExamplePrePopObservation | *Version*:0.1.0 |
| Draft as of 2025-11-18 | *Computable Name*:ExamplePrePopObservation |

 

### Beispiel-Questionnaire mit automatischer Vorbelegung von Observations

 
Die Suche nach passenden Observations geschieht innerhlab des Patienten-Kontextes anhand des in`item-code`hinterlegten Codes. Die Extension[SDC-ObservationLinkPeriod](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationLinkPeriod.html)legt fest, wie alt Observations maximal sein dürfen, um für die Vorbelegung herangezogen zu werden (hier: max. 1 Jahr)
Die Extension[SDC-ObservationExtract](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationExtract.html)legt fest, ob aus den Angaben des Questionnaires eine neue Observation extrahiert werden soll (hier: true) 

Profile: [ISiKFormularDefinition](StructureDefinition-ISiKFormularDefinition.md)

* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ExamplePrePopObservation
  * [Text](https://hl7.org/fhir/R4/formats.html#table): ### Beispiel-Questionnaire mit automatischer Vorbelegung von Observations Die Suche nach passenden Observations geschieht innerhlab des Patienten-Kontextes anhand des in `item-code`hinterlegten Codes. Die Extension [SDC-ObservationLinkPeriod](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationLinkPeriod.html) legt fest, wie alt Observations maximal sein dürfen, um für die Vorbelegung herangezogen zu werden (hier: max. 1 Jahr) Die Extension [SDC-ObservationExtract](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationExtract.html) legt fest, ob aus den Angaben des Questionnaires eine neue Observation extrahiert werden soll (hier: true)
  * [Cardinality](https://hl7.org/fhir/R4/formats.html#table): 
  * [Type](https://hl7.org/fhir/R4/formats.html#table): Questionnaire
  * [Flags](https://hl7.org/fhir/R4/formats.html#table): 
  * [Description & Constraints](https://hl7.org/fhir/R4/formats.html#table)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC): https://gematik.de/fhir/isik/Questionnaire/ExamplePrePopObservation#0.1.0
* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ![](icon-q-group.png)3
  * [Text](https://hl7.org/fhir/R4/formats.html#table): Pflegegrad
  * [Cardinality](https://hl7.org/fhir/R4/formats.html#table): 1..1
  * [Type](https://hl7.org/fhir/R4/formats.html#table): [group](https://hl7.org/fhir/R4/codesystem-item-type.html#item-type-group)
  * [Flags](https://hl7.org/fhir/R4/formats.html#table): 
  * [Description & Constraints](https://hl7.org/fhir/R4/formats.html#table)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC): 
* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ![](icon-q-coding.png)3.1
  * [Text](https://hl7.org/fhir/R4/formats.html#table): Bitte geben Sie den Pflegegrad an:
  * [Cardinality](https://hl7.org/fhir/R4/formats.html#table): 0..1
  * [Type](https://hl7.org/fhir/R4/formats.html#table): [choice](https://hl7.org/fhir/R4/codesystem-item-type.html#item-type-choice)
  * [Flags](https://hl7.org/fhir/R4/formats.html#table): 
  * [Description & Constraints](https://hl7.org/fhir/R4/formats.html#table)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC): Value Set:[PflegegradDE ValueSet](ValueSet-ExamplePrePopObservation_pflegegrad-de.md)
* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC)Documentation for this format

## Contained Resources

-------

Profile: [Shareable ValueSet](http://hl7.org/fhir/R4/shareablevalueset.html)

This value set contains 6 concepts

* **System**: `http://fhir.de/CodeSystem/bfarm/ops`
  * **Code**:   9-984.6
  * **Display**: Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 1
* **System**: `http://fhir.de/CodeSystem/bfarm/ops`
  * **Code**:   9-984.7
  * **Display**: Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 2
* **System**: `http://fhir.de/CodeSystem/bfarm/ops`
  * **Code**:   9-984.8
  * **Display**: Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 3
* **System**: `http://fhir.de/CodeSystem/bfarm/ops`
  * **Code**:   9-984.9
  * **Display**: Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 4
* **System**: `http://fhir.de/CodeSystem/bfarm/ops`
  * **Code**:   9-984.a
  * **Display**: Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 5
* **System**: `http://fhir.de/CodeSystem/bfarm/ops`
  * **Code**:   9-984.b
  * **Display**: Pflegebedürftigkeit: Erfolgter Antrag auf Einstufung in einen Pflegegrad



## Resource Content

```json
{
  "resourceType" : "Questionnaire",
  "id" : "ExamplePrePopObservation",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
    ]
  },
  "contained" : [
    {
      "resourceType" : "ValueSet",
      "id" : "pflegegrad-de",
      "meta" : {
        "profile" : ["http://hl7.org/fhir/StructureDefinition/shareablevalueset"]
      },
      "url" : "http://fhir.de/ValueSet/pflegegrad-de",
      "version" : "1.5.4",
      "name" : "PflegegradDE",
      "title" : "PflegegradDE ValueSet",
      "status" : "active",
      "experimental" : false,
      "date" : "2025-06-16",
      "publisher" : "HL7 Deutschland e.V. (Technisches Komitee FHIR)",
      "contact" : [
        {
          "telecom" : [
            {
              "system" : "url",
              "value" : "http://hl7.de/technische-komitees/fhir/"
            }
          ]
        }
      ],
      "description" : "Codes zur genaueren Differenzierung des Pflegegrads.",
      "compose" : {
        "include" : [
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "filter" : [
              {
                "property" : "parent",
                "op" : "=",
                "value" : "9-984"
              }
            ]
          }
        ]
      },
      "expansion" : {
        "identifier" : "440c50b5-7272-4184-9ddd-95a75d8207f8",
        "timestamp" : "2019-07-06",
        "total" : 6,
        "contains" : [
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "code" : "9-984.6",
            "display" : "Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 1"
          },
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "code" : "9-984.7",
            "display" : "Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 2"
          },
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "code" : "9-984.8",
            "display" : "Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 3"
          },
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "code" : "9-984.9",
            "display" : "Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 4"
          },
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "code" : "9-984.a",
            "display" : "Pflegebedürftigkeit: Pflegebedürftig nach Pflegegrad 5"
          },
          {
            "system" : "http://fhir.de/CodeSystem/bfarm/ops",
            "code" : "9-984.b",
            "display" : "Pflegebedürftigkeit: Erfolgter Antrag auf Einstufung in einen Pflegegrad"
          }
        ]
      }
    }
  ],
  "extension" : [
    {
      "extension" : [
        {
          "url" : "name",
          "valueCoding" : {
            "system" : "http://hl7.org/fhir/uv/sdc/CodeSystem/launchContext",
            "code" : "patient"
          }
        },
        {
          "url" : "type",
          "valueCode" : "Patient"
        },
        {
          "url" : "description",
          "valueString" : "Patientenkontext"
        }
      ],
      "url" : "http://hl7.org/fhir/uv/sdc/StructureDefinition/sdc-questionnaire-launchContext"
    }
  ],
  "url" : "https://gematik.de/fhir/isik/Questionnaire/ExamplePrePopObservation",
  "version" : "0.1.0",
  "name" : "ExamplePrePopObservation",
  "title" : "Vorbelegung von Observations",
  "status" : "draft",
  "experimental" : false,
  "subjectType" : ["Patient"],
  "date" : "2025-11-18T10:29:41+00:00",
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
  "description" : "### Beispiel-Questionnaire mit automatischer Vorbelegung von Observations  \nDie Suche nach passenden Observations geschieht innerhlab des Patienten-Kontextes anhand des in `item-code`hinterlegten Codes.\nDie Extension [SDC-ObservationLinkPeriod](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationLinkPeriod.html) legt fest, wie alt  Observations maximal sein dürfen, um für die Vorbelegung herangezogen zu werden (hier: max. 1 Jahr)  \nDie Extension [SDC-ObservationExtract](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationExtract.html) legt fest, ob aus den Angaben des Questionnaires eine neue Observation extrahiert werden soll (hier: true)",
  "item" : [
    {
      "linkId" : "3",
      "text" : "Pflegegrad",
      "type" : "group",
      "required" : true,
      "item" : [
        {
          "extension" : [
            {
              "url" : "http://hl7.org/fhir/uv/sdc/StructureDefinition/sdc-questionnaire-observationLinkPeriod",
              "valueDuration" : {
                "value" : 1,
                "system" : "http://unitsofmeasure.org",
                "code" : "a"
              }
            },
            {
              "url" : "http://hl7.org/fhir/uv/sdc/StructureDefinition/sdc-questionnaire-observationExtract",
              "valueBoolean" : true
            }
          ],
          "linkId" : "3.1",
          "code" : [
            {
              "system" : "http://loinc.org",
              "code" : "80391-6"
            }
          ],
          "text" : "Bitte geben Sie den Pflegegrad an:",
          "type" : "choice",
          "answerValueSet" : "#pflegegrad-de"
        }
      ]
    }
  ]
}

```
