# ISiK CapabilityStatement Imports Expectation - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK CapabilityStatement Imports Expectation**

## Extension: ISiK CapabilityStatement Imports Expectation 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ExtensionISiKCapabilityStatementImportsExpectation |

Defines the level of expectation associated with a given system capability. See the capabilitystatement-prohibited modifier extension to set expectations to **not** support a feature.

**Context of Use**

**Usage info**

**Usages:**

* Examples for this Extension: [ISiKCapabilityStatementAMTSAkteur](CapabilityStatement-ISiKCapabilityStatementAMTSAkteur.md), [ISiK-CapabilityStatementBasisServerAkteur](CapabilityStatement-ISiKCapabilityStatementBasisServerAkteur.md), [ISiKCapabilityStatementDokumentenServerAkteur](CapabilityStatement-ISiKCapabilityStatementDokumentenServerAkteur.md), [ISiKCapabilityStatementMedikationInformationAkteur](CapabilityStatement-ISiKCapabilityStatementMedikationInformationAkteur.md)...Show 7 more,[ISiKCapabilityStatementMedikationVerabreichungMedikationsinformationAkteur](CapabilityStatement-ISiKCapabilityStatementMedikationVerabreichungAkteur.md),[ISiKCapabilityStatementMedikationVerordnungAkteur](CapabilityStatement-ISiKCapabilityStatementMedikationVerordnungAkteur.md),[ISiK-CapabilityStatementSubscriptionServerAkteur](CapabilityStatement-ISiKCapabilityStatementSubscriptionServerAkteur.md),[ISiKCapabilityStatementTerminRepositoryAkteur](CapabilityStatement-ISiKCapabilityStatementTerminRepositoryAkteur.md),[ISiKCapabilityStatementVitalSignICUSourceExtendedAkteur](CapabilityStatement-ISiKCapabilityStatementVitalSignICUSourceExtendedAkteur.md),[ISiKCapabilityStatementVitalSignICUSourceMinimalAkteur](CapabilityStatement-ISiKCapabilityStatementVitalSignICUSourceMinimalAkteur.md)and[ISiKCapabilityStatementVitalSignStandardSourceAkteur](CapabilityStatement-ISiKCapabilityStatementVitalSignStandardSourceAkteur.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation)

### Formal Views of Extension Content

 [Description of Profiles, Differentials, Snapshots, and how the XML and JSON presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ExtensionISiKCapabilityStatementImportsExpectation.csv), [Excel](StructureDefinition-ExtensionISiKCapabilityStatementImportsExpectation.xlsx), [Schematron](StructureDefinition-ExtensionISiKCapabilityStatementImportsExpectation.sch) 

#### Terminology Bindings

#### Constraints



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ExtensionISiKCapabilityStatementImportsExpectation",
  "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation",
  "version" : "0.1.0",
  "name" : "ExtensionISiKCapabilityStatementImportsExpectation",
  "title" : "ISiK CapabilityStatement Imports Expectation",
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
  "description" : "Defines the level of expectation associated with a given system capability. See the capabilitystatement-prohibited modifier extension to set expectations to *not* support a feature.",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    }
  ],
  "kind" : "complex-type",
  "abstract" : false,
  "context" : [
    {
      "type" : "element",
      "expression" : "CapabilityStatement.imports"
    }
  ],
  "type" : "Extension",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Extension",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Extension",
        "path" : "Extension",
        "short" : "SHALL | SHOULD | MAY |SHOULD-NOT",
        "definition" : "Defines the level of expectation associated with a given system capability.",
        "comment" : "If \"SHALL NOT\" is desired, use the \"prohibited\" modifier extension.  This extension should only be used with CapabilityStatements documenting requirements, not those documenting actual system capabilities."
      },
      {
        "id" : "Extension.extension",
        "path" : "Extension.extension",
        "max" : "0"
      },
      {
        "id" : "Extension.url",
        "path" : "Extension.url",
        "fixedUri" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation"
      },
      {
        "id" : "Extension.value[x]",
        "path" : "Extension.value[x]",
        "min" : 1,
        "type" : [
          {
            "code" : "code"
          }
        ],
        "binding" : {
          "extension" : [
            {
              "url" : "http://hl7.org/fhir/StructureDefinition/elementdefinition-bindingName",
              "valueString" : "ConformanceExpectation"
            }
          ],
          "strength" : "required",
          "description" : "Indicates the degree of adherence to a specified behavior or capability expected for a system to be deemed conformant with a specification.",
          "valueSet" : "http://terminology.hl7.org/ValueSet/conformance-expectation"
        }
      }
    ]
  }
}

```
