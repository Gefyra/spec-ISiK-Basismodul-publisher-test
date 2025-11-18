# ISiKUnterbrechungReha - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKUnterbrechungReha**

## CodeSystem: ISiKUnterbrechungReha 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/CodeSystem/ISiKUnterbrechungRehaCS | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKUnterbrechungReha |

 
ISiK Unterbrechung Reha. Dokumentiert die relevanten Gründe einer Unterbrechung einer Rehabilitationsmaßnahme im Einzelfall. Vgl. Schlüsseltabelle 2.111 Erläuterung zur Unterbrechung. 

 This Code system is referenced in the content logical definition of the following value sets: 

* [ISiKUnterbrechungRehaVS](ValueSet-ISiKUnterbrechungReha.md)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "ISiKUnterbrechungRehaCS",
  "url" : "http://gefyra.info/training/CodeSystem/ISiKUnterbrechungRehaCS",
  "version" : "0.1.0",
  "name" : "ISiKUnterbrechungReha",
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
  "description" : "ISiK Unterbrechung Reha. Dokumentiert die relevanten Gründe einer Unterbrechung einer Rehabilitationsmaßnahme im Einzelfall. Vgl. Schlüsseltabelle 2.111 Erläuterung zur Unterbrechung.",
  "caseSensitive" : false,
  "content" : "complete",
  "count" : 7,
  "concept" : [
    {
      "code" : "01",
      "display" : "Interkurrente Erkrankung"
    },
    {
      "code" : "02",
      "display" : "Stationäre Krankenhausbehandlung (nicht interkurrente Erkrankung)"
    },
    {
      "code" : "03",
      "display" : "Beurlaubung"
    },
    {
      "code" : "04",
      "display" : "Stationäre Krankenhausbehandlung"
    },
    {
      "code" : "05",
      "display" : "Erkrankung (ohne Krankenhausbehandlung)"
    },
    {
      "code" : "06",
      "display" : "Belastungserprobung im häuslichen Umfeld"
    },
    {
      "code" : "09",
      "display" : "Sonstiger Grund, der zur Unterbrechung der Pflegekosten führt"
    }
  ]
}

```
