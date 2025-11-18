# Validierung von Formulareingaben gegen RegExPattern - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Validierung von Formulareingaben gegen RegExPattern**

## Questionnaire: Validierung von Formulareingaben gegen RegExPattern 

| | |
| :--- | :--- |
| *Official URL*:https://gematik.de/fhir/isik/Questionnaire/ExampleInputPatternValidation | *Version*:0.1.0 |
| Draft as of 2025-11-18 | *Computable Name*:ExampleInputPatternValidation |

 

### Beispiel-Questionnaire mit Validierung von Benutzereingaben mittels einer FHIRPath-Expression

 
Die Validierung erfolgt über die[targetConstraint](https://hl7.org/fhir/extensions/StructureDefinition-targetConstraint.html)-Extension 

Profile: [ISiKFormularDefinition](StructureDefinition-ISiKFormularDefinition.md)

* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ExampleInputPatternValidation
  * [Text](https://hl7.org/fhir/R4/formats.html#table): ### Beispiel-Questionnaire mit Validierung von Benutzereingaben mittels einer FHIRPath-Expression Die Validierung erfolgt über die [targetConstraint](https://hl7.org/fhir/extensions/StructureDefinition-targetConstraint.html)-Extension
  * [Cardinality](https://hl7.org/fhir/R4/formats.html#table): 
  * [Type](https://hl7.org/fhir/R4/formats.html#table): Questionnaire
  * [Description & Constraints](https://hl7.org/fhir/R4/formats.html#table)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC): https://gematik.de/fhir/isik/Questionnaire/ExampleInputPatternValidation#0.1.0
* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ![](icon-q-string.png)1.4
  * [Text](https://hl7.org/fhir/R4/formats.html#table): Versichertennummer:
  * [Cardinality](https://hl7.org/fhir/R4/formats.html#table): 0..1
  * [Type](https://hl7.org/fhir/R4/formats.html#table): [string](https://hl7.org/fhir/R4/codesystem-item-type.html#item-type-string)
  * [Description & Constraints](https://hl7.org/fhir/R4/formats.html#table)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC): 
* [LinkID](https://hl7.org/fhir/R4/formats.html#table): ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH3goXBCwdPqAP0wAAAldJREFUOMuNk0tIlFEYhp9z/vE2jHkhxXA0zJCMitrUQlq4lnSltEqCFhFG2MJFhIvIFpkEWaTQqjaWZRkp0g26URZkTpbaaOJkDqk10szoODP//7XIMUe0elcfnPd9zsfLOYplGrpRwZaqTtw3K7PtGem7Q6FoidbGgqHVy/HRb669R+56zx7eRV1L31JGxYbBtjKK93cxeqfyQHbehkZbUkK20goELEuIzEd+dHS+qz/Y8PTSif0FnGkbiwcAjHaU1+QWOptFiyCLp/LnKptpqIuXHx6rbR26kJcBX3yLgBfnd7CxwJmflpP2wUg0HIAoUUpZBmKzELGWcN8nAr6Gpu7tLU/CkwAaoKTWRSQyt89Q8w6J+oVQkKnBoblH7V0PPvUOvDYXfopE/SJmALsxnVm6LbkotrUtNowMeIrVrBcBpaMmdS0j9df7abpSuy7HWehwJdt1lhVwi/J58U5beXGAF6c3UXLycw1wdFklArBn87xdh0ZsZtArghBdAA3+OEDVubG4UEzP6x1FOWneHh2VDAHBAt80IbdXDcesNoCvs3E5AFyNSU5nbrDPZpcUEQQTFZiEVx+51fxMhhyJEAgvlriadIJZZksRuwBYMOPBbO3hePVVqgEJhFeUuFLhIPkRP6BQLIBrmMenujm/3g4zc398awIe90Zb5A1vREALqneMcYgP/xVQWlG+Ncu5vgwwlaUNx+3799rfe96u9K0JSDXcOzOTJg4B6IgmXfsygc7/Bvg9g9E58/cDVmGIBOP/zT8Bz1zqWqpbXIsd0O9hajXfL6u4BaOS6SeWAAAAAElFTkSuQmCC)Documentation for this format



## Resource Content

```json
{
  "resourceType" : "Questionnaire",
  "id" : "ExampleInputPatternValidation",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
    ]
  },
  "url" : "https://gematik.de/fhir/isik/Questionnaire/ExampleInputPatternValidation",
  "version" : "0.1.0",
  "name" : "ExampleInputPatternValidation",
  "title" : "Validierung von Formulareingaben gegen RegExPattern",
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
  "description" : "### Beispiel-Questionnaire mit Validierung von Benutzereingaben mittels einer FHIRPath-Expression  \nDie Validierung erfolgt über die [targetConstraint](https://hl7.org/fhir/extensions/StructureDefinition-targetConstraint.html)-Extension",
  "item" : [
    {
      "extension" : [
        {
          "extension" : [
            {
              "url" : "key",
              "valueId" : "kvid-1"
            },
            {
              "url" : "severity",
              "valueCode" : "warning"
            },
            {
              "url" : "expression",
              "valueExpression" : {
                "language" : "text/fhirpath",
                "expression" : "matches(^[A-Z][0-9]{9}$)"
              }
            },
            {
              "url" : "human",
              "valueString" : "Eine Versichertennummer muss mit einem Großbuchstaben beginnen, gefolgt von 9 Zahlen!"
            }
          ],
          "url" : "http://hl7.org/fhir/StructureDefinition/targetConstraint"
        }
      ],
      "linkId" : "1.4",
      "text" : "Versichertennummer:",
      "type" : "string"
    }
  ]
}

```
