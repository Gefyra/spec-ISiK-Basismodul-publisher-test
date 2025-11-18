# ISiK CapabilityStatement VitalSign ICU Source Minimal Rolle - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK CapabilityStatement VitalSign ICU Source Minimal Rolle**

## CapabilityStatement: ISiK CapabilityStatement VitalSign ICU Source Minimal Rolle 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceMinimalRolle | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKCapabilityStatementVitalSignICUSourceMinimalRolle |

 
Dieses CapabilityStatement beschreibt alle Interaktionen, die ein System unterstützen MUSS, welches diese Rolle implementiert. 
Die CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). Zur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, wird die[CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html)mit den möglichen Werten`SHALL`(=MUSS) und`MAY`(=KANN) verwendet. 

 
Das vorliegende CapabilityStatement beschreibt verpflichtende Interaktionen, die ein ISiK-konformes System oder eine Systemkomponenten in der Rolle 'VitalSign ICU Source Minimal' zur Unterstützung des ICU-Normalstation-Workflows implementieren muss. 
Die Interaktionen umfassen die Bereitstellung von Vitalparametern, die für die Behandlung von Patienten notwendig sind und sie z.B. typischerweise auf einer Normalstation in einem KIS erfasst werden. 
**HISTORIE:** 
**Historie**: mit der Version 4.0.2 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement im Sinne einer eigenständigen Rolle extrahiert (die Funktionalität bleibt dabei unverändert). 
**Historie**: mit der Version 4.0.1 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement überarbeitet. 
**Version 4.0.1** 
* `change` Die Verbindlichkeit des Suchparameters `subject` wurde von SHALL auf MAY reduziert, da der Suchparameter `patient` für ISiK-Zwecke ausreichend ist.
* `change` Die Verbindlichkeit von Include und RevInclude wurde von SHALL auf MAY reduziert, außer bei den Parameter `patient` und `encounter`, da diese für ISiK-Zwecke ausreichend sind.
 

 [Raw OpenAPI-Swagger Definition file](ISiKCapabilityStatementVitalSignICUSourceMinimalRolle.openapi.json) | [Download](ISiKCapabilityStatementVitalSignICUSourceMinimalRolle.openapi.json) 

## ISiK CapabilityStatement VitalSign ICU Source Minimal Rolle

* Implementation Guide Version: 0.1.0 
* FHIR Version: 4.0.1 
* Supported Formats: `application/fhir+xml`, `application/fhir+json`
* Published on: 2025-10-23 
* Published by: Gefyra GmbH 

> **Note to Implementers: FHIR Capabilities**Any FHIR capability may be 'allowed' by the system unless explicitly marked as 'SHALL NOT'. A few items are marked as MAY in the Implementation Guide to highlight their potential relevance to the use case.

## FHIR RESTful Capabilities

### Mode: server

### Capabilities by Resource/Profile

#### Summary

The summary table lists the resources that are part of this configuration, and for each resource it lists:

* The relevant profiles (if any)
* The interactions supported by each resource (**R**ead, **S**earch, **U**pdate, and **C**reate, are always shown, while **VR**ead, **P**atch, **D**elete, **H**istory on **I**nstance, or **H**istory on **T**ype are only present if at least one of the resources has support for them.
* The required, recommended, and some optional search parameters (if any).
* The linked resources enabled for `_include`
* The other resources enabled for `_revinclude`
* The operations on the resource (if any)

| | | | | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| [Observation](#Observation1-1) | Supported Profiles  [SD MII ICU Intrakranieller Druck ICP](StructureDefinition-sd-mii-icu-intrakranieller-druck-icp.md)  [SD MII ICU Koerpergewicht Percentil Altersabhaengig](StructureDefinition-sd-mii-icu-koerpergewicht-percentil-altersabhaengig.md)  [SD MII ICU Koerpergroesse Percentil](StructureDefinition-sd-mii-icu-koerpergroesse-percentil-altersabhaengig.md)  [SD MII ICU Ideales Koerpergewicht](StructureDefinition-sd-mii-icu-ideales-koerpergewicht.md)  [SD MII ICU Sauerstoffsaettigung Im Arteriellen Blut Durch Pulsoxymetrie](StructureDefinition-sd-mii-icu-o2saettigung-im-arteriellen-blut-durch-pulsoxymetrie.md)  [SD MII ICU Puls](StructureDefinition-sd-mii-icu-puls.md)  [SD MII ICU Koerpertemperatur Kern](StructureDefinition-sd-mii-icu-koerpertemperatur-kern.md)  [SD MII ICU Koerpertemperatur Gelenk](StructureDefinition-sd-mii-icu-koerpertemperatur-gelenk.md)  [SD MII ICU Koerpertemperatur Stirn](StructureDefinition-sd-mii-icu-koerpertemperatur-stirn.md)  [SD MII ICU Koerpertemperatur nasal](StructureDefinition-sd-mii-icu-koerpertemperatur-nasal.md)  [SD MII ICU Koerpertemperatur Leiste](StructureDefinition-sd-mii-icu-koerpertemperatur-leiste.md)  [SD MII ICU Koerpertemperatur Achsel](StructureDefinition-sd-mii-icu-koerpertemperatur-achsel.md)  [SD MII ICU Koerpertemperatur unter der Zunge](StructureDefinition-sd-mii-icu-koerpertemperatur-unter-der-zunge.md)  [SD MII ICU Koerpertemperatur vaginal](StructureDefinition-sd-mii-icu-koerpertemperatur-vaginal.md)  [SD MII ICU Koerpertemperatur Harnblase](StructureDefinition-sd-mii-icu-koerpertemperatur-harnblase.md)  [SD MII ICU Koerpertemperatur rektal](StructureDefinition-sd-mii-icu-koerpertemperatur-rektal.md)  [SD MII ICU Koerpertemperatur Trommelfell](StructureDefinition-sd-mii-icu-koerpertemperatur-trommelfell.md) | **Y** | **Y** |  |  | _id, _tag, _count, _has, category, status, date, code, patient, subject, encounter, combo-code, combo-code-value-quantity, component-code |  |  |  |

-------

#### Resource Conformance: SHALL Observation

Core FHIR Resource

[Observation](http://hl7.org/fhir/R4/observation.html)

Reference Policy

Interaction summary

* **SHALL** support `read`, `search-type`.

Supported Profiles
[SD MII ICU Intrakranieller Druck ICP](StructureDefinition-sd-mii-icu-intrakranieller-druck-icp.md)
[SD MII ICU Koerpergewicht Percentil Altersabhaengig](StructureDefinition-sd-mii-icu-koerpergewicht-percentil-altersabhaengig.md)
[SD MII ICU Koerpergroesse Percentil](StructureDefinition-sd-mii-icu-koerpergroesse-percentil-altersabhaengig.md)
[SD MII ICU Ideales Koerpergewicht](StructureDefinition-sd-mii-icu-ideales-koerpergewicht.md)
[SD MII ICU Sauerstoffsaettigung Im Arteriellen Blut Durch Pulsoxymetrie](StructureDefinition-sd-mii-icu-o2saettigung-im-arteriellen-blut-durch-pulsoxymetrie.md)
[SD MII ICU Puls](StructureDefinition-sd-mii-icu-puls.md)
[SD MII ICU Koerpertemperatur Kern](StructureDefinition-sd-mii-icu-koerpertemperatur-kern.md)
[SD MII ICU Koerpertemperatur Gelenk](StructureDefinition-sd-mii-icu-koerpertemperatur-gelenk.md)
[SD MII ICU Koerpertemperatur Stirn](StructureDefinition-sd-mii-icu-koerpertemperatur-stirn.md)
[SD MII ICU Koerpertemperatur nasal](StructureDefinition-sd-mii-icu-koerpertemperatur-nasal.md)
[SD MII ICU Koerpertemperatur Leiste](StructureDefinition-sd-mii-icu-koerpertemperatur-leiste.md)
[SD MII ICU Koerpertemperatur Achsel](StructureDefinition-sd-mii-icu-koerpertemperatur-achsel.md)
[SD MII ICU Koerpertemperatur unter der Zunge](StructureDefinition-sd-mii-icu-koerpertemperatur-unter-der-zunge.md)
[SD MII ICU Koerpertemperatur vaginal](StructureDefinition-sd-mii-icu-koerpertemperatur-vaginal.md)
[SD MII ICU Koerpertemperatur Harnblase](StructureDefinition-sd-mii-icu-koerpertemperatur-harnblase.md)
[SD MII ICU Koerpertemperatur rektal](StructureDefinition-sd-mii-icu-koerpertemperatur-rektal.md)
[SD MII ICU Koerpertemperatur Trommelfell](StructureDefinition-sd-mii-icu-koerpertemperatur-trommelfell.md)

Search Parameters


 



## Resource Content

```json
{
  "resourceType" : "CapabilityStatement",
  "id" : "ISiKCapabilityStatementVitalSignICUSourceMinimalRolle",
  "url" : "http://gefyra.info/training/CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceMinimalRolle",
  "version" : "0.1.0",
  "name" : "ISiKCapabilityStatementVitalSignICUSourceMinimalRolle",
  "title" : "ISiK CapabilityStatement VitalSign ICU Source Minimal Rolle",
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
  "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
  "purpose" : "Das vorliegende CapabilityStatement beschreibt verpflichtende Interaktionen, die ein ISiK-konformes System oder eine Systemkomponenten in der Rolle 'VitalSign ICU Source Minimal' zur Unterstützung des ICU-Normalstation-Workflows implementieren muss.\n\nDie Interaktionen umfassen die Bereitstellung von Vitalparametern, die für die Behandlung von Patienten notwendig sind und sie z.B. typischerweise auf einer Normalstation in einem KIS erfasst werden.\n  \n**HISTORIE:**    \n\n*Historie*: mit der Version 4.0.2 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement im Sinne einer eigenständigen Rolle extrahiert (die Funktionalität bleibt dabei unverändert).\n\n*Historie*: mit der Version 4.0.1 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement überarbeitet.\n\n**Version 4.0.1**\n\n* `change` Die Verbindlichkeit des Suchparameters `subject` wurde von SHALL auf MAY reduziert, da der Suchparameter `patient` für ISiK-Zwecke ausreichend ist.   \n* `change` Die Verbindlichkeit von Include und RevInclude wurde von SHALL auf MAY reduziert, außer bei den Parameter `patient` und `encounter`, da diese für ISiK-Zwecke ausreichend sind.  \n\n",
  "kind" : "requirements",
  "fhirVersion" : "4.0.1",
  "format" : ["application/fhir+xml", "application/fhir+json"],
  "rest" : [
    {
      "mode" : "server",
      "resource" : [
        {
          "extension" : [
            {
              "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
              "valueCode" : "SHALL"
            }
          ],
          "type" : "Observation",
          "supportedProfile" : [
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-intrakranieller-druck-icp",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpergewicht-percentil-altersabhaengig",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpergroesse-percentil-altersabhaengig",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-ideales-koerpergewicht",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-o2saettigung-im-arteriellen-blut-durch-pulsoxymetrie",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-puls",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-kern",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-gelenk",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-stirn",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-nasal",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-leiste",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-achsel",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-unter-der-zunge",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-vaginal",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-harnblase",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-rektal",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-trommelfell"
          ],
          "_supportedProfile" : [
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ]
            }
          ],
          "interaction" : [
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "code" : "read"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "code" : "search-type"
            }
          ],
          "searchParam" : [
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "_id",
              "definition" : "http://hl7.org/fhir/SearchParameter/Resource-id",
              "type" : "token",
              "documentation" : "**Beispiel:**\n        `GET [base]/[Resourcetype]?_id=103270`\n        **Anwendungshinweis:**\n        Der Parameter `_id` wird selten alleinstehend verwendet, da sich zum Abruf einer Ressource\n        anhand der `id`  die `READ`-Interaktion besser anbietet. Der Parameter kann jedoch verwendet werden,\n        um den Abruf einer Ressource bspw. mit einem `_include` weiterer Ressourcen zu verbinden,\n        z.B. zum Abruf eines Encounters in Verbindung mit dem zugehörigen Patienten:\n        `GET [base]/Encounter?_id=103270&_include=Encounter:patient`\n        Weitere Details siehe FHIR-Kernspezifikation, Abschnitt [Parameters for all resources](https://hl7.org/fhir/R4/search.html#all).\n        Dieser Suchparameter ist für die Umsetzung des IHE PDQm Profils verpflichtend."
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "_tag",
              "definition" : "http://hl7.org/fhir/SearchParameter/Resource-tag",
              "type" : "token",
              "documentation" : "**Beispiel:**\n        `GET [base]/[Resourcetype]?_tag=https://example.org/codes|needs-review`\n        **Anwendungshinweis:**\n        Weitere Details siehe FHIR-Kernspezifikation, Abschnitt [Parameters for all resources](https://hl7.org/fhir/R4/search.html#all)\n        sowie Abschnitt [Tags](https://www.hl7.org/fhir/R4/resource.html#simple-tags).  "
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "_count",
              "type" : "number",
              "documentation" : "**Beispiel:**\n        `GET [base]/[Resourcetype]?_count=100`\n        **Anwendungshinweis:**\n        Weitere Details siehe FHIR-Kernspezifikation, Abschnitt [Page Count](https://www.hl7.org/fhir/R4/search.html#count).  "
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "MAY"
                }
              ],
              "name" : "_has",
              "type" : "string",
              "documentation" : "**Beispiel:** Suche nach allen Patienten, die eine Observation  mit dem Code '1234-5' haben\n        `GET [base]/Patient?_has:Observation:patient:code=1234-5`\n        **Beispiel:** Suche nach allen Encountern, bei denen die Diagnose 'A12.3' gestellt wurde\n        `GET [base]/Encounter?_has:Condition:encounter:code=A12.3`\n        **Anwendungshinweis:**\n        Weitere Details siehe FHIR-Kernspezifikation, Abschnitt [Reverse Chaining](https://hl7.org/fhir/R4/search.html#has).  "
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "category",
              "definition" : "http://hl7.org/fhir/SearchParameter/Observation-category",
              "type" : "token"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "status",
              "definition" : "http://hl7.org/fhir/SearchParameter/Observation-status",
              "type" : "token"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "date",
              "definition" : "http://hl7.org/fhir/SearchParameter/clinical-date",
              "type" : "date"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "code",
              "definition" : "http://hl7.org/fhir/SearchParameter/clinical-code",
              "type" : "token"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "patient",
              "definition" : "http://hl7.org/fhir/SearchParameter/clinical-patient",
              "type" : "reference"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "MAY"
                }
              ],
              "name" : "subject",
              "definition" : "http://hl7.org/fhir/SearchParameter/Observation-subject",
              "type" : "reference"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "encounter",
              "definition" : "http://hl7.org/fhir/SearchParameter/clinical-encounter",
              "type" : "reference"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "combo-code",
              "definition" : "http://hl7.org/fhir/SearchParameter/Observation-combo-code",
              "type" : "token"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "combo-code-value-quantity",
              "definition" : "http://hl7.org/fhir/SearchParameter/Observation-combo-code-value-quantity",
              "type" : "composite"
            },
            {
              "extension" : [
                {
                  "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
                  "valueCode" : "SHALL"
                }
              ],
              "name" : "component-code",
              "definition" : "http://hl7.org/fhir/SearchParameter/Observation-component-code",
              "type" : "token"
            }
          ]
        }
      ]
    }
  ]
}

```
