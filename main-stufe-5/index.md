# Home - v0.1.0

* [**Table of Contents**](toc.md)
* **Home**

## Home

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ImplementationGuide/info.gefyra.training | *Version*:0.1.0 |
| Active as of 2025-11-18 | *Computable Name*:SchulungsIG |

# ISiK IG Publisher Test

Feel free to modify this index page with your own awesome content!



## Resource Content

```json
{
  "resourceType" : "ImplementationGuide",
  "id" : "info.gefyra.training",
  "url" : "http://gefyra.info/training/ImplementationGuide/info.gefyra.training",
  "version" : "0.1.0",
  "name" : "SchulungsIG",
  "status" : "active",
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
  "packageId" : "info.gefyra.training",
  "license" : "CC0-1.0",
  "fhirVersion" : ["4.0.1"],
  "dependsOn" : [
    {
      "id" : "hl7tx",
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/implementationguide-dependency-comment",
          "valueMarkdown" : "Automatically added as a dependency - all IGs depend on HL7 Terminology"
        }
      ],
      "uri" : "http://terminology.hl7.org/ImplementationGuide/hl7.terminology",
      "packageId" : "hl7.terminology.r4",
      "version" : "7.0.0"
    },
    {
      "id" : "hl7ext",
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/implementationguide-dependency-comment",
          "valueMarkdown" : "Automatically added as a dependency - all IGs depend on the HL7 Extension Pack"
        }
      ],
      "uri" : "http://hl7.org/fhir/extensions/ImplementationGuide/hl7.fhir.uv.extensions",
      "packageId" : "hl7.fhir.uv.extensions.r4",
      "version" : "5.2.0"
    },
    {
      "id" : "hl7_fhir_uv_ips",
      "uri" : "http://hl7.org/fhir/uv/ips/ImplementationGuide/hl7.fhir.uv.ips",
      "packageId" : "hl7.fhir.uv.ips",
      "version" : "1.1.0"
    },
    {
      "id" : "hl7_fhir_uv_subscriptions_backport_r4",
      "uri" : "http://hl7.org/fhir/uv/subscriptions-backport/ImplementationGuide/hl7.fhir.uv.subscriptions-backport",
      "packageId" : "hl7.fhir.uv.subscriptions-backport.r4",
      "version" : "1.1.0"
    },
    {
      "id" : "de_basisprofil_r4",
      "uri" : "http://fhir.org/packages/de.basisprofil.r4/ImplementationGuide/de.basisprofil.r4",
      "packageId" : "de.basisprofil.r4",
      "version" : "1.5.4"
    },
    {
      "id" : "de_ihe_d_terminology",
      "uri" : "http://fhir.de/packages/de.ihe-d.terminology",
      "packageId" : "de.ihe-d.terminology",
      "version" : "3.0.1"
    },
    {
      "id" : "dvmd_kdl_r4",
      "uri" : "http://fhir.org/packages/dvmd.kdl.r4/ImplementationGuide/dvmd.kdl.r4",
      "packageId" : "dvmd.kdl.r4",
      "version" : "2025.0.1"
    },
    {
      "id" : "ihe_formatcode_fhir",
      "uri" : "https://profiles.ihe.net/fhir/ihe.formatcode.fhir/ImplementationGuide/ihe.formatcode.fhir",
      "packageId" : "ihe.formatcode.fhir",
      "version" : "1.4.0"
    },
    {
      "id" : "hl7_fhir_uv_sdc",
      "uri" : "http://hl7.org/fhir/uv/sdc/ImplementationGuide/hl7.fhir.uv.sdc",
      "packageId" : "hl7.fhir.uv.sdc",
      "version" : "3.0.0"
    },
    {
      "id" : "de_gematik_terminology",
      "uri" : "https://gematik.de/fhir/terminology/ImplementationGuide/de.gematik.terminology",
      "packageId" : "de.gematik.terminology",
      "version" : "1.0.6"
    },
    {
      "id" : "de_fhir_medication",
      "uri" : "http://ig.fhir.de/igs/medication/ImplementationGuide/de.fhir.medication",
      "packageId" : "de.fhir.medication",
      "version" : "1.0.1"
    },
    {
      "id" : "de_gematik_ti",
      "uri" : "https://gematik.de/fhir/ti/ImplementationGuide/de.gematik.ti",
      "packageId" : "de.gematik.ti",
      "version" : "1.1.1"
    }
  ],
  "definition" : {
    "extension" : [
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "copyrightyear"
          },
          {
            "url" : "value",
            "valueString" : "2025+"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "releaselabel"
          },
          {
            "url" : "value",
            "valueString" : "ci-build"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "no-validate"
          },
          {
            "url" : "value",
            "valueString" : "*/*"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "autoload-resources"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-liquid"
          },
          {
            "url" : "value",
            "valueString" : "template/liquid"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-liquid"
          },
          {
            "url" : "value",
            "valueString" : "input/liquid"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-qa"
          },
          {
            "url" : "value",
            "valueString" : "temp/qa"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-temp"
          },
          {
            "url" : "value",
            "valueString" : "temp/pages"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-output"
          },
          {
            "url" : "value",
            "valueString" : "output"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-suppressed-warnings"
          },
          {
            "url" : "value",
            "valueString" : "input/ignoreWarnings.txt"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "path-history"
          },
          {
            "url" : "value",
            "valueString" : "http://gefyra.info/training/history.html"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "template-html"
          },
          {
            "url" : "value",
            "valueString" : "template-page.html"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "template-md"
          },
          {
            "url" : "value",
            "valueString" : "template-page-md.html"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-contact"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-context"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-copyright"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-jurisdiction"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-license"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-publisher"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-version"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "apply-wg"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "active-tables"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "fmm-definition"
          },
          {
            "url" : "value",
            "valueString" : "http://hl7.org/fhir/versions.html#maturity"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "propagate-status"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "excludelogbinaryformat"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueString" : "tabbed-snapshots"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-internal-dependency",
        "valueCode" : "hl7.fhir.uv.tools.r4#0.8.0"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "copyrightyear"
          },
          {
            "url" : "value",
            "valueString" : "2025+"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "releaselabel"
          },
          {
            "url" : "value",
            "valueString" : "ci-build"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "no-validate"
          },
          {
            "url" : "value",
            "valueString" : "*/*"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "autoload-resources"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-liquid"
          },
          {
            "url" : "value",
            "valueString" : "template/liquid"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-liquid"
          },
          {
            "url" : "value",
            "valueString" : "input/liquid"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-qa"
          },
          {
            "url" : "value",
            "valueString" : "temp/qa"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-temp"
          },
          {
            "url" : "value",
            "valueString" : "temp/pages"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-output"
          },
          {
            "url" : "value",
            "valueString" : "output"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-suppressed-warnings"
          },
          {
            "url" : "value",
            "valueString" : "input/ignoreWarnings.txt"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "path-history"
          },
          {
            "url" : "value",
            "valueString" : "http://gefyra.info/training/history.html"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "template-html"
          },
          {
            "url" : "value",
            "valueString" : "template-page.html"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "template-md"
          },
          {
            "url" : "value",
            "valueString" : "template-page-md.html"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-contact"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-context"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-copyright"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-jurisdiction"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-license"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-publisher"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-version"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "apply-wg"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "active-tables"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "fmm-definition"
          },
          {
            "url" : "value",
            "valueString" : "http://hl7.org/fhir/versions.html#maturity"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "propagate-status"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "excludelogbinaryformat"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      },
      {
        "extension" : [
          {
            "url" : "code",
            "valueCode" : "tabbed-snapshots"
          },
          {
            "url" : "value",
            "valueString" : "true"
          }
        ],
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
      }
    ],
    "resource" : [
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Account"
          }
        ],
        "reference" : {
          "reference" : "Account/AbrechnungsfallDRG"
        },
        "name" : "AbrechnungsfallDRG",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAbrechnungsfall"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Account"
          }
        ],
        "reference" : {
          "reference" : "Account/AbrechnungsfallGonarthrose"
        },
        "name" : "AbrechnungsfallGonarthrose",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAbrechnungsfall"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Organization"
          }
        ],
        "reference" : {
          "reference" : "Organization/AbteilungAllgemeinchirurgieOrganisationBeispiel"
        },
        "name" : "AbteilungAllgemeinchirurgieOrganisationBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKOrganisationFachabteilung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementBasisServerAkteur"
        },
        "name" : "Akteur &quot;ISiKCapabilityStatementBasisServerAkteur&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementSubscriptionServerAkteur"
        },
        "name" : "Akteur &quot;ISiKCapabilityStatementSubscriptionServerAkteur&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/AltersbedingteKreislaufstoerung"
        },
        "name" : "AltersbedingteKreislaufstoerung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Procedure"
          }
        ],
        "reference" : {
          "reference" : "Procedure/Appendektomie"
        },
        "name" : "Appendektomie",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKProzedur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/AppointmentReplaces"
        },
        "name" : "AppointmentReplaces",
        "description" : "Mit dieser Erweiterung kann eine neue Appointment-Ressource auf eine frühere, ersetzte Appointment-Ressource verweisen, z. B. bei einer Terminverschiebung oder -umbuchung. Dies erleichtert die Nachverfolgung von Terminänderungen und stellt sicher, dass der Zusammenhang zwischen ursprünglichem und aktuellem Termin eindeutig dokumentiert ist.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKFormularDaten"
        },
        "name" : "Ausgefülltes ISiK-Formular",
        "description" : "Im Profil `ISiKFormularDaten` sind Mindestanforderungen an ISiK kompatible, ausgefüllte Formulare definiert.\nDie verwendbaren Extensions sind nicht mit profiliert, sondern im IG unter [Artefakte->Extensions](https://simplifier.net/guide/isik-formular-stufe-5/Einfuehrung/Artefakte/Extensions.page.md?version=current) beschrieben.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExampleConditionalItem"
        },
        "name" : "Bedingte Fragestellungen",
        "description" : "### Beispiel-Questionnaire mit bedingten Fragestellungen/Items  \nDie zweite Frage &quot;Was ist denn los?&quot; soll nur gestellt werden, \nwenn die erste Frage &quot;Wie geht's&quot; mit &quot;muss.&quot; beantwortet wurde.",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/BehandlungsDiagnoseFreitext"
        },
        "name" : "BehandlungsDiagnoseFreitext",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Location"
          }
        ],
        "reference" : {
          "reference" : "Location/BettenstellplatzStandortBeispiel"
        },
        "name" : "BettenstellplatzStandortBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKStandortBettenstellplatz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Binary"
          }
        ],
        "reference" : {
          "reference" : "Binary/Binary-JPEG-Example"
        },
        "name" : "Binary-JPEG-Example",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Binary"
          }
        ],
        "reference" : {
          "reference" : "Binary/Binary-JPEG-Example-short"
        },
        "name" : "Binary-JPEG-Example-short",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Binary"
          }
        ],
        "reference" : {
          "reference" : "Binary/Binary-PDF-Example"
        },
        "name" : "Binary-PDF-Example",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Binary"
          }
        ],
        "reference" : {
          "reference" : "Binary/Binary-PDF-Example-short"
        },
        "name" : "Binary-PDF-Example-short",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Composition"
          }
        ],
        "reference" : {
          "reference" : "Composition/CompositionExampleBlutdruck"
        },
        "name" : "Blutdruckmessung vom 3.5.2022",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKBerichtSubSysteme"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "OperationDefinition"
          }
        ],
        "reference" : {
          "reference" : "OperationDefinition/ISiKAppointmentBookOperation"
        },
        "name" : "Book",
        "description" : "OperationDefinition für die Buchung eines Termins. Die Operation überprüft ob der Termin noch verfügbar ist im Termin-Repository.",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/ISiKBundle-Example"
        },
        "name" : "Bundle-Beispiel-Blutdruck",
        "description" : "Beispiel für ein Bundle mit Composition Blutdruck, das folgende User Story repräsentiert: Die Patientin von Musterfrau war vom 3. bis 5. Mai 2022 als stationärer Fall anlässlich einer geplanten Operation im Krankenhaus. Dabei wurde am 3. Mai der Blutdruck gemessen und das Ergebnis in einem Peripheriesystem vermerkt. Das Peripheriesystem sendet das Messergebnis an das KIS, so dass das KIS dieses in die Gesamtdokumentation zur Patientin aufnehmen kann.",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKBerichtBundle"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementAufbaustrukturRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;AufbaustrukturRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementCompositionKonsumentenRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;ISiKCapabilityStatementCompositionKonsumentenRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementErweiterteStammdatenRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;ISiKCapabilityStatementErweiterteStammdatenRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementGesundheitsstatusRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;ISiKCapabilityStatementGesundheitsstatusRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementKlinischeRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;ISiKCapabilityStatementKlinischeRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementTerminologieRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;ISiKCapabilityStatementTerminologieRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVersicherungsverhaeltnisRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;ISiKCapabilityStatementVersicherungsverhaeltnisRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementLeistungserbringerRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;LeistungserbringerRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementStammdatenRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;StammdatenRolle&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementSubscriptionRolle"
        },
        "name" : "CapabilityStatement für Rolle &quot;Subscription&quot;",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/CodeSystemExample"
        },
        "name" : "CodeSystemExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKCodeSystem"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ConditionDiagnosisSeverity"
        },
        "name" : "ConditionDiagnosisSeverity",
        "description" : "Enthaelt alle SNOMED DiagnosisSeverity Codes",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Coverage"
          }
        ],
        "reference" : {
          "reference" : "Coverage/CoverageGesetzlich"
        },
        "name" : "CoverageGesetzlich",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisGesetzlich"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Coverage"
          }
        ],
        "reference" : {
          "reference" : "Coverage/CoveragePrivat"
        },
        "name" : "CoveragePrivat",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisSelbstzahler"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Coverage"
          }
        ],
        "reference" : {
          "reference" : "Coverage/CoverageSonstige"
        },
        "name" : "CoverageSonstige",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisSonstige"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/current-smoking-status-uv-ips"
        },
        "name" : "Current Smoking Status - IPS",
        "description" : "HL7 LOINC value set for smoking status.  Based on the HL7 Vocab and Structured Doc WG (formerly TC) consensus - per US CDC submission 7/12/2012 for smoking status terms.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/DiagnosesSCT"
        },
        "name" : "DiagnosesSCT",
        "description" : "Enthaelt alle SNOMED Clinical finding, Event und Situation with explicit context codes",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "DocumentReference"
          }
        ],
        "reference" : {
          "reference" : "DocumentReference/dok-beispiel-server"
        },
        "name" : "dok-beispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenMetadaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "DocumentReference"
          }
        ],
        "reference" : {
          "reference" : "DocumentReference/dok-beispiel-client-with-binary-pdf-example-short"
        },
        "name" : "dok-beispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenMetadaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "DocumentReference"
          }
        ],
        "reference" : {
          "reference" : "DocumentReference/dok-beispiel-client-with-binary-jpeg-example-short"
        },
        "name" : "dok-beispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenMetadaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "DocumentReference"
          }
        ],
        "reference" : {
          "reference" : "DocumentReference/dok-beispiel-client-with-binary-jpeg-example"
        },
        "name" : "dok-beispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenMetadaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "DocumentReference"
          }
        ],
        "reference" : {
          "reference" : "DocumentReference/dok-beispiel-client-with-binary-pdf-example"
        },
        "name" : "dok-beispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenMetadaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/DorisQuelle"
        },
        "name" : "DorisQuelle",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/DorisZiel"
        },
        "name" : "DorisZiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "SearchParameter"
          }
        ],
        "reference" : {
          "reference" : "SearchParameter/Encounter-date-start"
        },
        "name" : "Encounter-date-start",
        "description" : "The actual start date of the Encounter (Backport from R5). The parameter cannot repeat or have multiple values.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "SearchParameter"
          }
        ],
        "reference" : {
          "reference" : "SearchParameter/Encounter-end-date"
        },
        "name" : "Encounter-end-date",
        "description" : "The actual end date of the Encounter (Backport from R5). The parameter cannot repeat or have multiple values.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/EncounterReasonCodes"
        },
        "name" : "EncounterReasonCodes",
        "description" : "Enthaelt alle SNOMED Reason Codes",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKDokumentenMetadaten"
        },
        "name" : "Erforderliche Metadaten für Dokumentenaustausch in ISiK",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Dokumentenmetadaten im Rahmen des Bestätigungsverfahrens der gematik.  \n\n  ### Motivation\nDie Ressource DocumentReference enthält die Metadaten, die für die Verwaltung von und die Suche nach Dokumenten benötigt werden. Der Inhalt des Dokumentes wird über DocumentReference.content beschrieben und über DocumentReference.content.attachment referenziert. Die Trennung von Dokument und Metadaten ermöglicht Clients die effiziente Suche und Auflistung von verfügbaren Dokumenten, ohne dass diese vollständig vom Server geladen werden müssen. Servern ermöglicht dieser Ansatz die Trennung zwischen den Metadaten in einer Datenbank und der Dokumentenablage in z.B. einem Dateisystem.\n\n  ### Kompatibilität\nDieses Profil basiert auf dem Profil [MHD DocumentReference Comprehensive UnContained References Option](https://profiles.ihe.net/ITI/MHD/StructureDefinition-IHE.MHD.UnContained.Comprehensive.DocumentReference.html) (Version 4.2.0) von IHE International.\n\n  #### Abweichungen vom IHE-Profil\n- Die Verwendung von `DocumentReference.docStatus` ist im ISiK-Kontext gestattet.\n- `DocumentReference.category` muss vom Client bei Vorhandensein eines KDL-Codes in `DocumentReference.type` nicht gefüllt werden. Bei der Verarbeitung auf dem Server im Rahmen der Interaktion {{pagelink: Dokumentenbereitstellung}} wird `DocumentReference.category` anhand der [KDL-Mappings](https://simplifier.net/kdl/%7Eresources?category=ConceptMap&sortBy=RankScore_desc) ergänzt und damit die IHE-Kompatibilität hergestellt.\n- `DocumentReference.sourcePatientInfo` muss im Rahmen von ISiK nicht gefüllt werden\n\n#### Einschränkungen des IHE-Profils\nElemente mit ValueSet-Bindings ohne verbindliche Vorgabe seitens IHE wurden auf die in Deutschland gebräuchlichen Terminologien (gemäß der Festlegungen von IHE Deutschland e.V.) eingeschränkt.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/Example-condition-ausrufezeichen-primaer"
        },
        "name" : "Example-condition-ausrufezeichen-primaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/Example-condition-ausrufezeichen-sekundaer"
        },
        "name" : "Example-condition-ausrufezeichen-sekundaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/Example-condition-kreuz-stern-primaer"
        },
        "name" : "Example-condition-kreuz-stern-primaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/Example-condition-kreuz-stern-sekundaer"
        },
        "name" : "Example-condition-kreuz-stern-sekundaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Device"
          }
        ],
        "reference" : {
          "reference" : "Device/ExampleDevice"
        },
        "name" : "ExampleDevice",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "QuestionnaireResponse"
          }
        ],
        "reference" : {
          "reference" : "QuestionnaireResponse/ExampleEntryValidationDecimalResponse"
        },
        "name" : "ExampleEntryValidationDecimalResponse",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "QuestionnaireResponse"
          }
        ],
        "reference" : {
          "reference" : "QuestionnaireResponse/ExampleExtractWithUnitResponse"
        },
        "name" : "ExampleExtractWithUnitResponse",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "RiskAssessment"
          }
        ],
        "reference" : {
          "reference" : "RiskAssessment/ExampleISiKAMTSBewertung1"
        },
        "name" : "ExampleISiKAMTSBewertung1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAMTSBewertung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungCRP1"
        },
        "name" : "ExampleISiKLaboruntersuchungCRP1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungCRP"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungGFR1"
        },
        "name" : "ExampleISiKLaboruntersuchungGFR1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungGFR"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungHb1"
        },
        "name" : "ExampleISiKLaboruntersuchungHb1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungHb"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungPCT1"
        },
        "name" : "ExampleISiKLaboruntersuchungPCT1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungPCT"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungSerumkreatinin1"
        },
        "name" : "ExampleISiKLaboruntersuchungSerumkreatinin1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungSerumkreatinin"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungThrombozyten1"
        },
        "name" : "ExampleISiKLaboruntersuchungThrombozyten1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungThrombozyten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungTroponin1"
        },
        "name" : "ExampleISiKLaboruntersuchungTroponin1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungTroponin"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExampleISiKLaboruntersuchungTSH1"
        },
        "name" : "ExampleISiKLaboruntersuchungTSH1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKLaboruntersuchungTSH"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament1"
        },
        "name" : "ExampleISiKMedikament1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament2"
        },
        "name" : "ExampleISiKMedikament2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament3"
        },
        "name" : "ExampleISiKMedikament3",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament4"
        },
        "name" : "ExampleISiKMedikament4",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament5"
        },
        "name" : "ExampleISiKMedikament5",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament6"
        },
        "name" : "ExampleISiKMedikament6",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament7"
        },
        "name" : "ExampleISiKMedikament7",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament8"
        },
        "name" : "ExampleISiKMedikament8",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ExampleISiKMedikament9"
        },
        "name" : "ExampleISiKMedikament9",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformation1"
        },
        "name" : "ExampleISiKMedikationsInformation1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformation2"
        },
        "name" : "ExampleISiKMedikationsInformation2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformation3"
        },
        "name" : "ExampleISiKMedikationsInformation3",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformation4"
        },
        "name" : "ExampleISiKMedikationsInformation4",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformation5"
        },
        "name" : "ExampleISiKMedikationsInformation5",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformation6"
        },
        "name" : "ExampleISiKMedikationsInformation6",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformationParkinson1"
        },
        "name" : "ExampleISiKMedikationsInformationParkinson1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformationParkinson2"
        },
        "name" : "ExampleISiKMedikationsInformationParkinson2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformationParkinson3"
        },
        "name" : "ExampleISiKMedikationsInformationParkinson3",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformationParkinson4"
        },
        "name" : "ExampleISiKMedikationsInformationParkinson4",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationStatement"
          }
        ],
        "reference" : {
          "reference" : "MedicationStatement/ExampleISiKMedikationsInformationParkinson5"
        },
        "name" : "ExampleISiKMedikationsInformationParkinson5",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "List"
          }
        ],
        "reference" : {
          "reference" : "List/ExampleISiKMedikationsListe"
        },
        "name" : "ExampleISiKMedikationsListe",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsListe"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "List"
          }
        ],
        "reference" : {
          "reference" : "List/ExampleISiKMedikationsListeParkinson"
        },
        "name" : "ExampleISiKMedikationsListeParkinson",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsListe"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationAdministration"
          }
        ],
        "reference" : {
          "reference" : "MedicationAdministration/ExampleISiKMedikationsVerabreichung"
        },
        "name" : "ExampleISiKMedikationsVerabreichung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerabreichung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationAdministration"
          }
        ],
        "reference" : {
          "reference" : "MedicationAdministration/ExampleISiKMedikationsVerabreichung2"
        },
        "name" : "ExampleISiKMedikationsVerabreichung2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerabreichung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationAdministration"
          }
        ],
        "reference" : {
          "reference" : "MedicationAdministration/ExampleISiKMedikationsVerabreichung3"
        },
        "name" : "ExampleISiKMedikationsVerabreichung3",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerabreichung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationAdministration"
          }
        ],
        "reference" : {
          "reference" : "MedicationAdministration/ExampleISiKMedikationsVerabreichung4"
        },
        "name" : "ExampleISiKMedikationsVerabreichung4",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerabreichung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationRequest"
          }
        ],
        "reference" : {
          "reference" : "MedicationRequest/ExampleISiKMedikationsVerordnung"
        },
        "name" : "ExampleISiKMedikationsVerordnung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerordnung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "MedicationRequest"
          }
        ],
        "reference" : {
          "reference" : "MedicationRequest/ExampleISiKMedikationsVerordnung2"
        },
        "name" : "ExampleISiKMedikationsVerordnung2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerordnung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/ExampleISiKMedikationTransaction"
        },
        "name" : "ExampleISiKMedikationTransaction",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationTransaction"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/ExampleISiKMedikationTransactionResponse"
        },
        "name" : "ExampleISiKMedikationTransactionResponse",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationTransactionResponse"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKRehaEntlassung"
        },
        "name" : "ExtensionISiKRehaEntlassung",
        "description" : "Extension zur Dokumentation von Informationen nach §301 (4 und 4a) SGB V, entsprechend dem ärztliche Reha-Entlassungsbericht. Mit dieser Extension können spezifische Entlassungsinformationen im Kontext einer Rehabilitationsmaßnahme angegeben werden. Dies ist besonders relevant für Einrichtungen, die Leistungen im Bereich Rehabilitation erbringen, und unterstützt die strukturierte Kommunikation im Entlassmanagement.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExtractedObservationKoerpergewicht"
        },
        "name" : "ExtractedObservationKoerpergewicht",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergewicht"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ExtractedObservationKoerpergroesse"
        },
        "name" : "ExtractedObservationKoerpergroesse",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergroesse"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/Fachabteilungskontakt"
        },
        "name" : "Fachabteilungskontakt",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktBettenverlegung"
        },
        "name" : "FachabteilungskontaktBettenverlegung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktEntlassung"
        },
        "name" : "FachabteilungskontaktEntlassung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktFachbereichswechsel1"
        },
        "name" : "FachabteilungskontaktFachbereichswechsel1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktFachbereichswechsel2"
        },
        "name" : "FachabteilungskontaktFachbereichswechsel2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktMinimal"
        },
        "name" : "FachabteilungskontaktMinimal",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktMinimal2"
        },
        "name" : "FachabteilungskontaktMinimal2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktNormal"
        },
        "name" : "FachabteilungskontaktNormal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktStationaereAufnahme"
        },
        "name" : "FachabteilungskontaktStationaereAufnahme",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktStationswechsel1"
        },
        "name" : "FachabteilungskontaktStationswechsel1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/FachabteilungskontaktStationswechsel2"
        },
        "name" : "FachabteilungskontaktStationswechsel2",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/FhirMimeTypeVS"
        },
        "name" : "FhirMimeTypeVS",
        "description" : "FHIR Mime Types",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExampleMdrRelevant"
        },
        "name" : "Formular aus einem Medizinprodukt",
        "description" : "### Beispiel-Questionnaire, welches eine MDR-Relevanz ausweist\n* Angabe der MDR-Relevanz mittels [ISiKMDRRelevanzFormular](https://simplifier.net/isik-stufe-5/isikmdrrelevanzformularextension)-Extension\nDisclaimer: Dies ist ein simples fantasie Beispiel und hat keine medizinische Aussagekraft. Das erwartete Verhalten von Systemen, die mit diesem Questionnaire testen wäre, dass das Formular mit einer Fehlermeldung *nicht* rendert!",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Herzzeitvolumen"
        },
        "name" : "Herzzeitvolumen",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-herzzeitvolumen"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Ideales-Koerpergewicht"
        },
        "name" : "Ideales-Koerpergewicht",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-ideales-koerpergewicht"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Intrakranieller-Druck-ICP"
        },
        "name" : "Intrakranieller-Druck-ICP",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-intrakranieller-druck-icp"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKKernTempSctVS"
        },
        "name" : "ISiK  Kerntemperatur SnomedCT ValueSet",
        "description" : "ValueSet der Körperkerntemperatur SnomedCT Konzepte",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKAcceptedRisk"
        },
        "name" : "ISiK Accepted Risk",
        "description" : "Extension zur Dokumentation eines im Rahmen der AMTS bewusst eingegangenen Risikos. In diesem Freitext kann die Begründung und ggf. zu treffende besondere Maßnahmen dokumentiert werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKAlkoholAbusus"
        },
        "name" : "ISiK Alkohol Abusus",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKAMTSBewertung"
        },
        "name" : "ISiK AMTS-Bewertung",
        "description" : "Dieses Profil ermöglicht die Abbildung von Informationen zur Risikobeurteilung im Rahmen der Arzneimitteltherapiesicherheit (AMTS).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKBehandlungsziel"
        },
        "name" : "ISiK Behandlungsziel",
        "description" : "Mit dieser Erweiterung kann das mit einer Medikation angestrebte Behandlungsziel ausführlich dokumentiert werden (z. B. Symptomkontrolle, Heilung, Prävention). Dies unterstützt die individuelle Therapieplanung, die Erfolgskontrolle und die Kommunikation zwischen verschiedenen Leistungserbringern.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementAMTSAkteur"
        },
        "name" : "ISiK CapabilityStatement AMTS Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementAMTSRolle"
        },
        "name" : "ISiK CapabilityStatement AMTS Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementDokumentenServerAkteur"
        },
        "name" : "ISiK CapabilityStatement Dokumenten Server Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementDokumentenverwaltungRolle"
        },
        "name" : "ISiK CapabilityStatement Dokumentenverwaltung Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation"
        },
        "name" : "ISiK CapabilityStatement Imports Expectation",
        "description" : "Defines the level of expectation associated with a given system capability. See the capabilitystatement-prohibited modifier extension to set expectations to *not* support a feature.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementLaborMinimalRolle"
        },
        "name" : "ISiK CapabilityStatement Labor Minimal Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikamentRolle"
        },
        "name" : "ISiK CapabilityStatement MedikamentRolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikationInformationRolle"
        },
        "name" : "ISiK CapabilityStatement Medikation Server - Medikationsinformation",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikationInformationAkteur"
        },
        "name" : "ISiK CapabilityStatement Medikationsinformation Server Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikationVerabreichungRolle"
        },
        "name" : "ISiK CapabilityStatement Medikationsverabreichung Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikationVerabreichungAkteur"
        },
        "name" : "ISiK CapabilityStatement Medikationsverabreichung Server Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikationVerordnungRolle"
        },
        "name" : "ISiK CapabilityStatement Medikationsverordnung Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMedikationVerordnungAkteur"
        },
        "name" : "ISiK CapabilityStatement Medikationsverordnung Server Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMetadatenErzeugenRolle"
        },
        "name" : "ISiK CapabilityStatement Metadaten Erzeugen Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementMetadatenUpdateRolle"
        },
        "name" : "ISiK CapabilityStatement Metadaten Update Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementTerminRepositoryAkteur"
        },
        "name" : "ISiK CapabilityStatement Termin-Repository Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementTerminRepositoryRolle"
        },
        "name" : "ISiK CapabilityStatement Termin-Repository Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVitalSignStandardSourceAkteur"
        },
        "name" : "ISiK CapabilityStatement Vital Sign Standard Source Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceExtendedAkteur"
        },
        "name" : "ISiK CapabilityStatement Vitalparameter Server Extended",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceExtendedRolle"
        },
        "name" : "ISiK CapabilityStatement VitalSign ICU Source Extended",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceMinimalAkteur"
        },
        "name" : "ISiK CapabilityStatement VitalSign ICU Source Minimal Akteur",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diesen Akteur implementiert.   \n\n  Jede Instanz eines bestätigungsrelevanten Systems MUSS an ihrem Endpunkt eine CapabilityStatement-Ressource bereitstellen.\nHierzu MUSS die [capabilities-Interaktion gemäß FHIR-Kernspezifikation](https://hl7.org/fhir/R4/http.html#capabilities) unterstützt werden. \nDer `MODE`-Parameter kann ignoriert werden.  \nDas CapabilityStatement in dieser Spezifikation stellt die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Rollen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Imports-Expectation-Extension](https://gematik.de/fhir/isik/StructureDefinition/ExtensionISiKCapabilityStatementImportsExpectation) mit den möglichen Werten 'SHALL' (=MUSS)  'SHOULD' (=SOLL)  'MAY' (=KANN) 'SHOULD-NOT' (=SOLL NICHT) verwendet.  \n\nEine Server-Instanz MUSS ihrerseits ein CapabilityStatement vom `kind = instance` liefern und im Element `software` den Namen \nund die Versionsnummer angeben.   \nDarüber hinaus MÜSSEN in `CapabilityStatement.instantiates` sämtliche Canonical URLs der implementierten Rollen angegeben werden.\nDie mindestens zu implementierenden Profile für einen Akteur und Interaktionen entsprechen daher den aggregierten Anforderungen der einzelnen Rolle (per 'imports'). In den CapabilityStatements zu den Rollen sind die Anforderungen tabellarisch gelistet und weisen so die zu implementierenden Profile aus.\n\nDas CapabilityStatement der Instanz MUSS alle Funktionalitäten auflisten, die im folgenden CapabilityStatement (bzw. der in ihm importierten Rollen - siehe 'imports') mit `SHALL` gekennzeichnet sind. \nDas CapabilityStatement KANN darüber hinaus die mit `MAY` gekennzeichneten Funktionalitäten, sowie weitere Funktionalitäten auflisten, \nsofern diese in der Instanz implementiert wurden.  \n\nDie Verwendung der CapabilityStatement-Expectation-Extension ist im CapabilityStatement der Server-Instanz nicht erforderlich.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVitalSignICUSourceMinimalRolle"
        },
        "name" : "ISiK CapabilityStatement VitalSign ICU Source Minimal Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CapabilityStatement"
          }
        ],
        "reference" : {
          "reference" : "CapabilityStatement/ISiKCapabilityStatementVitalSignStandardSourceRolle"
        },
        "name" : "ISiK CapabilityStatement VitalSign Standard Source Rolle",
        "description" : "Dieses CapabilityStatement beschreibt alle Interaktionen, \n  die ein System unterstützen MUSS, welches diese Rolle implementiert.   \n  \nDie CapabilityStatements in dieser Spezifikation stellen die Anforderungen seitens der gematik dar (`kind = requirements`). \nZur Unterscheidung von Anforderungen, die erfüllt werden MÜSSEN gegenüber jenen, die erfüllt werden KÖNNEN, \nwird die [CapabilityStatement-Expectation-Extension](https://hl7.org/fhir/R4/extension-capabilitystatement-expectation.html) mit den möglichen Werten `SHALL` (=MUSS) und `MAY` (=KANN) verwendet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKMedicationRequestReplaces"
        },
        "name" : "ISiK MedicationRequestReplaces",
        "description" : "Extension zur Verlinkung der Medikationsverordnung die ersetzt wurde",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKMedicationStatementReplaces"
        },
        "name" : "ISiK MedicationStatementReplaces",
        "description" : "Mit dieser Erweiterung kann festgelegt werden, welche vorherige Medikation durch die aktuelle Verordnung ersetzt wird. Sie erleichtert die Nachverfolgung von Therapieänderungen, sorgt für Transparenz im Medikationsprozess.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikationTransaction"
        },
        "name" : "ISiK Medikation Transactionbundle",
        "description" : "Dieses Profil definiert die Transaktions-Bundles im Rahmen von ISiK-Medikations-Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikationTransactionResponse"
        },
        "name" : "ISiK Medikation TransactionBundle-Response",
        "description" : "Dieses Profil definiert die Server-Antwort auf Transaktions-Bundles im Rahmen von ISiK-Medikations-Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKMedikationsart"
        },
        "name" : "ISiK Medikationsart",
        "description" : "Diese Erweiterung ermöglicht die genaue Angabe der Art der Medikation, beispielsweise ob es sich um eine Dauermedikation, Bedarfsmedikation oder eine situative Medikation handelt. Dies trägt zur besseren Strukturierung von Medikationsplänen und zur eindeutigen Kommunikation über die Medikation bei.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKMedikationsartCS"
        },
        "name" : "ISiK Medikationsart",
        "description" : "ISiK Therapiearten für Medikation",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikationsListe"
        },
        "name" : "ISiK Medikationsliste",
        "description" : "Dieses Profil ermöglicht die Zusammenführung einzelner MedikationsInformationen eines Patienten in ISiK Szenarien.\n\nDie MedicationList verweist auf MedicationStatement-Ressourcen und bildet Medikationen ab, die aktuell eingenommen, im Krankenhaus verabreicht oder aus externen Quellen dokumentiert wurden - etwa durch Patientenangaben, Medikationspläne oder Entlassbriefe.\nIm Unterschied zum eMP der ePA ist die ISiK-MedikationsListe dynamisch generierbar und systemseitig aktualisierbar. Sie kann auch Informationen enthalten, die außerhalb des eigenen Hauses erfasst wurden – sofern diese dem System strukturiert vorliegen (z.B. durch eMP-Import).\nEin Import aus dem eMP ist möglich, aber nicht verpflichtend.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKRaucherStatus"
        },
        "name" : "ISiK Raucherstatus",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSchwangerschaftErwarteterEntbindungstermin"
        },
        "name" : "ISiK Schwangerschaft - Erwarteter Entbindungstermin",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSchwangerschaftsstatus"
        },
        "name" : "ISiK Schwangerschaftsstatus",
        "description" : "Schwangerschaftsstatus einer Patientin",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ExtensionISiKSelbstmedikation"
        },
        "name" : "ISiK Selbstmedikation",
        "description" : "Mit dieser Erweiterung kann kenntlich gemacht werden, ob ein Arzneimittel als Selbstmedikation (d. h. ohne ärztliche Verordnung) eingenommen wird. Sie trägt zur vollständigen Erfassung der aktuellen Medikation und zur Erhöhung der Therapiesicherheit bei.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKSpecificGenericTempLoincVS"
        },
        "name" : "ISiK Specific Generische Koerpertemperatur LOINC Konzepte",
        "description" : "ValueSet der spezifischen generischen Körperkerntemperatur LOINC Konzepte die nicht dazu dienen eine Körperkerntemperatur zu messen",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKSpecificKernTempLoincVS"
        },
        "name" : "ISiK Specific Kerntemperatur LOINC ValueSet",
        "description" : "ValueSet der spezifischen Körperkerntemperatur LOINC Konzepte",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSubscription"
        },
        "name" : "ISiK Subscription",
        "description" : "ISiK Subscription  \n### Motivation\n\nSubscription ist eine FHIR Ressource, um als Client-System Benachrichtigungen über Events auf dem FHIR Server anzufragen. Der Subscription Mechanismus in FHIR R4 ist nicht geeignet, um alle relevanten Events (hier im Speziellen das Mergen von Patienten) zu unterstützen. Daher basiert das ISiK Subscription-Profil auf dem [Subscriptions R5 Backport Profil von HL7](https://hl7.org/fhir/uv/subscriptions-backport/STU1.1/StructureDefinition-backport-subscription.html).\n\nUm als Subsystem über ein Subsription-Event informiert zu werden, KANN der FHIR Subscription Mechanismus gemäß des [Subscriptions R5 Backport IGs von HL7](https://hl7.org/fhir/uv/subscriptions-backport/STU1.1/index.html) genutzt werden.\n\n### Kompatibilität\n\nDas Profil ISiKSubscription basiert auf dem [Backport-Subscription Profil](https://hl7.org/fhir/uv/subscriptions-backport/StructureDefinition-backport-subscription.html).\nDer [SubscriptionStatus](https://hl7.org/fhir/uv/subscriptions-backport/StructureDefinition-backport-subscription-status-r4.html), sowie das [Subscription Notification Bundle](https://hl7.org/fhir/uv/subscriptions-backport/StructureDefinition-backport-subscription-notification-r4.html) werden unverändert direkt aus dem [Subscriptions R5 Backport IG](https://hl7.org/fhir/uv/subscriptions-backport/index.html) genutzt.  \n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSubscriptionStatus"
        },
        "name" : "ISiK Subscription Status",
        "description" : "ISiK Subscription Status",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKSubscriptionTopic"
        },
        "name" : "ISiK-SubscriptionTopic",
        "description" : "Liste der aller SubscriptionTopics, die in ISiK verwendet werden können. Neben den merge-SubscriptionTopics sind auch die SubscriptionTopics für Updates der Ressourcen enthalten, die in ISiK verwendet werden können.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKAbrechnungsfall"
        },
        "name" : "ISiKAbrechnungsfall",
        "description" : "Dieses Profil ermöglicht die Gruppierung von medizinischen Leistungen zu einem gemeinsamen Abrechnungskontext.  \nZugleich dient es im Kontext von ISiK derzeit im Wesentlichen der Abbildung einer Fallnummer, über die im Krankenhaus unterschiedliche Prozesse - auch administrativer Natur - abgewickelt werden. Das Profil wurde *nicht* primär zum Zweck der Abbildung von Abrechnungsprozessen definiert. \n\n### Motivation\nKomplementär zum Datenobjekt &quot;Kontakt - Encounter&quot; können Fälle, im Sinne einer Gruppierung von medizinischen Leistungen \ninnerhalb eines gemeinsamen Kontextes, zu einem Abrechnungsfall zusammengefasst werden.\nEin solcher Abrechnungsfall kann mehrere Kontakte umfassen (z.B. vorstationärer Besuch, stationärer Aufenthalt und nachstationärer Besuch).  \n\nGemeinsam mit dem Einrichtungskontakt bildet der Abrechnungsfall einen wichtigen Einstiegspunkt in die Dokumentation der Behandlungsleistungen der Patienten.\nAls Bindeglied zwischen den Kontakten und dem Versicherungsverhältnis erfolgt eine feingranulare Auflistung, \nin welchen Zeiträumen ein Behandlungskontext zwischen einer Gesundheitseinrichtung und der Patienten bestand.\nZudem werden Diagnosen abschließend / nachträglich dokumentiert, sodass eine Übersicht von relevanten (DRG)-Diagnosen ermöglicht wird, \nohne die Gesamtheit aller Kontakte betrachten zu müssen.\n\nIn FHIR wird der Abrechnungsfall mit der `Account`-Ressource repräsentiert.\n\nWeitere Hinweise zu den Abgrenzungen der Begrifflichkeiten Fall und Kontakt finden sie unter {{pagelink: Fall, text: Fall-Begriff in ISiK}}.\n\n### Kompatibilität\n* zum Zeitpunkt der Veröffentlichung sind keine abweichenden Modellierungen der Account-Ressource bekannt.\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKAccountType"
        },
        "name" : "ISiKAccountType",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKAlkoholAbususBeispiel"
        },
        "name" : "ISiKAlkoholAbususBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAlkoholAbusus"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKAllergieUnvertraeglichkeit"
        },
        "name" : "ISiKAllergieUnvertraeglichkeit",
        "description" : "\nDiese Profil ermöglicht die Dokumentation von Allergien und Unverträglichkeiten in ISiK Szenarien.\n### Motivation\n\nDie Möglichkeit, auf eine Übersicht der Allergien und Unverträglichkeiten eines Patienten zuzugreifen, ist eine wichtige Funktion im klinischen Behandlungsablauf. Dies gilt insbesondere, aber nicht ausschließlich, im Bereich der Arzneimitteltherapiesicherheit.\nMotivierender Use-Case zur Einführung dieser Profile ist die [Arzneitmitteltherapiesicherheit im Krankenhaus - AMTS](https://simplifier.net/guide/isik-medikation-v4/ImplementationGuide-markdown-UebergreifendeUseCases-AMTS).\n\nIn FHIR werden Allergien und Unverträglichkeiten mit der [AllergyIntolerance](https://hl7.org/fhir/R4/allergyintolerance.html)-Ressource repräsentiert.\n\n### Kompatibilität\n\nFür das Profil ISiKAllergieUnvertraeglichkeit wird eine Kompatibilität mit folgenden Profilen angestrebt; allerdings kann nicht sichergestellt werden, dass Instanzen, die gegen ISiKAllergieUnvertraeglichkeit valide sind, auch valide sind gegen:\n* [das Profil KBV_PR_Base_AllergyIntolerance der KBV](https://fhir.kbv.de/StructureDefinition/KBV_PR_Base_AllergyIntolerance)\n* [das Profil EMDAF_PR_AllergyIntolerance der GEVKO](https://fhir.gevko.de/StructureDefinition/EMDAF_PR_AllergyIntolerance)\n* [das Profil AllergyIntolerance-uv-ips der International Patient Summary](http://hl7.org/fhir/uv/ips/StructureDefinition/AllergyIntolerance-uv-ips)\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "AllergyIntolerance"
          }
        ],
        "reference" : {
          "reference" : "AllergyIntolerance/ISiKAllergieUnvertraeglichkeitBeispiel1"
        },
        "name" : "ISiKAllergieUnvertraeglichkeitBeispiel1",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAllergieUnvertraeglichkeit"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKAngehoeriger"
        },
        "name" : "ISiKAngehoeriger",
        "description" : "Dieses Profil ermöglicht die Darstellung von Angehörigen in ISiK Szenarien.  \n### Motivation\nDer Angehörige wird vor allem im Zusammenhang mit Anwendungsszenarien verwendet,\n in denen das Versicherungsverhältnis eine Rolle spielt. \n Hier können Angehörige, bspw. der hauptversicherte Elternteil \n eines minderjährigen Kindes, in der Familienversicherung sein. \n In Selbstzahler-Szenarien können Angehörige die Zahler für eine \n im Krankenhaus erbrachte Leistung sein.\nIn FHIR werden Angehörige von Patienten mit der RelatedPerson-Ressource repräsentiert.\n\n### Kompatibilität\nFür das Profil ISiKAngehoeriger wurde bis zum Zeitpunkt der Veröffentlichung kein Abgleich der Kompatibilität zu anderen Profilen (der KBV und der Medizininformatik-Initiative) durchgeführt.\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "RelatedPerson"
          }
        ],
        "reference" : {
          "reference" : "RelatedPerson/ISiKAngehoerigerMustermann"
        },
        "name" : "ISiKAngehoerigerMustermann",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAngehoeriger"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKASKCoding"
        },
        "name" : "ISiKASKCoding",
        "description" : "Data Type profile for ASK Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKATCCoding"
        },
        "name" : "ISiKATCCoding",
        "description" : "Data Type profile for ATC Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKAtemfrequenz"
        },
        "name" : "ISiKAtemfrequenz",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die Atemfrequenz eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung der Atemfrequenz ist essenziell für die frühzeitige Erkennung von Gesundheitsveränderungen, die Behandlungsbewertung und die Unterstützung klinischer Entscheidungen.\n\nIn FHIR wird die Atemfrequenz mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKAtemfrequenz ist vom Profil [VitalSignDE_Atemfrequenz](http://fhir.de/StructureDefinition/observation-de-vitalsign-atemfrequenz) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Respiratory Rate Profile](http://hl7.org/fhir/StructureDefinition/resprate) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKAtemfrequenzExample"
        },
        "name" : "ISiKAtemfrequenzExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAtemfrequenz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKAtemfrequenzMaxExample"
        },
        "name" : "ISiKAtemfrequenzMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAtemfrequenz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKAtemfrequenzMinExample"
        },
        "name" : "ISiKAtemfrequenzMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAtemfrequenz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKBehandlungsergebnisRehaCS"
        },
        "name" : "ISiKBehandlungsergebnisReha",
        "description" : "Behandlungsergebnis Reha gemäß §301(4 UND 4A) SGB V. Diagnosenbezogene Bewertung des Behandlungsergebnisses für einen Versicherten/Berechtigten bei Entlassung aus der Reha-Maßnahme bzw. Stellung eines Antrags auf Verlängerung. Vgl. Schlüsseltabelle 2.71 Diagnose - Behandlungsergebnis.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKBehandlungsergebnisReha"
        },
        "name" : "ISiKBehandlungsergebnisRehaVS",
        "description" : "Behandlungsergebnis Reha gemäß §301(4 UND 4A) SGB V. Diagnosenbezogene Bewertung des Behandlungsergebnisses für einen Versicherten/Berechtigten bei Entlassung aus der Reha-Maßnahme bzw. Stellung eines Antrags auf Verlängerung. Vgl. Schlüsseltabelle 2.71 Diagnose - Behandlungsergebnis.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKBerichtBundle"
        },
        "name" : "ISiKBerichtBundle",
        "description" : "Das Document-Bundle dient dem Transport von Berichten zwischen Subsystemen im Krankenhaus. \nDas Bundle entspricht den Anforderungen an ein [FHIR Document Bundle](https://hl7.org/fhir/R4/documents.html) : Alle referenzierten Ressourcen müssen als Einträge im Bundle enthalten sein. \nDas Bundle unterstützt die Übermittlung einer menschenlesbaren Dokumentation (Narrative) und erlaubt zudem die Übernahme wichtiger Ressourcen (z. B. Diagnosen und Prozeduren), die einem Patienten und Fall (Patient, Encounter) zugeordnet sind.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKBerichtSubSysteme"
        },
        "name" : "ISiKBerichtSubSysteme",
        "description" : "Dieses Profil ermöglicht die krankenhaus-interne Übermittlung eines Berichtes bestehend aus beliebigen strukturierten FHIR-Ressourcen \nsowie einer textuellen HTML-Repräsentation (Narrative) an einen ISiK-Basis-kompatiblen Server.\n### Motivation\nIn der heterogenen Systemlandschaft im Krankenhaus sind eine Vielzahl spezialisierter Subsysteme im Einsatz. Die Ergebnisse aus diesen Subsystemen sind aktuell jedoch häufig nicht in den Primärsystemen des Krankenhauses verfügbar, denn es bestehen folgende Herausforderungen:\n\nDie Daten in Subsystemen sind sehr heterogen und können hochspezialisiert sein.\nBei der Nutzung dieser Subsysteme besteht häufig ein Interesse, auf die menschenlesbare Repräsentation der strukturierten Daten einwirken zu können.\nKünftig ist mit Szenarien zu rechnen, bei denen Befunde aus Subsystemen in eine elektronische Patientenakte übertragen werden sollen.\nAktuell werden Befunde, obwohl diese in den Subsystemen in hochstrukturierter Form vorliegen, nur als PDF an das Primärsystem übermittelt. Oft weil kein strukturiertes Format spezifiziert ist, das sowohl versendendes Subsystem als auch empfangendes Primärsystem implementiert haben.\nDer Umfang, in dem eine Datenübernahme in ein Primärsystem möglich ist, variiert stark zwischen den Systemen oder Installationen, z.B. abhängig davon, ob ein Modul für Vitalparameter installiert ist.\nDie ISiK-Spezifikation begegnet diesen Herausforderungen, indem sie die Übermittlung von Ergebnissen aus Subsystemen an die Primärsysteme in Form von strukturierten Dokumenten erfordert, die über eine menschenlesbare Repräsentation verfügen. Diese strukturierten Dokumente werden im ISiK-Kontext als Berichte bezeichnet. Dabei sind die strukturierten Inhalte der Berichte harmonisiert mit den verbreiteten Formaten für Primärsysteme.\n\n(Semi-)Strukturierte Dokumente werden in FHIR mit der `Composition`-Ressource repräsentiert, \ndie die Dokumentenmetadaten sowie die textuelle Repräsentation des Dokumentes enthält.\nDie Composition referenziert auf beliebige weiter FHIR-Ressourcen, die die strukturierten Komponenten des Dokumentes darstellen.\n\nFür den Transport wird die Composition zusammen mit allen direkt oder indirekt referenzierten Ressourcen in eine `Bundle`-Ressource\n vom Typ `document` aggregiert. \nDas Document-Bundle trägt alle Eigenschaften eines Dokumentes: Abgeschlossenheit, Unveränderbarkeit, Signierbarkeit.  \n\nEs obliegt dem empfangenden System, ob dieses Dokument lediglich in seiner Gesamtheit persistiert wird, oder ob darüber hinaus einzelne Bestandteile (Ressourcen) \nals strukturierte Daten automatisch oder auf Veranlassung eines Benutzers in die Patientenakte übernommen werden. \n\nIn der aktuellen Ausbaustufe von ISiK ist lediglich die Übernahme und Anzeige der Dokument-Metadaten (z.B. Dokumenttyp, Dokumentdatum, Quelle) und der menschenlesbaren HTML-Repräsentation in die Primärsysteme erforderlich.  \n\nIn weiteren Ausbaustufen von ISiK soll darüber hinaus eine Übernahme der strukturierten Anteile der Dokumente möglich sein, die den ISiK-Spezifikationen entsprechen, z.B. Diagnosen und Prozeduren.  \n\n### Kompatibilität  \nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKBesondereBehandlungsformRehaCS"
        },
        "name" : "ISiKBesondereBehandlungsformReha",
        "description" : "Besondere Behandlungsform der Reha gemäß §301(4 UND 4A) SGB V. Vgl. Schlüsseltabelle 2.51 Besondere Behandlungsformen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKBesondereBehandlungsformReha"
        },
        "name" : "ISiKBesondereBehandlungsformRehaVS",
        "description" : "Besondere Behandlungsform der Reha gemäß §301(4 UND 4A) SGB V. Vgl. Schlüsseltabelle 2.51 Besondere Behandlungsformen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKBinary"
        },
        "name" : "ISiKBinary",
        "description" : "Dieses Profil ermöglicht die Darstellung von FHIR-fremden Formaten (z.B. PDFs, Bilder, CDA) in ISiK Szenarien. \n\n### Motivation\nFür FHIR-fremde Formate werden die Daten base64-codiert in der Binary-Ressource (in XML oder JSON) transportiert oder \nüber die REST-API am Binary-Endpunkt in ihrem nativen Format bereitgestellt. \nBinary-Ressourcen werden von Attachment-Elementen in DocumentReference-Ressourcen verlinkt und damit in den Kontext anderer FHIR-Ressourcen (z.B. Patient und Encounter) gestellt. \n\n### Kompatibilität\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.\n\n### Hinweis\n\nDas ISIK-Binary-Profil ist *nicht* Bestandteil der Implementierung und des Bestätigungsverfahrens zum ISIK Basismodul.\nDas Profil ist Teil des ISIK Basismoduls, da es als übergreifend genutzte Ressource sowohl im [Modul Terminplanung](https://simplifier.net/guide/isik-terminplanung-v4/ImplementationGuide-markdown-Datenobjekte?version=current) als auch im [Modul Dokumentenaustausch](https://simplifier.net/guide/isik-dokumentenaustausch-v4/ImplementationGuide-markdown-Datenobjekte?version=current) implementiert werden muss.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKBlutdruckSystemischArteriell"
        },
        "name" : "ISiKBlutdruckSystemischArteriell",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über den Blutdruck eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung des Blutdrucks ist essenziell für die frühzeitige Erkennung von Gesundheitsveränderungen, die Behandlungsbewertung und die Unterstützung klinischer Entscheidungen.\n\nIn FHIR wird der Blutdruck mit der Observation-Ressource repräsentiert, die einzelnen Komponenten des Blutdrucks werden als Component-Elemente abgebildet.\n\nHinweis: In Fällen, in denen fachlich motiviert ausschließlich ein systolischer Blutdruck erhoben wird (z.B. in der Intensivmedizin), kann für den Slice zur Diastole (DiastolicBP) das Element .dataAbsentReason (mit dem Code 'not-performed') verwendet werden.\n\n### Kompatibilität\nDas Profil ISiKBlutdruckSystemischArteriell ist vom Profil [VitalSignDE_Blutdruck](http://fhir.de/StructureDefinition/observation-de-vitalsign-blutdruck) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Blood Pressure Profile](http://hl7.org/fhir/StructureDefinition/bp) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKBlutdruckSystemischArteriellExample"
        },
        "name" : "ISiKBlutdruckSystemischArteriellExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKBlutdruckSystemischArteriell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKBlutdruckSystemischArteriellMaxExample"
        },
        "name" : "ISiKBlutdruckSystemischArteriellMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKBlutdruckSystemischArteriell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKBlutdruckSystemischArteriellMinExample"
        },
        "name" : "ISiKBlutdruckSystemischArteriellMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKBlutdruckSystemischArteriell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKCodeSystem"
        },
        "name" : "ISiKCodeSystem",
        "description" : "Dieses Profil beschreibt die maschinenlesbare Repräsentation von \nsystem-spezifischen Kodierungen in ISiK-Szenarien.  \n\n### Motivation\n\nISiK erlaubt in diversen Kontexten die Erweiterung der Kodierung durch Krankenhaus-/System-interne Kodierungen. Das Profil ISiKKatalog (CodeSystem) als Profil erlaubt die Repräsentation der dazugehörigen Codes und Display-Werte. \n\nEine maschinenlesbare Repräsentation dieser Kodierungen erlaubt es Clients, dazugehörige Anzeigetext und Definitionen zu verarbeiten.\n\nEin Codesystem eignet sich auch dazu, auf dessen Basis definierte [ValueSets zu expandieren](https://hl7.org/fhir/R4/valueset-operation-expand.html).\nDa ISiKValueSet expandierte Valuesets vorsieht, ist eine dynamische Expansion in der Regel nicht erforderlich.\nDarüber hinausgehend ist ein Use Case im Kontext der Katalogabfrage folgender: Ein Client möchte eine Expansion neu generieren (z.B. mit anderen Expansionen-Parametern), um das ValueSet beispielsweise in einer anderen Sprache auszugeben.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKCoding"
        },
        "name" : "ISiKCoding",
        "description" : "Data Type profile for Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKConfidentialityCodes"
        },
        "name" : "ISiKConfidentialityCodes",
        "description" : "Vertraulichkeitsstufen",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKDiagnose"
        },
        "name" : "ISiKDiagnose",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen \nüber die Diagnosen eines Patienten im Rahmen des Bestätigungsverfahrens der gematik.  \n### Motivation\nDie Möglichkeit, auf eine Übersicht der Diagnosen eines Patienten zuzugreifen, Patienten anhand ihrer Diagnose zu suchen oder zu prüfen, \nob eine konkrete Diagnose bei einem Patienten vorliegt, sind wichtige Funktionen im klinischen Behandlungsablauf.  \n\nIn FHIR werden Diagnosen mit der Condition-Ressource repräsentiert.  \n\nDa die Diagnosen in klinischen Primärsystemen in der Regel in ICD-10-codierter Form vorliegen, fordert ISiK in erster Linie diese Form des Austausches. \nFalls eine Diagnose zwar dokumentiert, aber noch nicht codiert wurde (z.B. wenn die Kodierung erst nach der Entlassung erfolgt), \nist alternativ eine Repräsentation als Freitext-Diagnose möglich.\n\n### Kompatibilität\nFür das Profil ISiKDiagnose wird eine Kompatibilität mit folgenden Profilen angestrebt; allerdings kann nicht sichergestellt werden, dass Instanzen, die gegen ISiKDiagnose valide sind, auch valide sind gegen:\n* das [Profil ProfileConditionDiagnose der Medizininformatik-Initative](https://www.medizininformatik-initiative.de/fhir/core/modul-diagnose/StructureDefinition/Diagnose)\n* das [Profil KBV_PR_Base_Condition_Diagnosis der KBV](https://fhir.kbv.de/StructureDefinition/KBV_PR_Base_Condition_Diagnosis)]  \nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKEKG"
        },
        "name" : "ISiKEKG",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über kurze, relevante EKG-Ausschnitte eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus). Es wurde entwickelt, um spezifische klinische Fragestellungen zu unterstützen, bei denen prägnante und gezielte EKG-Daten im Vordergrund stehen. Für vollständige und längere EKG-Aufzeichnungen sind alternative Formate vorgesehen, die für umfangreiche Daten besser geeignet sind.\n### Motivation\nDie Bereitstellung kurzer EKG-Ausschnitte ermöglicht eine präzise und effiziente Unterstützung bei der Diagnose akuter kardiologischer Fragestellungen, der Überwachung von Arrhythmien oder der Beurteilung bestimmter Ereignisse wie ST-Strecken-Veränderungen. Diese fokussierte Darstellung dient der Optimierung klinischer Entscheidungen und der schnellen Verarbeitung relevanter Daten.\n\nIn FHIR wird das EKG durch die Observation-Ressource repräsentiert, wobei spezifische Anforderungen für die Darstellung und Kodierung der Daten in diesem Profil berücksichtigt werden.\n\n### Kompatibilität\nDas Profil ISiKEKG ist vom Profil [EkgDE](http://fhir.de/StructureDefinition/observation-de-ekg) aus den deutschen Basisprofilen abgeleitet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKEKGExample"
        },
        "name" : "ISiKEKGExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKEKG"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKEKGMaxExample"
        },
        "name" : "ISiKEKGMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKEKG"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKEKGMinExample"
        },
        "name" : "ISiKEKGMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKEKG"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKEntlassformRehaCS"
        },
        "name" : "ISiKEntlassformReha",
        "description" : "ISiK Entlassform Reha. Beschreibt Form und ggf. Weiterbehandlung der Entlassung eines Versicherten/Berechtigten aus verwaltungs- und medizinischer Sicht. Vgl. Schlüsseltabelle 2.107 Entlassungsform.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKEntlassformReha"
        },
        "name" : "ISiKEntlassformRehaVS",
        "description" : "ISiK Entlassform Reha. Beschreibt Form und ggf. Weiterbehandlung der Entlassung eines Versicherten/Berechtigten aus verwaltungs- und medizinischer Sicht. Vgl. Schlüsseltabelle 2.107 Entlassungsform.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKFormularDefinition"
        },
        "name" : "ISiKFormularDefinition",
        "description" : "Im Profil `ISiKFormularDefinition` sind Mindestanforderungen an ISiK kompatible Formulare definiert.\nDie verwendbaren Extensions sind nicht mit profiliert, sondern im IG unter [Artefakte->Extensions](https://simplifier.net/guide/isik-formular-stufe-5/Einfuehrung/Artefakte/Extensions.page.md?version=current) beschrieben.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKGCS"
        },
        "name" : "ISiKGCS",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über den Glasgow Coma Scale (GCS) Score eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n\n### Motivation\nDie Erfassung und Überwachung des Bewusstseinszustands anhand des GCS ist essenziell für die Beurteilung neurologischer Funktionen, die Überwachung von Patienten mit Schädel-Hirn-Trauma oder anderen neurologischen Erkrankungen sowie die Unterstützung klinischer Entscheidungen.\n\nIn FHIR wird der GCS-Score mit der Observation-Ressource repräsentiert, wobei die einzelnen Komponenten der Skala - Augenöffnung, verbale Reaktion und motorische Reaktion - als Component-Elemente abgebildet werden.\n### Kompatibilität\nDas Profil ISiKGCS ist vom Profil [ScoreDE_GCS](http://fhir.de/StructureDefinition/observation-de-score-gcs) aus den deutschen Basisprofilen abgeleitet.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKGCSExample"
        },
        "name" : "ISiKGCSExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKGCS"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKGCSMaxExample"
        },
        "name" : "ISiKGCSMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKGCS"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKGCSMinExample"
        },
        "name" : "ISiKGCSMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKGCS"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKHerzfrequenz"
        },
        "name" : "ISiKHerzfrequenz",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die Herzfrequenz eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung der Herzfrequenz ist essenziell für die frühzeitige Erkennung von Herz-Kreislauf-Problemen, die Beurteilung des Gesundheitszustands sowie die Unterstützung klinischer Entscheidungen in der Patientenversorgung.\n\nIn FHIR wird die Herzfrequenz mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKHerzfrequenz ist vom Profil [VitalSignDE_Herzfrequenz](http://fhir.de/StructureDefinition/observation-de-vitalsign-herzfrequenz) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Respiratory Rate Profile](http://hl7.org/fhir/StructureDefinition/heartrate) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKHerzfrequenzExample"
        },
        "name" : "ISiKHerzfrequenzExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKHerzfrequenz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKHerzfrequenzMaxExample"
        },
        "name" : "ISiKHerzfrequenzMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKHerzfrequenz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKHerzfrequenzMinExample"
        },
        "name" : "ISiKHerzfrequenzMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKHerzfrequenz"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKICD10GMCoding"
        },
        "name" : "ISiKICD10GMCoding",
        "description" : "Data Type profile for ICD10-GM Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKalender"
        },
        "name" : "ISiKKalender",
        "description" : "Das Datenobjekt ISiKKalender bietet die Möglichkeit Kalender für verschiedene Akteure (Practitioner, Device, HealthcareService) zu exponieren, sodass für die Ressourcen Termine gebucht werden können.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Schedule"
          }
        ],
        "reference" : {
          "reference" : "Schedule/ISiKKalenderExample"
        },
        "name" : "ISiKKalenderExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKalender"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKoerpergewicht"
        },
        "name" : "ISiKKoerpergewicht",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über das Körpergewicht eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung des Körpergewichts ist essenziell für die Beurteilung des Ernährungszustands, die Überwachung von Veränderungen im Rahmen der Therapie sowie die Unterstützung klinischer Entscheidungen in der Patientenversorgung.\n\nIn FHIR wird das Körpergewicht mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKKoerpergewicht ist vom Profil [VitalSignDE_Koerpergewicht](http://fhir.de/StructureDefinition/observation-de-vitalsign-koerpergewicht) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Body Weight Profile](http://hl7.org/fhir/StructureDefinition/bodyweight) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpergewichtExample"
        },
        "name" : "ISiKKoerpergewichtExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergewicht"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpergewichtMaxExample"
        },
        "name" : "ISiKKoerpergewichtMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergewicht"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpergewichtMinExample"
        },
        "name" : "ISiKKoerpergewichtMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergewicht"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKoerpergroesse"
        },
        "name" : "ISiKKoerpergroesse",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die Körpergröße eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung der Körpergröße ist essenziell für die Beurteilung von Wachstumsprozessen, die Berechnung wichtiger Indizes wie des Body-Mass-Index (BMI) sowie die Unterstützung klinischer Entscheidungen in der Patientenversorgung.\n\nIn FHIR wird die Körpergröße mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKKoerpergroesse ist vom Profil [VitalSignDE_Koerpergroesse](http://fhir.de/StructureDefinition/observation-de-vitalsign-koerpergroesse) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Body Height Profile](http://hl7.org/fhir/StructureDefinition/bodyheight) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpergroesseExample"
        },
        "name" : "ISiKKoerpergroesseExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergroesse"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpergroesseMaxExample"
        },
        "name" : "ISiKKoerpergroesseMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergroesse"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpergroesseMinExample"
        },
        "name" : "ISiKKoerpergroesseMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpergroesse"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKoerperkerntemperatur"
        },
        "name" : "ISiKKoerperkerntemperatur",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die Körperkerntemperatur eines Patienten im Rahmen der interoperablen Kommunikation gemäß den ISiK Vorgaben.  \nDieses Profil repräsentiert sowohl direkte als auch indirekte Messungen der Körperkerntemperatur.\n### Motivation\nDie Erfassung und Überwachung der Körpertemperatur ist essenziell für die frühzeitige Erkennung von Infektionen, die Beurteilung des Gesundheitszustands sowie die Unterstützung klinischer Entscheidungen in der Patientenversorgung.\nIn FHIR wird die Körpertemperatur mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKKoerperkerntemperatur ist vom Profil [VitalSignDE_Koerpertemperatur](http://fhir.de/StructureDefinition/observation-de-vitalsign-koerpertemperatur) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [OObservation Body Temperature Profile](http://hl7.org/fhir/StructureDefinition/bodytemp) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerperkerntemperaturExample"
        },
        "name" : "ISiKKoerperkerntemperaturExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerperkerntemperatur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerperkerntemperaturMaxExample"
        },
        "name" : "ISiKKoerperkerntemperaturMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerperkerntemperatur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerperkerntemperaturMinExample"
        },
        "name" : "ISiKKoerperkerntemperaturMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerperkerntemperatur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKoerpertemperatur"
        },
        "name" : "ISiKKoerpertemperatur",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die Körpertemperatur eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung der Körpertemperatur ist essenziell für die frühzeitige Erkennung von Infektionen, die Beurteilung des Gesundheitszustands sowie die Unterstützung klinischer Entscheidungen in der Patientenversorgung.\n\nIn FHIR wird die Körpertemperatur mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKKoerpertemperatur ist vom Profil [VitalSignDE_Koerpertemperatur](http://fhir.de/StructureDefinition/observation-de-vitalsign-koerpertemperatur) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [OObservation Body Temperature Profile](http://hl7.org/fhir/StructureDefinition/bodytemp) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpertemperaturExample"
        },
        "name" : "ISiKKoerpertemperaturExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpertemperatur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpertemperaturMaxExample"
        },
        "name" : "ISiKKoerpertemperaturMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpertemperatur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKoerpertemperaturMinExample"
        },
        "name" : "ISiKKoerpertemperaturMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKoerpertemperatur"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKontaktGesundheitseinrichtung"
        },
        "name" : "ISiKKontaktGesundheitseinrichtung",
        "description" : "\nDieses Profil ermöglicht die Abbildung von Besuchen/Aufenthalten eines Patienten in einer Gesundheitseinrichtung.\n### Motivation\nInformationen über die Besuche des Patienten entlang seines \nBehandlungspfades im Krankenhaus sind ein wichtiger Bestandteil \ndes einrichtungsinternen Datenaustausches. \nSie ermöglichen die Unterscheidung von stationären und ambulanten \nsowie aufgenommenen und entlassenen Patienten. \nWeiterhin ist aus den Besuchsinformationen der aktuelle Aufenthaltsort \ndes Patienten (Fachabteilung, Station, Bettplatz) ermittelbar. \nKlinische Ressourcen werden in FHIR durch Verlinkung auf die \nEncounter-Ressource in einen Kontext zum Besuch gestellt. \nDieser Kontext ist wichtig für die Steuerung von Zugriffsberechtigungen \nund Abrechnungsprozessen.  \n\nZu Beginn der meisten klinischen Workflows steht die Auswahl \ndes Besuchskontextes. \nDies geschieht bspw. durch das Suchen der Encounter-Ressource \nanhand von Eigenschaften wie Aufnahmenummer, Fallart oder Aufnahmedatum. \nDaraufhin werden die zutreffenden Suchergebnisse angezeigt \nund der gewünschte Besuch ausgewählt.\n\nIn FHIR werden Besuche, Aufenthalte, aber auch virtuelle Kontakte mit der `Encounter`-Ressource repräsentiert.\n\nWeitere Hinweise zu den Abgrenzungen der Begrifflichkeiten Fall und Kontakt finden sie unter {{pagelink: Fall, text: Fall-Begriff in ISiK}}\n\n### Kompatibilität\nFür das Profil ISiKKontaktGesundheitseinrichtung wird eine Kompatibilität \nmit folgenden Profilen angestrebt; \nallerdings kann nicht sichergestellt werden, dass Instanzen, \ndie gegen ISiKKontaktGesundheitseinrichtung valide sind, \nauch valide sind gegen:\n\n* Profil [Kontakt mit einer Gesundheitseinrichtung \nder Medizininformatik-Initiative](https://www.medizininformatik-initiative.de/fhir/core/modul-fall/StructureDefinition/KontaktGesundheitseinrichtung)\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKKopfumfang"
        },
        "name" : "ISiKKopfumfang",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über den Kopfumfang eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung des Kopfumfangs ist essenziell für die Beurteilung von Wachstumsprozessen, insbesondere bei Säuglingen und Kleinkindern, sowie für die frühzeitige Erkennung von Entwicklungsauffälligkeiten oder neurologischen Erkrankungen.\n\nIn FHIR wird der Kopfumfang mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKKopfumfang ist vom Profil [VitalSignDE_Kopfumfang](http://fhir.de/StructureDefinition/observation-de-vitalsign-kopfumfang) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Head Circumference Profile](\nhttp://hl7.org/fhir/StructureDefinition/headcircum) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKopfumfangExample"
        },
        "name" : "ISiKKopfumfangExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKopfumfang"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKopfumfangMaxExample"
        },
        "name" : "ISiKKopfumfangMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKopfumfang"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKKopfumfangMinExample"
        },
        "name" : "ISiKKopfumfangMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKopfumfang"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchung"
        },
        "name" : "ISiKLaboruntersuchung",
        "description" : "Dieses Profil ermöglicht die Abbildung von Informationen zur Laboruntersuchungen eines Patienten in ISiK Szenarien. Es dient primär als Vorlage, von der spezifische Laboruntersuchungs-Profile abgeleitet werden, kann aber grundsätzlich auch zur Repräsentation von nicht weiter ausspezifizierten Laboruntersuchungen genutzt werden.\n\nViele medizinischen Entscheidungen benötigen Informationen zu den Laboruntersuchungen eines Patienten. Hierzu gehören z.B. aktuelle Nierenfunktionswerte, Leberwerte, Blutbildwerte oder Hormone aus Schilddrüse.\nJede dieser Untersuchungen wird durch bestimmte [[https://loinc.org/ LOINC]] oder [[http://snomed.info/sct SNOMED CT]] Codes bezeichnet. Der angegebene Wert ist durch genaue Einheitenangaben in [[http://unitsofmeasure.org UCUM]] zu konkretitiseren.\nMotivierender Use-Case zur Einführung dieser Profile ist die [Arzneitmitteltherapiesicherheit im Krankenhaus - AMTS](https://simplifier.net/guide/isik-medikation-v4/ImplementationGuide-markdown-UseCases-AMTS?version=current).\n\nIn FHIR werden Untersuchungen, bzw. Beobachtungen als [`Observation`](https://hl7.org/fhir/R4/observation.html)-Ressource repräsentiert. Zugehörige Codes und Einheiten sind den entsprechenden Valuessets zu entnehmen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungCRP"
        },
        "name" : "ISiKLaboruntersuchungCRP",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung CRP eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungGFR"
        },
        "name" : "ISiKLaboruntersuchungGFR",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung GFR eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungHb"
        },
        "name" : "ISiKLaboruntersuchungHb",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung Hb eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungPCT"
        },
        "name" : "ISiKLaboruntersuchungPCT",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung PCT eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungSerumkreatinin"
        },
        "name" : "ISiKLaboruntersuchungSerumkreatinin",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung Serumkreatinin eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungThrombozyten"
        },
        "name" : "ISiKLaboruntersuchungThrombozyten",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung Thrombozyten eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungTroponin"
        },
        "name" : "ISiKLaboruntersuchungTroponin",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung Troponin eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLaboruntersuchungTSH"
        },
        "name" : "ISiKLaboruntersuchungTSH",
        "description" : "Dieses Profil ermöglicht die Abbildung der Laboruntersuchung TSH eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLebensZustand"
        },
        "name" : "ISiKLebensZustand",
        "description" : "Basisprofil für ISiKLebensZustand Observation \n\n### Motivation\n\nViele medizinischen Entscheidungen benötigen Informationen zu den Lebensumständen eines Patienten. Hierzu gehören eine aktuelle Schwangerschaft, Raucherstatus sowie der Alkoholabususstatus.\nMotivierender Use-Case zur Einführung dieser Profile ist die [Arzneitmitteltherapiesicherheit im Krankenhaus - AMTS](https://simplifier.net/guide/isik-medikation-v4/ImplementationGuide-markdown-UebergreifendeUseCases-AMTS).\n\nIn FHIR werden Untersuchungen, bzw. Beobachtungen als [`Observation`](https://hl7.org/fhir/R4/observation.html)-Ressource repräsentiert.\n\nDieses Profil ist eine generische, ISiK-spezifische Observation für die Abbildung von Lebenszuständen.  \nDie folgenden Profile vom Typ `Observation` sind spezifische Profile im oben genannten Sinn:  \n* {{pagelink:Schwangerschaftsstatus-Profil}}\n* {{pagelink:ErwarteterEntbindungstermin-Profil}}\n* {{pagelink:Stillstatus-Profil}} \n* {{pagelink:AlkoholAbusus-Profil}} \n* {{pagelink:RaucherStatus-Profil}} \n\n### Kompatibilität\n\nFür Schwangerschaftsstatus & Erwarteter Geburtstermin wird eine Kompatibilität mit folgenden **IPS** Profilen angestrebt:\n* [IPS Resource Profile: Observation - Pregnancy: EDD](https://hl7.org/fhir/uv/ips/STU1.1/StructureDefinition-Observation-pregnancy-edd-uv-ips.html). \n* [IPS Resource Profile: Observation - Pregnancy: status](https://hl7.org/fhir/uv/ips/STU1.1/StructureDefinition-Observation-pregnancy-status-uv-ips.html)\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKLocationPhysicalType"
        },
        "name" : "ISiKLocationPhysicalType",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKLoincCoding"
        },
        "name" : "ISiKLoincCoding",
        "description" : "Data Type profile for LOINC Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKMDRRelevanzFormularCS"
        },
        "name" : "ISiKMDRRelevanzFormular",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMDRRelevanzFormularExtension"
        },
        "name" : "ISiKMDRRelevanzFormularExtension",
        "description" : "Mit der Extension wird die Medizinprodukt-Relevanz angegeben. Ist die Extension nicht vorhanden, ist nichts in Richtung der MDR zu beachten. Sobald sie vorhanden ist, müssen ggf. Voraussetzung zur Befüllung oder Anzeige erfüllt sein. Im aktuellen Rahmen des Moduls sind diese aber nicht weiter spezifizert.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKMDRRelevanzFormularVS"
        },
        "name" : "ISiKMDRRelevanzFormularVS",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikament"
        },
        "name" : "ISiKMedikament",
        "description" : "Dieses Profil ermöglicht die Abbildung von patientenunabhängigen Informationen zu Medikamenten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKMedikationsartVS"
        },
        "name" : "ISiKMedikationsartVS",
        "description" : "ISiK Therapiearten für Medikation",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikationsInformation"
        },
        "name" : "ISiKMedikationsInformation",
        "description" : "Dieses Profil ermöglicht die Abbildung von Informationen zur Medikation eines Patienten in ISiK Szenarien.\n\nHinweis zur Auswahl des Profils: \nIn Abgrenzung zu ISiKMedikationsVerabreichung (MedicationAdministration) wird mittels des vorliegenden Profils die Verabreichung eines Medikaments an einen Patienten mit einer lediglich Datums-genauen Angabe abgebildet (einschließlich Granularität Jahr, Monat oder Tag für .effectiveDateTime oder .effectivePeriod auf Datums-Ebene gemäß der [FHIR-Core Vorgabe](https://hl7.org/fhir/R4/datatypes.html#dateTime)).\nZur sekunden-genauen Angabe der Verabreichung eines Medikaments (im Sinne einer medizinischen Verabreichungsdokumentation durch medizinisches Personal) an einen Patienten SOLL das Profil ISiKMedikationsVerabreichung (MedicationAdministration) verwendet werden. Siehe entsprechende Profilseite für weitere Begründung.\n\n**Hinweis zur Pausierung einer Medikation (Best-Practice):**\n\nFür die Abbildung der Pausierung einer Medikation wird empfohlen, **mehrere `MedicationStatement`-Ressourcen** zu verwenden, anstatt eine bestehende zu überschreiben. Dies bringt folgende Vorteile:\n\n- **Korrekte Statusabbildung:**  \n  Das `status`-Feld muss stets aktuell gepflegt werden, um den momentanen Zustand der Medikation systemweit sichtbar und durchsuchbar zu halten.\n\n- **Effiziente Abfragen über REST API:**  \n  In Kombination mit `effective[x]` ermöglicht das `status`-Feld die gezielte Abfrage aller aktuell gültigen Medikationseinträge über die REST API.  \n  Wird stattdessen nur das `dosage`-Element verändert, ist keine zuverlässige Filterung möglich – alle `MedicationStatements` müssten abgerufen und manuell analysiert werden.\n\n- **Erhalt von Verlaufsinformationen:**  \n  Wenn z. B. auch ein `statusReason` (z. B. „pausiert wegen Nebenwirkungen“) dokumentiert wird, ginge diese Information bei einem Update der bestehenden Ressource verloren, sobald die Medikation fortgesetzt wird.  \n  Durch neue `MedicationStatement`-Einträge bleibt die Verlaufshistorie erhalten.  \n  *(Dieser Anwendungsfall ist aktuell nicht gefordert, aber zukünftig denkbar.)*",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikationsVerabreichung"
        },
        "name" : "ISiKMedikationsVerabreichung",
        "description" : "Dieses Profil ermöglicht die Abbildung der Verabreichung von Medikamenten für einen Patienten in ISiK Szenarien. \nHinweis zur Auswahl des Profils: In Abgrenzung zu ISiKMedikationsInformation (MedicationStatement) wird mittels des vorliegenden Profils die Verabreichung eines Medikaments an einen Patienten mit einer Zeitpunkt-genauen Angabe abgebildet (.effectiveDateTime oder .effectivePeriod auf Sekundenebene gemäß der [FHIR-Core Vorgabe](https://hl7.org/fhir/R4/datatypes.html#dateTime)). D.h. die lediglich Datums-genaue Angabe  ist im vorliegenden Profil nicht erlaubt. \nDas Profil ISiKMedikationsInformation (MedicationStatement) kann ebenfalls für  die Abbildung der Verabreichung von Medikamenten für einen Patienten verwendet werden, wenn keine Zeitpunkt-genauen Angaben zur Verabreichung vorliegen, sondern lediglich Datums-genaue Angaben (einschließlich Granularität Jahr, Monat oder Tag).\n\nBegründung zur Profil- und Nutzungsdifferenzierung:\nHandelt es sich bei Erfassung um eine medizinische Verabreichungsdokumentation, dann ist ein genauer Zeitstempel zwingend. Die medizinische Verabreichungsdokumentation muss durch medizinisches Personal erfolgen. Angaben von Patienten und Angehörigen sind grundsätzlich keine medizinische Verabreichungsdokumentation und daher als MedicationStament zu erfassen(['report that such a sequence (or at least a part of it) did take place'](https://hl7.org/fhir/R4/medicationstatement.html)). \n\n**Hinweis zur Pausierung einer Medikation (Best-Practice):**\n\nFür die Abbildung der Pausierung einer Medikation wird empfohlen, **mehrere `MedicationAdministration`-Ressourcen** zu verwenden, anstatt eine bestehende zu überschreiben. Dies bringt folgende Vorteile:\n\n- **Korrekte Statusabbildung:**  \n  Das `status`-Feld muss stets aktuell gepflegt werden, um den momentanen Zustand der Medikation systemweit sichtbar und durchsuchbar zu halten.\n\n- **Effiziente Abfragen über REST API:**  \n  In Kombination mit `effective[x]` ermöglicht das `status`-Feld die gezielte Abfrage aller aktuell gültigen Medikationseinträge über die REST API.  \n  Wird stattdessen nur das `dosage`-Element verändert, ist keine zuverlässige Filterung möglich – alle `MedicationAdministrations` müssten abgerufen und manuell analysiert werden.\n\n- **Erhalt von Verlaufsinformationen:**  \n  Wenn z. B. auch ein `statusReason` (z. B. „pausiert wegen Nebenwirkungen“) dokumentiert wird, ginge diese Information bei einem Update der bestehenden Ressource verloren, sobald die Medikation fortgesetzt wird.  \n  Durch neue `MedicationAdministration`-Einträge bleibt die Verlaufshistorie erhalten.  \n  *(Dieser Anwendungsfall ist aktuell nicht gefordert, aber zukünftig denkbar.)*",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedikationsVerordnung"
        },
        "name" : "ISiKMedikationsVerordnung",
        "description" : "Dieses Profil ermöglicht die Abbildung von Medikationsverordnungen eines Patienten in ISiK Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKMedizinischeBehandlungseinheit"
        },
        "name" : "ISiKMedizinischeBehandlungseinheit",
        "description" : "Unter einer medizinischen Behandlungseinheit wird hier im weiteren Sinne eine Dienstleistung (diagnostisch, therapeutisch, im weiten Sinne gesundheitsfördernd etc.) zum Zweck einer Terminbuchung verstanden. Hierfür können von der Fachabteilung (Organization) unabhängige Kalender gepflegt werden. Im Kontext der Terminplanung können somit angebotene Leistungen (z.B. CT/MRT-Untersuchungen, chirurgische Eingriffe, Beratungsstunden zur Geburt etc.) abgebildet werden.\n\nDer Kontext zu diesem Profil wird mit folgender User Story veranschaulicht: \n\n**User Story**: Ein Patient erhält von seiner Hausärztin einen Überweisungsschein für eine weitere diagnostische Untersuchung in Form einer Kapselendoskopie der Speiseröhre. Der Patient nutzt ein Patientenportal, um unter Angabe der benötigten diagnostische Leistung nach einem verfügbaren Termin zu suchen und findet einen passenden Termin bei der Fachabteilung für Gastroenterologie eines örtlichen Krankenhauses.\n\nHintergrund: Die Suche nach verfügbaren Terminenblöcken (Slot) unter Einbeziehung der Dienstleistung entspricht der Angabe des Überweisungsscheins, ermöglicht hier zugleich eine präzisere Suche und vergrößert darüber hinaus den Raum möglicher Termine über verschiedene Abteilungen (und Institutionen im Patientenportal) hinweg.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "HealthcareService"
          }
        ],
        "reference" : {
          "reference" : "HealthcareService/ISiKMedizinischeBehandlungseinheitExample"
        },
        "name" : "ISiKMedizinischeBehandlungseinheitExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedizinischeBehandlungseinheit"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKOrganisation"
        },
        "name" : "ISiKOrganisation",
        "description" : "Dieses Profil beschreibt die Nutzung von Organisationseinheiten innerhalb eines Krankenhauses oder eines Krankenhauses als ganzem in ISiK-Szenarien.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKOrganisationFachabteilung"
        },
        "name" : "ISiKOrganisationFachabteilung",
        "description" : "Dieses Profil beschreibt die Organisationseinheit Fachabteilung innerhalb eines Krankenhauses.\n### Motivation\n\nDie Abbildung der Aufbauorganisation eines Krankenhauses dient der Festlegung von Zuständigkeiten und (Entscheidungs-)Verantwortungen von Organisationseinheiten (z.B. Fachkliniken, Fachabteilungen und -bereichen etc.) in strukturierter Form. \n\nIn FHIR wird die Organisation (Organization) vom Standort (Location) eindeutig abgegrenzt.\n\nDie Erfassung der Organisation in strukturierter Form ermöglicht u.a.:\n- Zuweisungen von Diensten an bestimmte Bereiche der Aufbauorganisation im Rahmen des Terminmanagements\n- Die Raum- und Betten-Belegung in strukturierter Form (interdisziplinär)\n\nAuch die Erfassung des Krankenhauses als Ganzem ist relevant.\nEntsprechend fokussieren die folgenden Profile zur Organisation auf das Krankenhaus als Ganzes und die Fachabteilung als Organisation.  \n### Kompatibilität\n\nFür das Profil ISiKOrganisationFachabteilung wird eine Kompatibilität mit folgenden Profilen angestrebt; allerdings kann nicht sichergestellt werden, dass Instanzen, die gegen ISIKPatient valide sind, auch valide sind gegen:\n* [Profil TIOrganization der gematik](https://gematik.de/fhir/ti/StructureDefinition/ti-organization)  \n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKPatient"
        },
        "name" : "ISiKPatient",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von administrativen Patientendaten im Rahmen des Bestätigungsverfahrens der gematik.\n### Motivation  \nDer Austausch administrativer Patientendaten ist eine der grundlegenden Funktionalitäten beim Datenaustausch in der klinischen Versorgung.  \nIn FHIR werden sämtliche klinischen Ressourcen durch Verlinkung auf die Ressource 'Patient' in einen Patientenkontext gestellt.  \nDie Herstellung des korrekten Patientenkontextes durch Suchen der Patientenressource anhand von Eigenschaften wie Aufnahmenummer, Name oder Geburtsdatum, \ndie Anzeige der zutreffenden Suchergebnisse und der Auswahl bzw. Bestätigung des richtigen Datensatzes durch den Anwender steht am Beginn der meisten klinischen Workflows.  \n\n### Kompatibilität\nFür das Profil ISIKPatient wird eine Kompatibilität mit folgenden Profilen angestrebt; allerdings kann nicht sichergestellt werden, dass Instanzen, die gegen ISIKPatient valide sind, auch valide sind gegen:\n\n* [Profil KBV_PR_Base_Patient der KBV Basisprofile](https://fhir.kbv.de/StructureDefinition/KBV_PR_Base_Patient)\n* [Profil Patient im International Patient Summary (IPS)](https://hl7.org/fhir/uv/ips/StructureDefinition-Patient-uv-ips.html)\n* [Profil Patient der MI-Initiative](https://www.medizininformatik-initiative.de/fhir/core/modul-person/StructureDefinition/Patient)\n* [Profil TIPatient der gematik](https://gematik.de/fhir/ti/StructureDefinition/ti-patient)\n\nEs ist zu beachten, dass das Profil ISiKPatient NICHT unmittelbar kompatibel mit folgenden Profilen ist:\n\n* [Profil EPAPatient der gematik](https://gematik.de/fhir/epa/StructureDefinition/epa-patient): In ISiK ist die Angabe einer KVNR nicht verpflichtend, da in vielen Use Cases bereits eine PID ausreichend ist. Außerdem ist in ISiK keine verpflichtende Versionierung über meta.versionId vorgesehen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/ISiKPatientTest"
        },
        "name" : "ISiKPatientTest",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKPersonImGesundheitsberuf"
        },
        "name" : "ISiKPersonImGesundheitsberuf",
        "description" : "Dieses Profil ermöglicht die Nutzung von in Gesundheitsberufen tätigen Personen in ISiK Szenarien.\n### Motivation\n\nDas Profil ISIKPersonImGesundheitsberuf bildet alle denkbaren medizinischen Leistungserbringer und Fachexperten  ab. In den ISiK-FHIR-Profilen können PersonImGesundheitsberuf bspw. als Ausführende einer Prozedur auftreten, im Element `performer` der Procedure Ressource, oder als die Person, die eine Diagnose stellt, im Element `asserter` der Condition Ressource.\n\nIn FHIR werden PersonImGesundheitsberuf mit der [`Practitioner`](https://hl7.org/fhir/R4/practitioner.html)-Ressource\n repräsentiert.  \n Für das Profil ISIKPersonImGesundheitsberuf wird eine Kompatibilität mit folgenden Profilen angestrebt; allerdings kann nicht sichergestellt werden, dass Instanzen, die gegen ISIKPatient valide sind, auch valide sind gegen:\n* [Profil KBV_PR_Base_Practitioner der KBV Basisprofile](https://fhir.kbv.de/StructureDefinition/KBV_PR_Base_Practitioner). \n* [Profil HiGHmed_IC_Practitioner, MI Initiative - HiGHmed Use Case Infection Control der  Medizininformatik Initiative ](https://simplifier.net/medizininformatikinitiative-highmed-ic/highmed-ic-practitioner)\n* [Profil TIPractitioner der gematik](https://gematik.de/fhir/ti/StructureDefinition/ti-practitioner)  \n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKProzedur"
        },
        "name" : "ISiKProzedur",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die Behandlungen/Prozeduren eines Patienten im Rahmen des Bestätigungsverfahrens der gematik.\n### Motivation\nDie Möglichkeit auf eine Übersicht der Prozeduren eines Patienten zuzugreifen, Patienten anhand durchgeführter oder geplanter Prozeduren zu suchen, oder zu prüfen, ob eine konkrete Prozedur bei einem Patienten durchgeführt wurde, sind wichtige Funktionen im klinischen Behandlungsablauf.\n\nIn FHIR werden Prozeduren mit der Procedure-Ressource repräsentiert.\n\nDa die Prozeduren in klinischen Primärsystemen, in der Regel, in OPS-codierter Form vorliegen, fordert ISiK in erster Linie diese Form des Austausches. Falls eine Prozedur zwar dokumentiert aber noch nicht codiert wurde (z.B. wenn die Kodierung erst nach der Entlassung erfolgt), ist alternativ eine Repräsentation als Freitext-Prozedur möglich.\n\n### Kompatibilität\nFür das Profil ISIKProzedur wird eine Kompatibilität mit folgenden Profilen angestrebt; allerdings kann nicht sichergestellt werden, dass Instanzen, die gegen ISIKProzedur valide sind, auch valide sind gegen:\n\n* [Profil Prozedur](https://www.medizininformatik-initiative.de/fhir/core/modul-prozedur/StructureDefinition/Procedure) der Medizininformatik Initiative  \nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKPZNCoding"
        },
        "name" : "ISiKPZNCoding",
        "description" : "Data Type profile for ATC Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKRaucherStatusBeispiel"
        },
        "name" : "ISiKRaucherStatusBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKRaucherStatus"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSauerstoffsaettigungArteriell"
        },
        "name" : "ISiKSauerstoffsaettigungArteriell",
        "description" : "Dieses Profil spezifiziert die Minimalanforderungen für die Bereitstellung von Informationen über die arterielle Sauerstoffsättigung eines Patienten im Rahmen der interoperablen Kommunikation gemäß den Vorgaben der ISiK (Interoperable Schnittstelle im Krankenhaus).\n### Motivation\nDie Erfassung und Überwachung der arteriellen Sauerstoffsättigung ist essenziell für die Beurteilung der respiratorischen Funktion, die Überwachung von Patienten mit Atemwegserkrankungen sowie die Unterstützung klinischer Entscheidungen, insbesondere in kritischen Versorgungssituationen.\n\nIn FHIR wird die arterielle Sauerstoffsättigung mit der Observation-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKSauerstoffsaettigungArteriell ist vom Profil [VitalSignDE_Arterielle_Sauerstoffsaettigung_Pulsoximetrie](http://fhir.de/StructureDefinition/observation-de-vitalsign-sauerstoffsaettigung-pulsoximetrie) aus den deutschen Basisprofilen abgeleitet. Es ist kompatibel mit dem Profil [Observation Oxygen Saturation Profile](http://hl7.org/fhir/StructureDefinition/oxygensat) aus der FHIR R4 Spezifikation.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKSauerstoffsaettigungArteriellExample"
        },
        "name" : "ISiKSauerstoffsaettigungArteriellExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSauerstoffsaettigungArteriell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKSauerstoffsaettigungArteriellMaxExample"
        },
        "name" : "ISiKSauerstoffsaettigungArteriellMaxExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSauerstoffsaettigungArteriell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKSauerstoffsaettigungArteriellMinExample"
        },
        "name" : "ISiKSauerstoffsaettigungArteriellMinExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSauerstoffsaettigungArteriell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKSchwangerschaftErwarteterEntbindungsterminBeispiel"
        },
        "name" : "ISiKSchwangerschaftErwarteterEntbindungsterminBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSchwangerschaftErwarteterEntbindungstermin"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKSchwangerschaftsstatusBeispiel"
        },
        "name" : "ISiKSchwangerschaftsstatusBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSchwangerschaftsstatus"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSnomedCTCoding"
        },
        "name" : "ISiKSnomedCTCoding",
        "description" : "Data Type profile for Snomed-CT Codings in ISiK",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKStandort"
        },
        "name" : "ISiKStandort",
        "description" : "Dieses Profil dient der strukturierten Erfassung von Standortangaben eines \nKrankenhauses oder von Organisationseinheiten innerhalb eines Krankenhauses in ISiK-Szenarien.  \n### Motivation\nIn FHIR wird die Organisation (Organization) vom Standort (Location) eindeutig abgegrenzt.\n\nDie Abbildung von Standorten in einem Krankenhaus unterstützt u.a. die Raum- und Bettenbelegung in strukturierter Form. \n\nDie Erfassung des Standortes in strukturierter Form soll u.a. ermöglichen:\n- Zuweisungen von Diensten an bestimmte Standorte im Rahmen des Terminmanagements\n- Die Raum- und Betten-Belegung in strukturierter Form (interdisziplinär) - u.a. für \n    - Patientenportale im Rahmen der Terminbuchung, z.B. um den Wunsch nach Einzelbett, bzw. 1 oder 2 Betten abzubilden\n    - KIS und weitere Subsysteme:\n      - zur Patientenabholung und Information für den Transportdienst\n      - Abbildung der Verfügbarkeit eines spezifischen Bettenstellplatzes (z.B. mit spezifischem Monitoring-Device) \n- Im Rahmen der Versorgung kann eine der folgenden Beispiel-Fragen beantworten werden:\n    - Handelt es sich um ein Isolationszimmer?\n    - Gibt es bestimmte Ausstattung, z.B. Beatmungsgeräte?\n    - etc.\n\nDafür werden Standort-Profile in unterschiedlicher Granularität definiert. \n\n### Kompatibilität\nFür das Profil ISiKStandort wurde bis zum Zeitpunkt der Veröffentlichung kein Abgleich der \nKompatibilität zu anderen Profilen (der KBV und der Medizininformatik-Initiative) durchgeführt.  \nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKStandortBettenstellplatz"
        },
        "name" : "ISiKStandortBettenstellplatz",
        "description" : "Dieses Profil dient der strukturierten Erfassung von Bettenstellplätzen (als Standorten) \neines Krankenhauses.  \n### Hinweis  \nEin einzelnes Bett als Gegenstand kann als FHIR-Ressource 'Device' abgebildet werden, \ndas einen Bettenstellplatz referenziert.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKStandortRaum"
        },
        "name" : "ISiKStandortRaum",
        "description" : "Dieses Profil dient der strukturierten Erfassung von Räumen (als Standorten) eines Krankenhauses.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKStillstatus"
        },
        "name" : "ISiKStillstatus",
        "description" : "Profil zur Abbildung ob gestillt/Muttermilch abgepumpt und gefüttert wird",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/ISiKStillstatusBeispiel"
        },
        "name" : "ISiKStillstatusBeispiel",
        "description" : "ISiKStillstatusBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKStillstatus"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKSubscriptionNotification"
        },
        "name" : "ISiKSubscriptionNotification",
        "description" : "ISiKSubscriptionNotification",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Parameters"
          }
        ],
        "reference" : {
          "reference" : "Parameters/ISiKSubscriptionStatusExample"
        },
        "name" : "ISiKSubscriptionStatusExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSubscriptionStatus"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKSubscriptionTopicVS"
        },
        "name" : "ISiKSubscriptionTopic ValueSet",
        "description" : "ValueSet, das alle Codes des ISiKSubscriptionTopic CodeSystems enthält",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKTermin"
        },
        "name" : "ISiKTermin",
        "description" : "Das Datenobjekte ISiKTermin repräsentiert einen gebuchten Termin, sowie einen Terminvorschlag.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKTerminblock"
        },
        "name" : "ISiKTerminblock",
        "description" : "Die Slot-Ressource repräsentiert die Verbindung eines Termins (Appointment) und den dazugehörigen Ressourcen (z.B. HealthcareService, Device, Practitioner). Für diese Ressourcen können separate Kalender (Schedules) verwaltet werden. Der Slot agiert als Verbindungsstück zwischen diesen Ressourcen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Slot"
          }
        ],
        "reference" : {
          "reference" : "Slot/ISiKTerminblockExample"
        },
        "name" : "ISiKTerminblockExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKTerminblock"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKTerminCancelationReason"
        },
        "name" : "ISiKTerminCancelationReason",
        "description" : "Enthaelt alle erlaubten Gruende fuer eine Stornierung eines ISiKTermins",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Appointment"
          }
        ],
        "reference" : {
          "reference" : "Appointment/ISiKTerminExample"
        },
        "name" : "ISiKTerminExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKTermin"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Appointment"
          }
        ],
        "reference" : {
          "reference" : "Appointment/ISiKTerminExampleExtendedICU"
        },
        "name" : "ISiKTerminExampleExtendedICU",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKTermin"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKTerminKontaktMitGesundheitseinrichtung"
        },
        "name" : "ISiKTerminKontaktMitGesundheitseinrichtung",
        "description" : "Das Datenobjekt ISiKKontaktMitGesundheitseinrichtung dient der Verknüpfung des ISiK-Basis-Encounters (ISiKKontaktMitGesundheitseinrichtung) mit einem Termin (Appointment) und - darauf aufbauend - der Dokumentenkommunikation.\n\nDie Anforderung dieser Verknüpfung stammt aus dem Szenario der Dokument-Übertragung zwischen Patientenportal und krankenhaus-internem Primärsystem (KIS): Dokumente liegen bei Termin-Buchung erst im Patientenportal (im Appointment) vor und werden erst mit Anlage des Encounters in das KIS (etc.) übermittelt. Dazu muss das Appointment mit dem neu angelegten Encounter verknüpft werden, um die Dokumente aus dem Patientenportal darüber zuzuordnen.\n\nHieraus folgt, dass das Datenobjekt nur relevant ist, falls das bestätigungsrelevante System das Datenobjekt ISiKKontaktMitGesundheitseinrichtung sowie ISiKTermin implementiert. Zu Beginn des Termins sollte das System die Verknüpfung zwischen Encounter und Appointment herstellen. Ausgenommen hiervon sind Termine, die nicht stattfinden, da für diese in der Regel keine Encounter angelegt werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKTerminPriority"
        },
        "name" : "ISiKTerminPriority",
        "description" : "Enthaelt alle SNOMED Codes, die eine valide Priorität für den ISiKTermin sind",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKTerminPriorityExtension"
        },
        "name" : "ISiKTerminPriorityExtension",
        "description" : "Diese Extension ermöglicht die strukturierte Angabe der Dringlichkeit (Priorität) eines Termins. Dies ist wichtig, um Notfälle oder besonders dringliche Termine im Buchungs- und Verwaltungssystem deutlich zu kennzeichnen und eine priorisierte Bearbeitung zu ermöglichen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/ISiKUnterbrechungRehaCS"
        },
        "name" : "ISiKUnterbrechungReha",
        "description" : "ISiK Unterbrechung Reha. Dokumentiert die relevanten Gründe einer Unterbrechung einer Rehabilitationsmaßnahme im Einzelfall. Vgl. Schlüsseltabelle 2.111 Erläuterung zur Unterbrechung.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKUnterbrechungReha"
        },
        "name" : "ISiKUnterbrechungRehaVS",
        "description" : "ISiK Unterbrechung Reha. Dokumentiert die relevanten Gründe einer Unterbrechung einer Rehabilitationsmaßnahme im Einzelfall. Vgl. Schlüsseltabelle 2.111 Erläuterung zur Unterbrechung.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKValueSet"
        },
        "name" : "ISiKValueSet",
        "description" : "Dieses Profil beschreibt die maschinenlesbare Auswahl von Codes \nfür die Kodierung spezifischer FHIR-Elemente in ISiK-Szenarien.\n### Motivation\n\nISiK erlaubt in diversen Kontexten die Erweiterung der Kodierung durch Krankenhaus- / System-interne Kodierungen.\nMittels der Veröffentlichung von ValueSets können Auswahllisten für externe Clients bereitgestellt werden, sodass diese entsprechende Kodierungen ebenfalls anbieten können.\n### Kompatibilität\n\nFür das Profil ISiKValueSet wurde bis zum Zeitpunkt der Veröffentlichung kein Abgleich der Kompatibilität zu anderen Profilen (der KBV und der Medizininformatik-Initiative) durchgeführt.\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ISiKValueSetExample"
        },
        "name" : "ISiKValueSetExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKValueSet"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKVersicherungsverhaeltnisGesetzlich"
        },
        "name" : "ISiKVersicherungsverhaeltnisGesetzlich",
        "description" : "Dieses Profil ermöglicht die Darstellung eines gesetzlichen Versicherungsverhältnisses in ISiK Szenarien.  \n### Motivation\nISiK unterstützt Anwendungsszenarien, in denen durch das Krankenhaus erbrachte Leistungen erfasst oder gegenüber Kostenträgern abgerechnet werden.\nIn diesen Anwendungsszenarien wird das Versicherungsverhältnis verwendet, um bspw. den Versicherungsstatus oder die Rechnungsanschrift der Versicherung zu ermitteln.  \nIn FHIR werden Versicherungsverhältnisse mit der Coverage-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKVersicherungsverhaeltnisGesetzlich basiert auf dem [GKV-Profil der deutschen Basisprofile](http://fhir.de/StructureDefinition/coverage-de-basis). \nInstanzen, die gegen ISiKVersicherungsverhaeltnisGesetzlich valide sind, sind auch valide gegen\n\n* [GKV-Profil der deutschen Basisprofile](http://fhir.de/StructureDefinition/coverage-de-basis)\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKVersicherungsverhaeltnisSelbstzahler"
        },
        "name" : "ISiKVersicherungsverhaeltnisSelbstzahler",
        "description" : "Dieses Profil ermöglicht die Darstellung eines gesetzlichen Versicherungsverhältnisses in ISiK Szenarien.  \n### Motivation\nISiK unterstützt Anwendungsszenarien, in denen durch das Krankenhaus erbrachte Leistungen erfasst oder gegenüber Kostenträgern abgerechnet werden.\nIn diesen Anwendungsszenarien wird das Versicherungsverhältnis verwendet, um bspw. den Versicherungsstatus oder die Rechnungsanschrift der Versicherung zu ermitteln.  \nIn FHIR werden Versicherungsverhältnisse mit der Coverage-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKVersicherungsverhaeltnisSelbstzahler basiert auf dem [Selbstzahler-Profil der deutschen Basisprofile](https://fhir.de/StructureDefinition/coverage-de-sel). \nInstanzen, die gegen ISiKVersicherungsverhaeltnisSelbstzahler valide sind, sind auch valide gegen\n\n* [Selbstzahler-Profil der deutschen Basisprofile](https://fhir.de/StructureDefinition/coverage-de-sel)\n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKVersicherungsverhaeltnisSonstige"
        },
        "name" : "ISiKVersicherungsverhaeltnisSonstige",
        "description" : "Dieses Profil ermöglicht die Darstellung sonstiger Versicherungsverhältnisses in ISiK Szenarien.  \n### Motivation\nISiK unterstützt Anwendungsszenarien, in denen durch das Krankenhaus erbrachte Leistungen erfasst oder gegenüber Kostenträgern abgerechnet werden, \nbei denen es sich *weder* um gesetzliche Versicherungen noch Selbstzahlerverhältnisse handelt.\nIn diesen Anwendungsszenarien wird das Versicherungsverhältnis verwendet, um bspw. den Versicherungsstatus oder die Rechnungsanschrift der Versicherung zu ermitteln.  \nIn FHIR werden Versicherungsverhältnisse mit der Coverage-Ressource repräsentiert.\n\n### Kompatibilität\nDas Profil ISiKVersicherungsverhaeltnisSonstige basiert auf dem [Basis-Coverage-Profil der deutschen Basisprofile](http://fhir.de/StructureDefinition/coverage-de-basis). \n\nHinweise zu Inkompatibilitäten können über die [Portalseite](https://service.gematik.de/servicedesk/customer/portal/16) gemeldet werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpergewicht-Percentile-altersabhaengig"
        },
        "name" : "Koerpergewicht-Percentile-altersabhaengig",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpergewicht-percentil-altersabhaengig"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpergroesse-Percentil"
        },
        "name" : "Koerpergroesse-Percentil",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpergroesse-percentil-altersabhaengig"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Achsel"
        },
        "name" : "Koerpertemperatur-Achsel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-achsel"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Atemwege"
        },
        "name" : "Koerpertemperatur-Atemwege",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-atemwege"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Blut"
        },
        "name" : "Koerpertemperatur-Blut",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-blut"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Brust"
        },
        "name" : "Koerpertemperatur-Brust",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-brust"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Brustwirbelsaeule"
        },
        "name" : "Koerpertemperatur-Brustwirbelsaeule",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-brustwirbelsaeule"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Gelenk"
        },
        "name" : "Koerpertemperatur-Gelenk",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-gelenk"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Halswirbelsaeule"
        },
        "name" : "Koerpertemperatur-Halswirbelsaeule",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-halswirbelsaeule"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Harnblase"
        },
        "name" : "Koerpertemperatur-Harnblase",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-harnblase"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Kern"
        },
        "name" : "Koerpertemperatur-Kern",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-kern"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Leiste"
        },
        "name" : "Koerpertemperatur-Leiste",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-leiste"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Lendenwirbelsaeule"
        },
        "name" : "Koerpertemperatur-Lendenwirbelsaeule",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-lendenwirbelsaeule"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Myokard"
        },
        "name" : "Koerpertemperatur-Myokard",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-myokard"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-nasal"
        },
        "name" : "Koerpertemperatur-nasal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-nasal"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Nasen-Rachen-Raum"
        },
        "name" : "Koerpertemperatur-Nasen-Rachen-Raum",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-nasen-rachen-raum"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Oral"
        },
        "name" : "Koerpertemperatur-Oral",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-unter-der-zunge"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-rektal"
        },
        "name" : "Koerpertemperatur-rektal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-rektal"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Speiseroehre"
        },
        "name" : "Koerpertemperatur-Speiseroehre",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-speiseroehre"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Stirn"
        },
        "name" : "Koerpertemperatur-Stirn",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-stirn"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-Trommelfell"
        },
        "name" : "Koerpertemperatur-Trommelfell",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-trommelfell"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Koerpertemperatur-vaginal"
        },
        "name" : "Koerpertemperatur-vaginal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-vaginal"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Organization"
          }
        ],
        "reference" : {
          "reference" : "Organization/KrankenhausOrganisationBeispiel"
        },
        "name" : "KrankenhausOrganisationBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKOrganisation"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksatrialer-Druck"
        },
        "name" : "Linksatrialer-Druck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksatrialer-druck"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksvent-Schlagvolumenindex-Durch-Indikatorverduennung"
        },
        "name" : "Linksvent-Schlagvolumenindex-Durch-Indikatorverduennung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-schlagvolumenindex-durch-indikatorverd"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaerer-Druck"
        },
        "name" : "Linksventrikulaerer-Druck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaerer-druck"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaerer-Herzindex"
        },
        "name" : "Linksventrikulaerer-Herzindex",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaerer-herzindex"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaerer-Herzindex-Durch-Indikatorverduennung"
        },
        "name" : "Linksventrikulaerer-Herzindex-Durch-Indikatorverduennung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-herzindex-durch-indikatorverduennung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaeres-Herzzeitvolumen-durch-Indikatorverduennung"
        },
        "name" : "Linksventrikulaeres-Herzzeitvolumen-durch-Indikatorverduennung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-herzzeitvolumen-durch-indikatorverd"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaeres-Schlagvolumen"
        },
        "name" : "Linksventrikulaeres-Schlagvolumen",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaeres-schlagvolumen"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaeres-Schlagvolumen-Durch-Indikatorverduennung"
        },
        "name" : "Linksventrikulaeres-Schlagvolumen-Durch-Indikatorverduennung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventri-schlagvolumen-durch-indikatorverduennung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Linksventrikulaeres-Schlagvolumenindex"
        },
        "name" : "Linksventrikulaeres-Schlagvolumenindex",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-linksventrikulaeres-schlagvolumenindex"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:complex-type"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/MedicationQuantity"
        },
        "name" : "Medication Quantity",
        "description" : "Quantity Datentyp der die Nutzung von UCUM vorgibt. Bei dimensionslosen Einheiten wie 'Tablette' wird ein code von '1' erwartet, 'Tablette' kann als String in Unit hinterlegt werden.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/MedikationsListeListModeVS"
        },
        "name" : "Medikationslisten-Modes",
        "description" : "Erlaubte ListModes der ISiK MedikationsListe",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/MittelgradigeIntelligenzminderung"
        },
        "name" : "MittelgradigeIntelligenzminderung",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExampleExtractWithUnit"
        },
        "name" : "Observation Based Extraction bei quantitativen Angaben",
        "description" : "### Beispiel-Questionnaire mit Observation Based Extraction von Dezimalwerten mit Maßeinheiten  \n  * Vorgabe der anzugebenden Maßeinheit mittels [questionnaire-unit](https://hl7.org/fhir/R4/extension-questionnaire-unit.html)-Extension\n  * Annotation zur Extraktion mittels [observationExtract](http://hl7.org/fhir/uv/sdc/StructureDefinition/sdc-questionnaire-observationExtract)\n  * Annotation zum Setzen der category bei Extraktion mittels [observationExtractCategory](http://hl7.org/fhir/uv/sdc/StructureDefinition/sdc-questionnaire-observationExtract-category)",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesCRP"
        },
        "name" : "ObservationCodesCRP",
        "description" : "Enthält LOINC-Codes für die Observation CRP",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesGFR"
        },
        "name" : "ObservationCodesGFR",
        "description" : "Enthält LOINC-Codes für die Observation GFR",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesHb"
        },
        "name" : "ObservationCodesHb",
        "description" : "Enthält LOINC-Codes für die Observation Hb",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesPCT"
        },
        "name" : "ObservationCodesPCT",
        "description" : "Enthält LOINC-Codes für die Observation PCT",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesSerumkreatinin"
        },
        "name" : "ObservationCodesSerumkreatinin",
        "description" : "Enthält LOINC-Codes für die Observation Serumkreatinin",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesThrombozyten"
        },
        "name" : "ObservationCodesThrombozyten",
        "description" : "Enthält LOINC-Codes für die Observation Thrombozyten",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesTroponin"
        },
        "name" : "ObservationCodesTroponin",
        "description" : "Enthält LOINC-Codes für die Observation Troponin",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationCodesTSH"
        },
        "name" : "ObservationCodesTSH",
        "description" : "Enthält LOINC-Codes für die Observation TSH",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsCRP"
        },
        "name" : "ObservationUnitsCRP",
        "description" : "Enthält UCUM-Einheiten für die Observation CRP",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsGFR"
        },
        "name" : "ObservationUnitsGFR",
        "description" : "Enthält UCUM-Einheiten für die Observation GFR",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsHb"
        },
        "name" : "ObservationUnitsHb",
        "description" : "Enthält UCUM-Einheiten für die Observation Hb",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsPCT"
        },
        "name" : "ObservationUnitsPCT",
        "description" : "Enthält UCUM-Einheiten für die Observation PCT",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsSerumkreatinin"
        },
        "name" : "ObservationUnitsSerumkreatinin",
        "description" : "Enthält UCUM-Einheiten für die Observation Serumkreatinin",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsThrombozyten"
        },
        "name" : "ObservationUnitsThrombozyten",
        "description" : "Enthält UCUM-Einheiten für die Observation Thrombozyten",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsTroponin"
        },
        "name" : "ObservationUnitsTroponin",
        "description" : "Enthält UCUM-Einheiten für die Observation Troponin",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ObservationUnitsTSH"
        },
        "name" : "ObservationUnitsTSH",
        "description" : "Enthält UCUM-Einheiten für die Observation TSH",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Medication"
          }
        ],
        "reference" : {
          "reference" : "Medication/ParacetamolInfusion"
        },
        "name" : "ParacetamolInfusion",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKMedikament"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Parameters"
          }
        ],
        "reference" : {
          "reference" : "Parameters/ParametersExampleUpdateMetadata"
        },
        "name" : "ParametersExampleUpdateMetadata",
        "description" : "Example of an input parameter for the request body for the update-metadata operation",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/PatientinMinimal"
        },
        "name" : "PatientinMinimal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/PatientinMusterfrau"
        },
        "name" : "PatientinMusterfrau",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/PatientinMusterfrauMinimal"
        },
        "name" : "PatientinMusterfrauMinimal",
        "description" : "Minimalbeispiel für Patientin Musterfrau",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/PatientinNormal"
        },
        "name" : "PatientinNormal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Subscription"
          }
        ],
        "reference" : {
          "reference" : "Subscription/PatientMergeSubscriptionExample"
        },
        "name" : "PatientMergeSubscriptionExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSubscription"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/PlannedEndDate"
        },
        "name" : "PlannedEndDate",
        "description" : "Diese Erweiterung dokumentiert das geplante Enddatum bzw. den geplanten Endzeitpunkt eines Encounters. Sie unterstützt die Vorausplanung von Aufenthalten oder Behandlungen, beispielsweise für die Ressourcenplanung, Terminverwaltung und für die Kommunikation mit nachfolgenden Einrichtungen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/PlannedStartDate"
        },
        "name" : "PlannedStartDate",
        "description" : "Diese Extension dient der Erfassung des geplanten Startzeitpunkts (dateTime) eines Encounters, z. B. einer stationären Aufnahme, Operation oder eines Termins. Sie ermöglicht eine strukturierte Terminplanung, erleichtert die Koordination verschiedener Versorgungsprozesse und verbessert die Kommunikation zwischen Systemen und Leistungserbringern.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Practitioner"
          }
        ],
        "reference" : {
          "reference" : "Practitioner/PractitionerWalterArzt"
        },
        "name" : "PractitionerWalterArzt",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPersonImGesundheitsberuf"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/PrimaereGonarthroseMinimal"
        },
        "name" : "PrimaereGonarthroseMinimal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/PrimaereGonarthroseNormal"
        },
        "name" : "PrimaereGonarthroseNormal",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ProzedurenCodesSCT"
        },
        "name" : "ProzedurenCodesSCT",
        "description" : "Enthaelt alle SNOMED Procedure Codes",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/ProzedurenKategorieSCT"
        },
        "name" : "ProzedurenKategorieSCT",
        "description" : "Enthaelt alle SNOMED Codes für ein Mapping der OPS Klassentitel",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Pulmonalarterieller-Blutdruck"
        },
        "name" : "Pulmonalarterieller-Blutdruck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-pulmonalarterieller-blutdruck"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Pulmonalarterieller-wedge-Blutdruck"
        },
        "name" : "Pulmonalarterieller-wedge-Blutdruck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-pulmonalarterieller-wedge-druck"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Pulmonalvaskulaerer-Widerstandsindex"
        },
        "name" : "Pulmonalvaskulaerer-Widerstandsindex",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-pulmonalvaskulaerer-widerstandsindex"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Puls"
        },
        "name" : "Puls",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-puls"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/BackportSubscriptionStatusR4Fixed"
        },
        "name" : "R4 Backported R5 SubscriptionStatus",
        "description" : "Profil auf der FHIR-R4-Resource Parameters zur Unterstützung themenbasierter Subscription-Benachrichtigungen in R4.\n\nDieses Profil ist funktional identisch mit `http://hl7.org/fhir/uv/subscriptions-backport/StructureDefinition/backport-subscription-status-r4`.  \nDie Version 1.1.0 des offiziellen Profils weist jedoch technische Fehler auf. Daher wurde es hier als Workaround erneut implementiert.\nDiese lokale Definition wird durch das offizielle `backport-subscription-status-r4` Profil ersetzt, sobald eine korrigierte Version veröffentlicht wurde.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/BackportSubscriptionNotificationR4Fixed"
        },
        "name" : "R4 Topic-Based Subscription Notification Bundle",
        "description" : "Profil auf der FHIR-R4-Resource Bundle, um R5-ähnliche, themenbasierte Subscription-Benachrichtigungen in FHIR R4 zu ermöglichen.\n\nDieses Profil ist funktional identisch mit `http://hl7.org/fhir/uv/subscriptions-backport/StructureDefinition/backport-subscription-notification-r4`.  \nDie Version 1.1.0 des offiziellen Profils enthält jedoch technische Fehler. Daher wurde dieses Profil lokal als temporärer Workaround nachgebildet.\nEs wird durch das offizielle `backport-subscription-notification-r4` Profil ersetzt, sobald eine korrigierte Version veröffentlicht wurde.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Location"
          }
        ],
        "reference" : {
          "reference" : "Location/RaumStandortBeispiel"
        },
        "name" : "RaumStandortBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKStandortRaum"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Rechtsatrialer-Druck"
        },
        "name" : "Rechtsatrialer-Druck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-rechtsatrialer-druck"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Rechtsventrikulaerer-Druck"
        },
        "name" : "Rechtsventrikulaerer-Druck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-rechtsventrikulaerer-druck"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Sauerstoffsaettigung-im-Arteriellen-Blut-durch-Pulsoxymetrie"
        },
        "name" : "Sauerstoffsaettigung-im-Arteriellen-Blut-durch-Pulsoxymetrie",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-o2saettigung-im-arteriellen-blut-durch-pulsoxymetrie"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Sauerstoffsaettigung-im-Blut-Postduktal-durch-Pulsoxymetrie"
        },
        "name" : "Sauerstoffsaettigung-im-Blut-Postduktal-durch-Pulsoxymetrie",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-o2saettigung-im-blut-postduktal-durch-pulsoxymetrie"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Sauerstoffsaettigung-im-Blut-Preduktal-durch-Pulsoxymetrie"
        },
        "name" : "Sauerstoffsaettigung-im-Blut-Preduktal-durch-Pulsoxymetrie",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-o2saettigung-im-blut-preduktal-durch-pulsoxymetrie"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:extension"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ScheduleName"
        },
        "name" : "ScheduleName",
        "description" : "Diese Erweiterung ermöglicht es, einem FHIR Schedule (Kalender) einen menschenlesbaren Namen zuzuweisen, der eine schnelle Identifikation und Unterscheidung mehrerer Kalender in Terminplanungsanwendungen erlaubt. Der Name dient zur besseren Übersichtlichkeit, z. B. bei der Auswahl eines Kalenders durch Nutzer oder in Verwaltungsoberflächen für Terminressourcen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/SchwangerschaftEtMethodeVS"
        },
        "name" : "Schwangerschaft Erwarteter Entbindungstermin Methode",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/SchwangerschaftsstatusVS"
        },
        "name" : "Schwangerschaftsstatus Valueset",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/SctRouteOfAdministration"
        },
        "name" : "SctRouteOfAdministration",
        "description" : "Enthaelt alle SNOMED CT Administrationsarten",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-herzzeitvolumen"
        },
        "name" : "SD MII ICU Herzzeitvolumen",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des Herzzeitvolumens in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-ideales-koerpergewicht"
        },
        "name" : "SD MII ICU Ideales Koerpergewicht",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des idealen Körpergewichts in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-intrakranieller-druck-icp"
        },
        "name" : "SD MII ICU Intrakranieller Druck ICP",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des intrakraniellen Drucks (ICP) in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpergewicht-percentil-altersabhaengig"
        },
        "name" : "SD MII ICU Koerpergewicht Percentil Altersabhaengig",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des altersabhängigen Körpergewicht-Perzentils in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpergroesse-percentil-altersabhaengig"
        },
        "name" : "SD MII ICU Koerpergroesse Percentil",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des altersabhängigen Körpergrößen-Perzentils in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-achsel"
        },
        "name" : "SD MII ICU Koerpertemperatur Achsel",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen in der Achsel in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-atemwege"
        },
        "name" : "SD MII ICU Koerpertemperatur Atemwege",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung in den Atemwegen in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-blut"
        },
        "name" : "SD MII ICU Koerpertemperatur Blut",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten Körperkerntemperatur gemessen im Blut in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-brust"
        },
        "name" : "SD MII ICU Koerpertemperatur Brust",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung an der Brust in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-brustwirbelsaeule"
        },
        "name" : "SD MII ICU Koerpertemperatur Brustwirbelsaeule",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung an der Brustwirbelsäule in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-gelenk"
        },
        "name" : "SD MII ICU Koerpertemperatur Gelenk",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung am Gelenk in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-generisch"
        },
        "name" : "SD MII ICU Koerpertemperatur Generisch",
        "description" : "Dieses Profil bietet eine abstrahierte Schicht zur Körpertemperaturmessung in der Akutmedizin. Es ist generisch im Sinne der Profil-Abstraktion, allerdings explizit nicht im Sinne einer KörperKERNtemperatur zu verwenden (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-halswirbelsaeule"
        },
        "name" : "SD MII ICU Koerpertemperatur Halswirbelsaeule",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung an der Halswirbelsäule in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-harnblase"
        },
        "name" : "SD MII ICU Koerpertemperatur Harnblase",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten Körperkerntemperatur gemessen in der Harnblase in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-kern"
        },
        "name" : "SD MII ICU Koerpertemperatur Kern",
        "description" : "Dieses Profil bietet eine generische Abbildung der geschätzten KörperKERNtemperatur in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-leiste"
        },
        "name" : "SD MII ICU Koerpertemperatur Leiste",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen in der Leiste in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-lendenwirbelsaeule"
        },
        "name" : "SD MII ICU Koerpertemperatur Lendenwirbelsaeule",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung im Bereich der Lendenwirbelsäule. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-myokard"
        },
        "name" : "SD MII ICU Koerpertemperatur Myokard",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung im Myokard (Herzmuskel). Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-nasal"
        },
        "name" : "SD MII ICU Koerpertemperatur nasal",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung im Nasenbereich in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-nasen-rachen-raum"
        },
        "name" : "SD MII ICU Koerpertemperatur Nasen-Rachen-Raum",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung im Nasen-Rachen-Raum in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-rektal"
        },
        "name" : "SD MII ICU Koerpertemperatur rektal",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen rektal in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-speiseroehre"
        },
        "name" : "SD MII ICU Koerpertemperatur Speiseroehre",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen in der Speiseröhre in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-stirn"
        },
        "name" : "SD MII ICU Koerpertemperatur Stirn",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Körpertemperaturmessung an der Stirn in der Akutmedizin. Es dient nicht der Abbildung der KörperKERNtemperatur (siehe dafür Profile zu Körperkerntemperatur im generischen Modul Vitalparameter bzw. abgeleitete Profile im ICU-Bereich).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-trommelfell"
        },
        "name" : "SD MII ICU Koerpertemperatur Trommelfell",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen im Trommelfell in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-unter-der-zunge"
        },
        "name" : "SD MII ICU Koerpertemperatur unter der Zunge",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen unter der Zunge in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-koerpertemperatur-vaginal"
        },
        "name" : "SD MII ICU Koerpertemperatur vaginal",
        "description" : "Dieses Profil bietet eine spezialisierte Abbildung der geschätzten KörperKERNtemperatur gemessen vaginal in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksatrialer-druck"
        },
        "name" : "SD MII ICU Linksatrialer Druck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksatrialen Drucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventrikulaerer-druck"
        },
        "name" : "SD MII ICU Linksventrikulaerer Druck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Drucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventrikulaerer-herzindex"
        },
        "name" : "SD MII ICU Linksventrikulaerer Herzindex",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Herzindex in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventri-herzindex-durch-indikatorverduennung"
        },
        "name" : "SD MII ICU Linksventrikulaerer Herzindex durch Indikatorverduennung",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Herzindex durch Indikatorverdünnung in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventri-schlagvolumenindex-durch-indikatorverd"
        },
        "name" : "SD MII ICU Linksventrikulaerer Schlagvolumenindex Durch Indikatorverduennung",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Schlagvolumenindex durch Indikatorverdünnung in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventri-herzzeitvolumen-durch-indikatorverd"
        },
        "name" : "SD MII ICU Linksventrikulaeres Herzzeitvolumen Durch Indikatorverduennung",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Herzzeitvolumens durch Indikatorverdünnung in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventrikulaeres-schlagvolumen"
        },
        "name" : "SD MII ICU Linksventrikulaeres Schlagvolumen",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Schlagvolumens in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventri-schlagvolumen-durch-indikatorverduennung"
        },
        "name" : "SD MII ICU Linksventrikulaeres Schlagvolumen Durch Indikatorverduennung",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Schlagvolumens durch Indikatorverdünnung in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-linksventrikulaeres-schlagvolumenindex"
        },
        "name" : "SD MII ICU Linksventrikulaeres Schlagvolumenindex",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des linksventrikulären Schlagvolumenindex in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-monitoring-und-vitaldaten"
        },
        "name" : "SD MII ICU Monitoring und Vitaldaten",
        "description" : "Dieses Profil dient als Abstraktionsprofil für verschiedene spezialisierte Beobachtungen in der Akutmedizin zur Abbildung von Monitoring- und Vitaldaten.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-pulmonalarterieller-blutdruck"
        },
        "name" : "SD MII ICU Pulmonalarterieller Blutdruck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des pulmonalarteriellen Blutdrucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-pulmonalarterieller-wedge-druck"
        },
        "name" : "SD MII ICU Pulmonalarterieller Wedge Druck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des pulmonalarteriellen Wedge-Drucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-pulmonalvaskulaerer-widerstandsindex"
        },
        "name" : "SD MII ICU Pulmonalvaskulaerer Widerstandsindex",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des pulmonalvaskulären Widerstandsindex in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-puls"
        },
        "name" : "SD MII ICU Puls",
        "description" : "Dieses Profil repräsentiert Pulsuntersuchungen die nicht den Zweck einer Herzfrequenzmessung haben, sondern die Pulsfrequenz als eigenständige Vitalfunktion erfassen.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-rechtsatrialer-druck"
        },
        "name" : "SD MII ICU Rechtsatrialer Druck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des rechtsatrialen Drucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-rechtsventrikulaerer-druck"
        },
        "name" : "SD MII ICU Rechtsventrikulaerer Druck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des rechtsventrikulären Drucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-o2saettigung-im-arteriellen-blut-durch-pulsoxymetrie"
        },
        "name" : "SD MII ICU Sauerstoffsaettigung Im Arteriellen Blut Durch Pulsoxymetrie",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Sauerstoffsättigung im arteriellen Blut durch Pulsoxymetrie in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-o2saettigung-im-blut-postduktal-durch-pulsoxymetrie"
        },
        "name" : "SD MII ICU Sauerstoffsaettigung Im Blut Postduktal Durch Pulsoxymetrie",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Sauerstoffsättigung im Blut postduktal durch Pulsoxymetrie in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-o2saettigung-im-blut-preduktal-durch-pulsoxymetrie"
        },
        "name" : "SD MII ICU Sauerstoffsaettigung Im Blut Preduktal Durch Pulsoxymetrie",
        "description" : "Dieses Profil dient der spezialisierten Abbildung der Sauerstoffsättigung im Blut preduktal durch Pulsoxymetrie in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-sonstige-pulsatile-druecke-generisch"
        },
        "name" : "SD MII ICU Sonstige pulsatile Druecke Generisch",
        "description" : "Dieses Profil bietet eine abstrahierte Schicht zur Abbildung sonstiger pulsatiler Drücke in der Akutmedizin. Es ist generisch im Sinne der Profil-Abstraktion, allerdings explizit nicht im Sinne einer Blutdruckmessung (siehe dafür Profile zu Blutdruck im generischen Modul Vitalparameter).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-systemischer-vaskulaerer-widerstandsindex"
        },
        "name" : "SD MII ICU Systemischer Vaskulaerer Widerstandsindex",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des systemisch-vaskulären Widerstandsindex in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/sd-mii-icu-zentralvenoeser-blutdruck"
        },
        "name" : "SD MII ICU Zentralvenoeser Blutdruck",
        "description" : "Dieses Profil dient der spezialisierten Abbildung des zentralvenösen Blutdrucks in der Akutmedizin.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Location"
          }
        ],
        "reference" : {
          "reference" : "Location/StationStandortBeispiel"
        },
        "name" : "StationStandortBeispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKStandort"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/StillstatusVS"
        },
        "name" : "Stillstatus LOINC Antwortoptionen",
        "description" : "Dieses Valueset enthält die Codes zur Beschreibung von Stillstatus LOINC.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/SubscriptionNotificationBundleExample"
        },
        "name" : "SubscriptionNotificationBundleExample",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKSubscriptionNotification"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/subscription-notification-type"
        },
        "name" : "SubscriptionNotificationType",
        "description" : "The type of notification represented by the status message.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "CodeSystem"
          }
        ],
        "reference" : {
          "reference" : "CodeSystem/subscription-notification-type"
        },
        "name" : "SubscriptionNotificationType",
        "description" : "The type of notification represented by the status message.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/Suchergebnis-Beispiel"
        },
        "name" : "Suchergebnis-Beispiel",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenSuchergebnisse"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "StructureDefinition:resource"
          }
        ],
        "reference" : {
          "reference" : "StructureDefinition/ISiKDokumentenSuchergebnisse"
        },
        "name" : "Suchergebnisse einer Dokumentensuche",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Systemischer-vaskulaerer-Widerstandsindex"
        },
        "name" : "Systemischer-vaskulaerer-Widerstandsindex",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-systemischer-vaskulaerer-widerstandsindex"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Account"
          }
        ],
        "reference" : {
          "reference" : "Account/SZ1DRGFall"
        },
        "name" : "SZ1DRGFall",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAbrechnungsfall"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "RelatedPerson"
          }
        ],
        "reference" : {
          "reference" : "RelatedPerson/SZ1Mutter"
        },
        "name" : "SZ1Mutter",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAngehoeriger"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/SZ1Nachstationaer"
        },
        "name" : "SZ1Nachstationaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/SZ1Patient"
        },
        "name" : "SZ1Patient",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/SZ1Stationaer"
        },
        "name" : "SZ1Stationaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Coverage"
          }
        ],
        "reference" : {
          "reference" : "Coverage/SZ1VersicherungGesetzlich"
        },
        "name" : "SZ1VersicherungGesetzlich",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisGesetzlich"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Coverage"
          }
        ],
        "reference" : {
          "reference" : "Coverage/SZ1VersicherungSelbstzahler"
        },
        "name" : "SZ1VersicherungSelbstzahler",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisSelbstzahler"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/SZ1Vorstationaer"
        },
        "name" : "SZ1Vorstationaer",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Account"
          }
        ],
        "reference" : {
          "reference" : "Account/SZ2DRGFall"
        },
        "name" : "SZ2DRGFall",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKAbrechnungsfall"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Encounter"
          }
        ],
        "reference" : {
          "reference" : "Encounter/SZ2Encounter"
        },
        "name" : "SZ2Encounter",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Patient"
          }
        ],
        "reference" : {
          "reference" : "Patient/SZ2Patient"
        },
        "name" : "SZ2Patient",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKPatient"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/SZ2Primaerdiagnose"
        },
        "name" : "SZ2Primaerdiagnose",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Condition"
          }
        ],
        "reference" : {
          "reference" : "Condition/SZ2Sekundaerdiagnose"
        },
        "name" : "SZ2Sekundaerdiagnose",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Coverage"
          }
        ],
        "reference" : {
          "reference" : "Coverage/SZ2VersicherungGesetzlich"
        },
        "name" : "SZ2VersicherungGesetzlich",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisGesetzlich"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/Szenario1"
        },
        "name" : "Szenario1",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Bundle"
          }
        ],
        "reference" : {
          "reference" : "Bundle/Szenario2"
        },
        "name" : "Szenario2",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "QuestionnaireResponse"
          }
        ],
        "reference" : {
          "reference" : "QuestionnaireResponse/TestMaxDecimal0"
        },
        "name" : "TestMaxDecimal0",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "QuestionnaireResponse"
          }
        ],
        "reference" : {
          "reference" : "QuestionnaireResponse/TestMaxDecimal1"
        },
        "name" : "TestMaxDecimal1",
        "description" : "Test-Instanz für Validierungs-Fehler 'Too many decimal places'",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "QuestionnaireResponse"
          }
        ],
        "reference" : {
          "reference" : "QuestionnaireResponse/TestMaxDecimal2"
        },
        "name" : "TestMaxDecimal2",
        "description" : "Test-Instanz für Validierungs-Fehler 'Too many decimal places'",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "QuestionnaireResponse"
          }
        ],
        "reference" : {
          "reference" : "QuestionnaireResponse/TestMaxDecimal3"
        },
        "name" : "TestMaxDecimal3",
        "description" : "Test-Instanz für Validierungs-Fehler 'Too many decimal places'",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDaten"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "OperationDefinition"
          }
        ],
        "reference" : {
          "reference" : "OperationDefinition/UpdateMetadata"
        },
        "name" : "update-metadata",
        "description" : "\n## Interaktion: Update von Metadaten, Löschen von Dokumenten\n\nDie Operation ``UpdateMetadata`` ermöglicht es, unkritische Metadaten gezielt und kontrolliert zu aktualisieren oder vorläufige Dokumente durch Setzen des Status entered-in-error zuverlässig zu löschen, ohne ein neues Dokument anlegen zu müssen.\n\n### Herstellung von Dokumentenkontext\nDer Client muss zunächst die URL der DocumentReference ermitteln, auf die das Update angewendet werden soll. Hierzu kann die Interaktion {{pagelink:Dokumentenabfrage, text:Dokumentenabfrage}} verwendet werden.\n\n### Metadatenupdate\nDas Update der Metadaten erfolgt mittels der `$update-metadata` Operation.\nHinweis: Der zum Zeitpunkt der Erstellung dieser Spezifikation vorliegende IHE-MHD-Implementierungsleitfaden sieht kein Metadatenupdate vor. Hier müsste stets ein neues Dokument übermittelt werden.\n\nFür den ISiK Use Case als maßgeblich relevant und unkritisch in Bezug auf die Versionierung hat sich jedoch das Element `docStatus`erwiesen, welches im IHE-Kontext keine Berücksichtigung findet. Im einrichtungsinternen Dokumentenaustausch kommt es häufig vor, dass sich der Status eines Dokumentes ändert (z.b. `preliminary` -> `final`), ohne dass dies Auswirkungen auf den Inhalt hat. Die Anlage eines neuen Dokumentes wäre in diesem Kontext nicht effizient.\n\nEbenso erlaubt diese Operation, vorläufige Dokumente durch ein Update von docStatus zu *löschen* (`preliminary` -> `entered-in-error` ). \n\nWenn Dokumenten-Server $update-metadata unterstützen, dann MÜSSEN Dokumenten-Server das *Löschen* von vorläufigen Dokumenten unterstützen, d.h. dann MÜSSEN Server bei einem Update auf den Status `entered-in-error` auch den Code in `DocumentReference.status` auf  `entered-in-error` setzen und dafür Sorge tragen, dass diese Dokumente bei Suchanfragen nicht mehr als Ergebnisse zurückgegeben werden (siehe [Search Related Safety Checks](https://hl7.org/fhir/R4/safety.html)), es sei denn der Client sucht *explizit* nach gelöschten Dokumenten (z.B. `/DocumentReference?status=entered-in-error`). \n\nSobald ein Dokument den Status `final` erreicht hat, MUSS ein Server  die Änderungen von Metadaten NICHT mehr zulassen (d.h. ein Server KANN in diesem Fall die Löschung finaler Dokumente erlauben, MUSS es aber nicht. Der Server KANN in diesem Fall auch eine Fehlermeldung ausgeben).\n\nFinale Dokumente SOLLEN nur noch mit MHD-konformen Methoden aktualisiert bzw. gelöscht werden, indem sie durch eine neue bzw. leere Version ersetzt werden. \nEin Client SOLL in diesem Fall eine erneute Dokumentenbereitstellung durchführen, mit Referenz auf das zu ersetzende Dokument in `DocumentReference.relatesTo.target` und dem Code `replaces` in `DocumentReference.relatesTo.code`.",
        "exampleBoolean" : true
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExampleEntryValidationDecimal"
        },
        "name" : "Validierung von Dezimalen",
        "description" : "### Beispiel-Questionnaire Validierung von Dezimalwerten  \n* Vorgabe des Eingabeformates mittels [entryFormat](https://hl7.org/fhir/R4/extension-entryformat.html)-Extension\n* Limitierung der Dezimalstellen mittels [maxDecimalPlaces](https://hl7.org/fhir/R4/extension-maxdecimalplaces.html)-Extension\n* Limitierung des Wertebereiches mittels [minValue](https://hl7.org/fhir/R4/extension-minvalue.html) \n   und [maxValue](https://hl7.org/fhir/R4/extension-maxvalue.html)-Extension\n* Vorgabe der anzugebenden Maßeinheit mittels [questionnaire-unit](https://hl7.org/fhir/R4/extension-questionnaire-unit.html)-Extension",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExampleInputPatternValidation"
        },
        "name" : "Validierung von Formulareingaben gegen RegExPattern",
        "description" : "### Beispiel-Questionnaire mit Validierung von Benutzereingaben mittels einer FHIRPath-Expression  \nDie Validierung erfolgt über die [targetConstraint](https://hl7.org/fhir/extensions/StructureDefinition-targetConstraint.html)-Extension",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExampleEntryValidationText"
        },
        "name" : "Validierung von Texten",
        "description" : "### Beispiel-Questionnaire Validierung von Textfeldern\n* Limitierung der Mindest- und Maximalvorkommen einer wiederholbaren Gruppe mittels [questionnaire-minOccurs](https://hl7.org/fhir/R4/extension-questionnaire-minoccurs.html)-Extension und [questionnaire-maxOccurs](https://hl7.org/fhir/R4/extension-questionnaire-maxoccurs.html)-Extension\n* Limitierung der Eingabelänge mittels [minLength](https://hl7.org/fhir/R4/extension-minlength.html)-Extension",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExamplePrePopDemo"
        },
        "name" : "Vorbelegung Demografischer Daten",
        "description" : "### Beispiel-Questionnaire mit automatischer Vorbelegung von demografischen Patientendaten \nDer Patientenkontext wird mittels der [SDC-LaunchContexts](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-launchContext.html)-Extension hergestellt.  \nDie Vorbelegung erfolgt über die [SDC-InitialExpression](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-initialExpression.html)-Extension",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Questionnaire"
          }
        ],
        "reference" : {
          "reference" : "Questionnaire/ExamplePrePopObservation"
        },
        "name" : "Vorbelegung von Observations",
        "description" : "### Beispiel-Questionnaire mit automatischer Vorbelegung von Observations  \nDie Suche nach passenden Observations geschieht innerhlab des Patienten-Kontextes anhand des in `item-code`hinterlegten Codes.\nDie Extension [SDC-ObservationLinkPeriod](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationLinkPeriod.html) legt fest, wie alt  Observations maximal sein dürfen, um für die Vorbelegung herangezogen zu werden (hier: max. 1 Jahr)  \nDie Extension [SDC-ObservationExtract](https://build.fhir.org/ig/HL7/sdc/StructureDefinition-sdc-questionnaire-observationExtract.html) legt fest, ob aus den Angaben des Questionnaires eine neue Observation extrahiert werden soll (hier: true)",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/ISiKFormularDefinition"
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/vs-mii-icu-bodysite-observation-blutdruck"
        },
        "name" : "VS MII ICU BodySite Observation Blutdruck",
        "description" : "Dieses ValueSet enthält Codes für bodySites von Blutdrücken (pulsatilen Drücken).",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/vs-mii-icu-bodysite-observation-monitoring-und-vitaldaten"
        },
        "name" : "VS MII ICU BodySite Observation Monitoring und Vitaldaten",
        "description" : "Dieses ValueSet enthält Codes für bodySites von Vitaldaten sowie Daten aus dem Patientenmonitoring.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/vs-mii-icu-code-monitoring-und-vitaldaten-iso11073"
        },
        "name" : "VS MII ICU Code Monitoring und Vitaldaten [ISO11073]",
        "description" : "Dieses ValueSet enthält Codes für Vitaldaten sowie Daten aus dem Patientenmonitoring.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/vs-mii-icu-code-monitoring-und-vitaldaten-loinc"
        },
        "name" : "VS MII ICU Code Monitoring und Vitaldaten [LOINC]",
        "description" : "Dieses ValueSet enthält Codes für Vitaldaten sowie Daten aus dem Patientenmonitoring.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/vs-mii-icu-code-monitoring-und-vitaldaten-snomed"
        },
        "name" : "VS MII ICU Code Monitoring und Vitaldaten [sct]",
        "description" : "Dieses ValueSet enthaelt Codes fuer Vitaldaten sowie Daten aus dem Patientenmonitoring.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "ValueSet"
          }
        ],
        "reference" : {
          "reference" : "ValueSet/vs-mii-icu-method-observation-blutdruck"
        },
        "name" : "VS MII ICU Method Observation Blutdruck",
        "description" : "Dieses ValueSet enthält Codes zur Angabe, ob ein Blutdruck invasiv oder nicht-invasiv gemessen ist.",
        "exampleBoolean" : false
      },
      {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/tools/StructureDefinition/resource-information",
            "valueString" : "Observation"
          }
        ],
        "reference" : {
          "reference" : "Observation/Zentralvenoeser-Blutdruck"
        },
        "name" : "Zentralvenoeser-Blutdruck",
        "exampleCanonical" : "http://gefyra.info/training/StructureDefinition/sd-mii-icu-zentralvenoeser-blutdruck"
      }
    ],
    "page" : {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "toc.html"
        }
      ],
      "nameUrl" : "toc.html",
      "title" : "Table of Contents",
      "generation" : "html",
      "page" : [
        {
          "extension" : [
            {
              "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
              "valueUrl" : "index.html"
            }
          ],
          "nameUrl" : "index.html",
          "title" : "Home",
          "generation" : "markdown"
        }
      ]
    },
    "parameter" : [
      {
        "code" : "path-resource",
        "value" : "input/capabilities"
      },
      {
        "code" : "path-resource",
        "value" : "input/examples"
      },
      {
        "code" : "path-resource",
        "value" : "input/extensions"
      },
      {
        "code" : "path-resource",
        "value" : "input/models"
      },
      {
        "code" : "path-resource",
        "value" : "input/operations"
      },
      {
        "code" : "path-resource",
        "value" : "input/profiles"
      },
      {
        "code" : "path-resource",
        "value" : "input/resources"
      },
      {
        "code" : "path-resource",
        "value" : "input/vocabulary"
      },
      {
        "code" : "path-resource",
        "value" : "input/maps"
      },
      {
        "code" : "path-resource",
        "value" : "input/testing"
      },
      {
        "code" : "path-resource",
        "value" : "input/history"
      },
      {
        "code" : "path-resource",
        "value" : "fsh-generated/resources"
      },
      {
        "code" : "path-pages",
        "value" : "template/config"
      },
      {
        "code" : "path-pages",
        "value" : "input/images"
      },
      {
        "code" : "path-tx-cache",
        "value" : "input-cache/txcache"
      }
    ]
  }
}

```
