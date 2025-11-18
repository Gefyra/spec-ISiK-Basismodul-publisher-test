# Szenario2 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Szenario2**

## Example Bundle: Szenario2

Bundle Szenario2 of type collection

-------

Entry 1 - fullUrl = https://example.com/fhir/Patient/SZ2Patient

Resource Patient:

> 

Profile: [ISiKPatient](StructureDefinition-ISiKPatient.md)

Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)
-------

-------

Entry 2 - fullUrl = https://example.com/fhir/Condition/SZ2Primaerdiagnose

Resource Condition:

> 

Profile: [ISiKDiagnose](StructureDefinition-ISiKDiagnose.md)

**code**:Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet**subject**:[Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)](Patient-SZ2Patient.md)**encounter**:[Encounter: identifier = Visit number; status = finished; class = inpatient encounter (ActCode#IMP); type = Abteilungskontakt,Normalstationär; period = 2024-10-07 --> 2024-10-10](Encounter-SZ2Encounter.md)**recordedDate**: 2024-11-05

-------

Entry 3 - fullUrl = https://example.com/fhir/Condition/SZ2Sekundaerdiagnose

Resource Condition:

> 

Profile: [ISiKDiagnose](StructureDefinition-ISiKDiagnose.md)

**Condition Related**:[Condition Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet](Condition-SZ2Primaerdiagnose.md)**code**:Retinopathia diabetica**subject**:[Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)](Patient-SZ2Patient.md)**encounter**:[Encounter: identifier = Visit number; status = finished; class = inpatient encounter (ActCode#IMP); type = Abteilungskontakt,Normalstationär; period = 2024-10-07 --> 2024-10-10](Encounter-SZ2Encounter.md)**recordedDate**: 2024-11-05

-------

Entry 4 - fullUrl = https://example.com/fhir/Encounter/SZ2Encounter

Resource Encounter:

> 

Profile: [ISiKKontaktGesundheitseinrichtung](StructureDefinition-ISiKKontaktGesundheitseinrichtung.md)

**identifier**: Visit number/222222222-2**status**: completed**class**:inpatient encounter**type**:Abteilungskontakt,Normalstationär**subject**:[Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)](Patient-SZ2Patient.md)**account**:[Account: extension = ; identifier = Account number; status = active; type = inpatient encounter](Account-SZ2DRGFall.md)

-------

Entry 5 - fullUrl = https://example.com/fhir/Account/SZ2DRGFall

Resource Account:

> 

Profile: [ISiKAbrechnungsfall](StructureDefinition-ISiKAbrechnungsfall.md)

> **Fallbezogene Abrechnungsrelevanz von Diagnosen und Prozeduren**
* Use: [KontaktDiagnoseProzedur: hospital-main-diagnosis](https://simplifier.net/resolve?scope=de.basisprofil.r4@1.5.4&canonical=http://fhir.de/CodeSystem/KontaktDiagnoseProzedur#KontaktDiagnoseProzedur-hospital-main-diagnosis) (Krankenhaus Hauptdiagnose)
* Referenz: [Condition Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet](Condition-SZ2Primaerdiagnose.md)

**identifier**: Account number/22222222222**status**: Active**type**:inpatient encounter**subject**:[Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)](Patient-SZ2Patient.md)

### Coverages

| | | |
| :--- | :--- | :--- |
| - | **Extension** | **Coverage** |
| * |  | [Coverage: status = active; type = gesetzliche Krankenversicherung](Coverage-SZ2VersicherungGesetzlich.md) |


-------

Entry 6 - fullUrl = https://example.com/fhir/Coverage/SZ2VersicherungGesetzlich

Resource Coverage:

> 

Profile: [ISiKVersicherungsverhaeltnisGesetzlich](StructureDefinition-ISiKVersicherungsverhaeltnisGesetzlich.md)

**status**: Active**type**:gesetzliche Krankenversicherung**subscriber**:[Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)](Patient-SZ2Patient.md)**beneficiary**:[Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)](Patient-SZ2Patient.md)



## Resource Content

```json
{
  "resourceType" : "Bundle",
  "id" : "Szenario2",
  "type" : "collection",
  "entry" : [
    {
      "fullUrl" : "https://example.com/fhir/Patient/SZ2Patient",
      "resource" : {
        "resourceType" : "Patient",
        "id" : "SZ2Patient",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKPatient"
          ]
        },
        "text" : {
          "status" : "generated",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Patient_SZ2Patient\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Patient SZ2Patient</b></p><a name=\"SZ2Patient\"> </a><a name=\"hcSZ2Patient\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKPatient.html\">ISiKPatient</a></p></div><p style=\"border: 1px #661aff solid; background-color: #e6e6ff; padding: 10px;\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</p><hr/><table class=\"grid\"><tr><td style=\"background-color: #f3f5da\" title=\"Record is active\">Active:</td><td colspan=\"3\">true</td></tr><tr><td style=\"background-color: #f3f5da\" title=\"Other Id (see the one above)\">Other Id:</td><td colspan=\"3\">Medical record number/222222</td></tr></table></div>"
        },
        "identifier" : [
          {
            "type" : {
              "coding" : [
                {
                  "system" : "http://fhir.de/CodeSystem/identifier-type-de-basis",
                  "code" : "KVZ10"
                }
              ]
            },
            "system" : "http://fhir.de/sid/gkv/kvid-10",
            "value" : "A222222222"
          },
          {
            "type" : {
              "coding" : [
                {
                  "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
                  "code" : "MR"
                }
              ]
            },
            "system" : "http://beispiel-krankenhaus.de/sid/Patienten",
            "value" : "222222"
          }
        ],
        "active" : true,
        "name" : [
          {
            "use" : "official",
            "family" : "Musterfrau",
            "given" : ["Friedlinde"]
          }
        ],
        "gender" : "female",
        "birthDate" : "1924-01-01"
      }
    },
    {
      "fullUrl" : "https://example.com/fhir/Condition/SZ2Primaerdiagnose",
      "resource" : {
        "resourceType" : "Condition",
        "id" : "SZ2Primaerdiagnose",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
          ]
        },
        "text" : {
          "status" : "generated",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Condition_SZ2Primaerdiagnose\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Condition SZ2Primaerdiagnose</b></p><a name=\"SZ2Primaerdiagnose\"> </a><a name=\"hcSZ2Primaerdiagnose\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKDiagnose.html\">ISiKDiagnose</a></p></div><p><b>code</b>: <span title=\"Codes:{http://fhir.de/CodeSystem/bfarm/icd-10-gm E10.30}\">Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet</span></p><p><b>subject</b>: <a href=\"Patient-SZ2Patient.html\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</a></p><p><b>encounter</b>: <a href=\"Encounter-SZ2Encounter.html\">Encounter: identifier = Visit number; status = finished; class = inpatient encounter (ActCode#IMP); type = Abteilungskontakt,Normalstationär; period = 2024-10-07 --&gt; 2024-10-10</a></p><p><b>recordedDate</b>: 2024-11-05</p></div>"
        },
        "code" : {
          "coding" : [
            {
              "extension" : [
                {
                  "url" : "http://fhir.de/StructureDefinition/icd-10-gm-mehrfachcodierungs-kennzeichen",
                  "valueCoding" : {
                    "system" : "http://fhir.de/CodeSystem/icd-10-gm-mehrfachcodierungs-kennzeichen",
                    "code" : "†"
                  }
                }
              ],
              "system" : "http://fhir.de/CodeSystem/bfarm/icd-10-gm",
              "version" : "2024",
              "code" : "E10.30",
              "display" : "Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet"
            }
          ]
        },
        "subject" : {
          "reference" : "Patient/SZ2Patient"
        },
        "encounter" : {
          "reference" : "Encounter/SZ2Encounter"
        },
        "recordedDate" : "2024-11-05"
      }
    },
    {
      "fullUrl" : "https://example.com/fhir/Condition/SZ2Sekundaerdiagnose",
      "resource" : {
        "resourceType" : "Condition",
        "id" : "SZ2Sekundaerdiagnose",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
          ]
        },
        "text" : {
          "status" : "extensions",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Condition_SZ2Sekundaerdiagnose\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Condition SZ2Sekundaerdiagnose</b></p><a name=\"SZ2Sekundaerdiagnose\"> </a><a name=\"hcSZ2Sekundaerdiagnose\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKDiagnose.html\">ISiKDiagnose</a></p></div><p><b>Condition Related</b>: <a href=\"Condition-SZ2Primaerdiagnose.html\">Condition Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet</a></p><p><b>code</b>: <span title=\"Codes:{http://fhir.de/CodeSystem/bfarm/icd-10-gm H36.0}\">Retinopathia diabetica</span></p><p><b>subject</b>: <a href=\"Patient-SZ2Patient.html\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</a></p><p><b>encounter</b>: <a href=\"Encounter-SZ2Encounter.html\">Encounter: identifier = Visit number; status = finished; class = inpatient encounter (ActCode#IMP); type = Abteilungskontakt,Normalstationär; period = 2024-10-07 --&gt; 2024-10-10</a></p><p><b>recordedDate</b>: 2024-11-05</p></div>"
        },
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/StructureDefinition/condition-related",
            "valueReference" : {
              "reference" : "Condition/SZ2Primaerdiagnose"
            }
          }
        ],
        "code" : {
          "coding" : [
            {
              "extension" : [
                {
                  "url" : "http://fhir.de/StructureDefinition/icd-10-gm-mehrfachcodierungs-kennzeichen",
                  "valueCoding" : {
                    "system" : "http://fhir.de/CodeSystem/icd-10-gm-mehrfachcodierungs-kennzeichen",
                    "code" : "*"
                  }
                }
              ],
              "system" : "http://fhir.de/CodeSystem/bfarm/icd-10-gm",
              "version" : "2024",
              "code" : "H36.0",
              "display" : "Retinopathia diabetica"
            }
          ]
        },
        "subject" : {
          "reference" : "Patient/SZ2Patient"
        },
        "encounter" : {
          "reference" : "Encounter/SZ2Encounter"
        },
        "recordedDate" : "2024-11-05"
      }
    },
    {
      "fullUrl" : "https://example.com/fhir/Encounter/SZ2Encounter",
      "resource" : {
        "resourceType" : "Encounter",
        "id" : "SZ2Encounter",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
          ]
        },
        "text" : {
          "status" : "generated",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Encounter_SZ2Encounter\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Encounter SZ2Encounter</b></p><a name=\"SZ2Encounter\"> </a><a name=\"hcSZ2Encounter\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKKontaktGesundheitseinrichtung.html\">ISiKKontaktGesundheitseinrichtung</a></p></div><p><b>identifier</b>: Visit number/222222222-2</p><p><b>status</b>: Finished</p><p><b>class</b>: <a href=\"http://terminology.hl7.org/7.0.0/CodeSystem-v3-ActCode.html#v3-ActCode-IMP\">ActCode: IMP</a> (inpatient encounter)</p><p><b>type</b>: <span title=\"Codes:{http://fhir.de/CodeSystem/Kontaktebene abteilungskontakt}\">Abteilungskontakt</span>, <span title=\"Codes:{http://fhir.de/CodeSystem/kontaktart-de normalstationaer}\">Normalstationär</span></p><p><b>subject</b>: <a href=\"Patient-SZ2Patient.html\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</a></p><p><b>period</b>: 2024-10-07 --&gt; 2024-10-10</p><p><b>account</b>: <a href=\"Account-SZ2DRGFall.html\">Account: extension = ; identifier = Account number; status = active; type = inpatient encounter</a></p></div>"
        },
        "identifier" : [
          {
            "type" : {
              "coding" : [
                {
                  "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
                  "code" : "VN"
                }
              ]
            },
            "system" : "http://beispiel-krankenhaus.de/sid/besuchsnummer",
            "value" : "222222222-2"
          }
        ],
        "status" : "finished",
        "class" : {
          "system" : "http://terminology.hl7.org/CodeSystem/v3-ActCode",
          "code" : "IMP"
        },
        "type" : [
          {
            "coding" : [
              {
                "system" : "http://fhir.de/CodeSystem/Kontaktebene",
                "code" : "abteilungskontakt"
              }
            ]
          },
          {
            "coding" : [
              {
                "system" : "http://fhir.de/CodeSystem/kontaktart-de",
                "code" : "normalstationaer",
                "display" : "Normalstationär"
              }
            ]
          }
        ],
        "subject" : {
          "reference" : "Patient/SZ2Patient"
        },
        "period" : {
          "start" : "2024-10-07",
          "end" : "2024-10-10"
        },
        "account" : [
          {
            "reference" : "Account/SZ2DRGFall",
            "identifier" : {
              "system" : "http://beispiel-krankenhaus.de/sid/fallnummern",
              "value" : "22222222222"
            }
          }
        ]
      }
    },
    {
      "fullUrl" : "https://example.com/fhir/Account/SZ2DRGFall",
      "resource" : {
        "resourceType" : "Account",
        "id" : "SZ2DRGFall",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKAbrechnungsfall"
          ]
        },
        "text" : {
          "status" : "extensions",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Account_SZ2DRGFall\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Account SZ2DRGFall</b></p><a name=\"SZ2DRGFall\"> </a><a name=\"hcSZ2DRGFall\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKAbrechnungsfall.html\">ISiKAbrechnungsfall</a></p></div><blockquote><p><b>Fallbezogene Abrechnungsrelevanz von Diagnosen und Prozeduren</b></p><ul><li>Use: <a href=\"https://simplifier.net/resolve?scope=de.basisprofil.r4@1.5.4&amp;canonical=http://fhir.de/CodeSystem/KontaktDiagnoseProzedur#KontaktDiagnoseProzedur-hospital-main-diagnosis\">KontaktDiagnoseProzedur: hospital-main-diagnosis</a> (Krankenhaus Hauptdiagnose)</li><li>Referenz: <a href=\"Condition-SZ2Primaerdiagnose.html\">Condition Diabetes mellitus, Typ 1: Mit Augenkomplikationen: Nicht als entgleist bezeichnet</a></li></ul></blockquote><p><b>identifier</b>: Account number/22222222222</p><p><b>status</b>: Active</p><p><b>type</b>: <span title=\"Codes:{http://terminology.hl7.org/CodeSystem/v3-ActCode IMP}\">inpatient encounter</span></p><p><b>subject</b>: <a href=\"Patient-SZ2Patient.html\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</a></p><h3>Coverages</h3><table class=\"grid\"><tr><td style=\"display: none\">-</td><td><b>Extension</b></td><td><b>Coverage</b></td></tr><tr><td style=\"display: none\">*</td><td/><td><a href=\"Coverage-SZ2VersicherungGesetzlich.html\">Coverage: status = active; type = gesetzliche Krankenversicherung</a></td></tr></table></div>"
        },
        "extension" : [
          {
            "extension" : [
              {
                "url" : "Use",
                "valueCoding" : {
                  "system" : "http://fhir.de/CodeSystem/KontaktDiagnoseProzedur",
                  "code" : "hospital-main-diagnosis"
                }
              },
              {
                "url" : "Referenz",
                "valueReference" : {
                  "reference" : "Condition/SZ2Primaerdiagnose"
                }
              }
            ],
            "url" : "http://fhir.de/StructureDefinition/ExtensionAbrechnungsDiagnoseProzedur"
          }
        ],
        "identifier" : [
          {
            "type" : {
              "coding" : [
                {
                  "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
                  "code" : "AN"
                }
              ]
            },
            "system" : "http://beispiel-krankenhaus.de/sid/fallnummern",
            "value" : "22222222222"
          }
        ],
        "status" : "active",
        "type" : {
          "coding" : [
            {
              "system" : "http://terminology.hl7.org/CodeSystem/v3-ActCode",
              "code" : "IMP"
            }
          ]
        },
        "subject" : [
          {
            "reference" : "Patient/SZ2Patient"
          }
        ],
        "coverage" : [
          {
            "extension" : [
              {
                "url" : "http://fhir.de/StructureDefinition/ExtensionAbrechnungsart",
                "valueCoding" : {
                  "system" : "http://fhir.de/CodeSystem/dkgev/Abrechnungsart",
                  "code" : "DRG",
                  "display" : "Diagnosebezogene Fallgruppen"
                }
              }
            ],
            "coverage" : {
              "reference" : "Coverage/SZ2VersicherungGesetzlich"
            }
          }
        ]
      }
    },
    {
      "fullUrl" : "https://example.com/fhir/Coverage/SZ2VersicherungGesetzlich",
      "resource" : {
        "resourceType" : "Coverage",
        "id" : "SZ2VersicherungGesetzlich",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisGesetzlich"
          ]
        },
        "text" : {
          "status" : "generated",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Coverage_SZ2VersicherungGesetzlich\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Coverage SZ2VersicherungGesetzlich</b></p><a name=\"SZ2VersicherungGesetzlich\"> </a><a name=\"hcSZ2VersicherungGesetzlich\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKVersicherungsverhaeltnisGesetzlich.html\">ISiKVersicherungsverhaeltnisGesetzlich</a></p></div><p><b>status</b>: Active</p><p><b>type</b>: <span title=\"Codes:{http://fhir.de/CodeSystem/versicherungsart-de-basis GKV}\">gesetzliche Krankenversicherung</span></p><p><b>subscriber</b>: <a href=\"Patient-SZ2Patient.html\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</a></p><p><b>beneficiary</b>: <a href=\"Patient-SZ2Patient.html\">Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)</a></p><p><b>payor</b>: BKK für Testpatienten (Identifier: Organization identifier/260326855)</p></div>"
        },
        "status" : "active",
        "type" : {
          "coding" : [
            {
              "system" : "http://fhir.de/CodeSystem/versicherungsart-de-basis",
              "code" : "GKV"
            }
          ]
        },
        "subscriber" : {
          "reference" : "Patient/SZ2Patient",
          "identifier" : {
            "type" : {
              "coding" : [
                {
                  "system" : "http://fhir.de/CodeSystem/identifier-type-de-basis",
                  "code" : "KVZ10"
                }
              ]
            },
            "system" : "http://fhir.de/sid/gkv/kvid-10",
            "value" : "A222222222"
          }
        },
        "beneficiary" : {
          "reference" : "Patient/SZ2Patient"
        },
        "payor" : [
          {
            "identifier" : {
              "type" : {
                "coding" : [
                  {
                    "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
                    "code" : "XX"
                  }
                ]
              },
              "system" : "http://fhir.de/sid/arge-ik/iknr",
              "value" : "260326855"
            },
            "display" : "BKK für Testpatienten"
          }
        ]
      }
    }
  ]
}

```
