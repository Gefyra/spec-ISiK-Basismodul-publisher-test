# ISiK CapabilityStatement VitalSign ICU Source Extended - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK CapabilityStatement VitalSign ICU Source Extended**

## CapabilityStatement: ISiK CapabilityStatement VitalSign ICU Source Extended 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceExtendedRolle | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKCapabilityStatementVitalSignICUSourceExtendedRolle |

 
Dieses CapabilityStatement beschreibt alle Interaktionen, die ein System unterstützen MUSS, welches diese Rolle implementiert. 
Die CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). Zur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, wird die[CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html)mit den möglichen Werten`SHALL`(=MUSS) und`MAY`(=KANN) verwendet. 

 
Das vorliegende CapabilityStatement beschreibt verpflichtende Interaktionen, die ein ISiK-konformes System oder eine Systemkomponente in der Rolle 'VitalSign ICU Source Extended' zur Unterstützung des ICU-Normalstation-Workflows implementieren muss. 
Die Interaktionen umfassen die Bereitstellung von Vitalparametern, die für die Behandlung von Intensivpatienten notwendig sind und sie z.B. typischerweise auf einer Intensivstation in einem PDMS erfasst werden. 
**HISTORIE:** 
**Historie**: mit der Version 4.0.2 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement im Sinne einer eigenständigen Rolle extrahiert (die Funktionalität bleibt dabei unverändert). 
**Historie**: mit der Version 4.0.1 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement überarbeitet. 

 [Raw OpenAPI-Swagger Definition file](ISiKCapabilityStatementVitalSignICUSourceExtendedRolle.openapi.json) | [Download](ISiKCapabilityStatementVitalSignICUSourceExtendedRolle.openapi.json) 

## ISiK CapabilityStatement VitalSign ICU Source Extended

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
| [Observation](#Observation1-1) | Supported Profiles  [SD MII ICU Pulmonalarterieller Wedge Druck](StructureDefinition-sd-mii-icu-pulmonalarterieller-wedge-druck.md)  [SD MII ICU Sauerstoffsaettigung Im Blut Preduktal Durch Pulsoxymetrie](StructureDefinition-sd-mii-icu-o2saettigung-im-blut-preduktal-durch-pulsoxymetrie.md)  [SD MII ICU Sauerstoffsaettigung Im Blut Postduktal Durch Pulsoxymetrie](StructureDefinition-sd-mii-icu-o2saettigung-im-blut-postduktal-durch-pulsoxymetrie.md)  [SD MII ICU Linksventrikulaeres Schlagvolumenindex](StructureDefinition-sd-mii-icu-linksventrikulaeres-schlagvolumenindex.md)  [SD MII ICU Linksventrikulaerer Schlagvolumenindex Durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-schlagvolumenindex-durch-indikatorverd.md)  [SD MII ICU Linksventrikulaeres Schlagvolumen](StructureDefinition-sd-mii-icu-linksventrikulaeres-schlagvolumen.md)  [SD MII ICU Linksventrikulaeres Schlagvolumen Durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-schlagvolumen-durch-indikatorverduennung.md)  [SD MII ICU Pulmonalvaskulaerer Widerstandsindex](StructureDefinition-sd-mii-icu-pulmonalvaskulaerer-widerstandsindex.md)  [SD MII ICU Systemischer Vaskulaerer Widerstandsindex](StructureDefinition-sd-mii-icu-systemischer-vaskulaerer-widerstandsindex.md)  [SD MII ICU Linksventrikulaerer Herzindex](StructureDefinition-sd-mii-icu-linksventrikulaerer-herzindex.md)  [SD MII ICU Herzzeitvolumen](StructureDefinition-sd-mii-icu-herzzeitvolumen.md)  [SD MII ICU Linksventrikulaerer Herzindex durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-herzindex-durch-indikatorverduennung.md)  [SD MII ICU Linksventrikulaeres Herzzeitvolumen Durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-herzzeitvolumen-durch-indikatorverd.md)  [SD MII ICU Zentralvenoeser Blutdruck](StructureDefinition-sd-mii-icu-zentralvenoeser-blutdruck.md)  [SD MII ICU Linksatrialer Druck](StructureDefinition-sd-mii-icu-linksatrialer-druck.md)  [SD MII ICU Rechtsatrialer Druck](StructureDefinition-sd-mii-icu-rechtsatrialer-druck.md)  [SD MII ICU Rechtsventrikulaerer Druck](StructureDefinition-sd-mii-icu-rechtsventrikulaerer-druck.md)  [SD MII ICU Linksventrikulaerer Druck](StructureDefinition-sd-mii-icu-linksventrikulaerer-druck.md)  [SD MII ICU Pulmonalarterieller Blutdruck](StructureDefinition-sd-mii-icu-pulmonalarterieller-blutdruck.md)  [SD MII ICU Koerpertemperatur Brustwirbelsaeule](StructureDefinition-sd-mii-icu-koerpertemperatur-brustwirbelsaeule.md)  [SD MII ICU Koerpertemperatur Lendenwirbelsaeule](StructureDefinition-sd-mii-icu-koerpertemperatur-lendenwirbelsaeule.md)  [SD MII ICU Koerpertemperatur Halswirbelsaeule](StructureDefinition-sd-mii-icu-koerpertemperatur-halswirbelsaeule.md)  [SD MII ICU Koerpertemperatur Brust](StructureDefinition-sd-mii-icu-koerpertemperatur-brust.md)  [SD MII ICU Koerpertemperatur Myokard](StructureDefinition-sd-mii-icu-koerpertemperatur-myokard.md)  [SD MII ICU Koerpertemperatur Atemwege](StructureDefinition-sd-mii-icu-koerpertemperatur-atemwege.md)  [SD MII ICU Koerpertemperatur Blut](StructureDefinition-sd-mii-icu-koerpertemperatur-blut.md)  [SD MII ICU Koerpertemperatur Nasen-Rachen-Raum](StructureDefinition-sd-mii-icu-koerpertemperatur-nasen-rachen-raum.md)  [SD MII ICU Koerpertemperatur Speiseroehre](StructureDefinition-sd-mii-icu-koerpertemperatur-speiseroehre.md) | **Y** | **Y** |  |  | _id, _tag, _count, _has, category, status, date, code, patient, subject, encounter, combo-code, combo-code-value-quantity, component-code |  |  |  |

-------

#### Resource Conformance: SHALL Observation

Core FHIR Resource

[Observation](http://hl7.org/fhir/R4/observation.html)

Reference Policy

Interaction summary

* **SHALL** support `read`, `search-type`.

Supported Profiles
[SD MII ICU Pulmonalarterieller Wedge Druck](StructureDefinition-sd-mii-icu-pulmonalarterieller-wedge-druck.md)
[SD MII ICU Sauerstoffsaettigung Im Blut Preduktal Durch Pulsoxymetrie](StructureDefinition-sd-mii-icu-o2saettigung-im-blut-preduktal-durch-pulsoxymetrie.md)
[SD MII ICU Sauerstoffsaettigung Im Blut Postduktal Durch Pulsoxymetrie](StructureDefinition-sd-mii-icu-o2saettigung-im-blut-postduktal-durch-pulsoxymetrie.md)
[SD MII ICU Linksventrikulaeres Schlagvolumenindex](StructureDefinition-sd-mii-icu-linksventrikulaeres-schlagvolumenindex.md)
[SD MII ICU Linksventrikulaerer Schlagvolumenindex Durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-schlagvolumenindex-durch-indikatorverd.md)
[SD MII ICU Linksventrikulaeres Schlagvolumen](StructureDefinition-sd-mii-icu-linksventrikulaeres-schlagvolumen.md)
[SD MII ICU Linksventrikulaeres Schlagvolumen Durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-schlagvolumen-durch-indikatorverduennung.md)
[SD MII ICU Pulmonalvaskulaerer Widerstandsindex](StructureDefinition-sd-mii-icu-pulmonalvaskulaerer-widerstandsindex.md)
[SD MII ICU Systemischer Vaskulaerer Widerstandsindex](StructureDefinition-sd-mii-icu-systemischer-vaskulaerer-widerstandsindex.md)
[SD MII ICU Linksventrikulaerer Herzindex](StructureDefinition-sd-mii-icu-linksventrikulaerer-herzindex.md)
[SD MII ICU Herzzeitvolumen](StructureDefinition-sd-mii-icu-herzzeitvolumen.md)
[SD MII ICU Linksventrikulaerer Herzindex durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-herzindex-durch-indikatorverduennung.md)
[SD MII ICU Linksventrikulaeres Herzzeitvolumen Durch Indikatorverduennung](StructureDefinition-sd-mii-icu-linksventri-herzzeitvolumen-durch-indikatorverd.md)
[SD MII ICU Zentralvenoeser Blutdruck](StructureDefinition-sd-mii-icu-zentralvenoeser-blutdruck.md)
[SD MII ICU Linksatrialer Druck](StructureDefinition-sd-mii-icu-linksatrialer-druck.md)
[SD MII ICU Rechtsatrialer Druck](StructureDefinition-sd-mii-icu-rechtsatrialer-druck.md)
[SD MII ICU Rechtsventrikulaerer Druck](StructureDefinition-sd-mii-icu-rechtsventrikulaerer-druck.md)
[SD MII ICU Linksventrikulaerer Druck](StructureDefinition-sd-mii-icu-linksventrikulaerer-druck.md)
[SD MII ICU Pulmonalarterieller Blutdruck](StructureDefinition-sd-mii-icu-pulmonalarterieller-blutdruck.md)
[SD MII ICU Koerpertemperatur Brustwirbelsaeule](StructureDefinition-sd-mii-icu-koerpertemperatur-brustwirbelsaeule.md)
[SD MII ICU Koerpertemperatur Lendenwirbelsaeule](StructureDefinition-sd-mii-icu-koerpertemperatur-lendenwirbelsaeule.md)
[SD MII ICU Koerpertemperatur Halswirbelsaeule](StructureDefinition-sd-mii-icu-koerpertemperatur-halswirbelsaeule.md)
[SD MII ICU Koerpertemperatur Brust](StructureDefinition-sd-mii-icu-koerpertemperatur-brust.md)
[SD MII ICU Koerpertemperatur Myokard](StructureDefinition-sd-mii-icu-koerpertemperatur-myokard.md)
[SD MII ICU Koerpertemperatur Atemwege](StructureDefinition-sd-mii-icu-koerpertemperatur-atemwege.md)
[SD MII ICU Koerpertemperatur Blut](StructureDefinition-sd-mii-icu-koerpertemperatur-blut.md)
[SD MII ICU Koerpertemperatur Nasen-Rachen-Raum](StructureDefinition-sd-mii-icu-koerpertemperatur-nasen-rachen-raum.md)
[SD MII ICU Koerpertemperatur Speiseroehre](StructureDefinition-sd-mii-icu-koerpertemperatur-speiseroehre.md)

Search Parameters


 



## Resource Content

```json
{
  "resourceType" : "CapabilityStatement",
  "id" : "ISiKCapabilityStatementVitalSignICUSourceExtendedRolle",
  "url" : "http://gefyra.info/training/CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceExtendedRolle",
  "version" : "0.1.0",
  "name" : "ISiKCapabilityStatementVitalSignICUSourceExtendedRolle",
  "title" : "ISiK CapabilityStatement VitalSign ICU Source Extended",
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
  "purpose" : "Das vorliegende CapabilityStatement beschreibt verpflichtende Interaktionen, die ein ISiK-konformes System oder eine Systemkomponente in der Rolle 'VitalSign ICU Source Extended' zur Unterstützung des ICU-Normalstation-Workflows implementieren muss.\n\nDie Interaktionen umfassen die Bereitstellung von Vitalparametern, die für die Behandlung von Intensivpatienten notwendig sind und sie z.B. typischerweise auf einer Intensivstation in einem PDMS erfasst werden.\n\n**HISTORIE:**   \n\n*Historie*: mit der Version 4.0.2 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement im Sinne einer eigenständigen Rolle extrahiert (die Funktionalität bleibt dabei unverändert).\n\n*Historie*: mit der Version 4.0.1 des IG ICU-Normalstation-Workflow wurde das vorliegende CapabilityStatement überarbeitet.\n\n",
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
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-pulmonalarterieller-wedge-druck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-o2saettigung-im-blut-preduktal-durch-pulsoxymetrie",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-o2saettigung-im-blut-postduktal-durch-pulsoxymetrie",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaeres-schlagvolumenindex",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-schlagvolumenindex-durch-indikatorverd",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaeres-schlagvolumen",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-schlagvolumen-durch-indikatorverduennung",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-pulmonalvaskulaerer-widerstandsindex",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-systemischer-vaskulaerer-widerstandsindex",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaerer-herzindex",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-herzzeitvolumen",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-herzindex-durch-indikatorverduennung",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-herzzeitvolumen-durch-indikatorverd",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-zentralvenoeser-blutdruck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksatrialer-druck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-rechtsatrialer-druck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-rechtsventrikulaerer-druck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaerer-druck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-pulmonalarterieller-blutdruck",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-brustwirbelsaeule",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-lendenwirbelsaeule",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-halswirbelsaeule",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-brust",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-myokard",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-atemwege",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-blut",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-nasen-rachen-raum",
            "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-speiseroehre"
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
