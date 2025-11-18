# ISiKTerminKontaktMitGesundheitseinrichtung - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKTerminKontaktMitGesundheitseinrichtung**

## Resource Profile: ISiKTerminKontaktMitGesundheitseinrichtung 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKTerminKontaktMitGesundheitseinrichtung | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKTerminKontaktMitGesundheitseinrichtung |

 
Das Datenobjekt ISiKKontaktMitGesundheitseinrichtung dient der Verknüpfung des ISiK-Basis-Encounters (ISiKKontaktMitGesundheitseinrichtung) mit einem Termin (Appointment) und - darauf aufbauend - der Dokumentenkommunikation. 
Die Anforderung dieser Verknüpfung stammt aus dem Szenario der Dokument-Übertragung zwischen Patientenportal und krankenhaus-internem Primärsystem (KIS): Dokumente liegen bei Termin-Buchung erst im Patientenportal (im Appointment) vor und werden erst mit Anlage des Encounters in das KIS (etc.) übermittelt. Dazu muss das Appointment mit dem neu angelegten Encounter verknüpft werden, um die Dokumente aus dem Patientenportal darüber zuzuordnen. 
Hieraus folgt, dass das Datenobjekt nur relevant ist, falls das bestätigungsrelevante System das Datenobjekt ISiKKontaktMitGesundheitseinrichtung sowie ISiKTermin implementiert. Zu Beginn des Termins sollte das System die Verknüpfung zwischen Encounter und Appointment herstellen. Ausgenommen hiervon sind Termine, die nicht stattfinden, da für diese in der Regel keine Encounter angelegt werden. 

**Usages:**

* This Profile is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKTerminKontaktMitGesundheitseinrichtung)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKTerminKontaktMitGesundheitseinrichtung.csv), [Excel](StructureDefinition-ISiKTerminKontaktMitGesundheitseinrichtung.xlsx), [Schematron](StructureDefinition-ISiKTerminKontaktMitGesundheitseinrichtung.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKTerminKontaktMitGesundheitseinrichtung",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKTerminKontaktMitGesundheitseinrichtung",
  "version" : "0.1.0",
  "name" : "ISiKTerminKontaktMitGesundheitseinrichtung",
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
  "description" : "Das Datenobjekt ISiKKontaktMitGesundheitseinrichtung dient der Verknüpfung des ISiK-Basis-Encounters (ISiKKontaktMitGesundheitseinrichtung) mit einem Termin (Appointment) und - darauf aufbauend - der Dokumentenkommunikation.\n\nDie Anforderung dieser Verknüpfung stammt aus dem Szenario der Dokument-Übertragung zwischen Patientenportal und krankenhaus-internem Primärsystem (KIS): Dokumente liegen bei Termin-Buchung erst im Patientenportal (im Appointment) vor und werden erst mit Anlage des Encounters in das KIS (etc.) übermittelt. Dazu muss das Appointment mit dem neu angelegten Encounter verknüpft werden, um die Dokumente aus dem Patientenportal darüber zuzuordnen.\n\nHieraus folgt, dass das Datenobjekt nur relevant ist, falls das bestätigungsrelevante System das Datenobjekt ISiKKontaktMitGesundheitseinrichtung sowie ISiKTermin implementiert. Zu Beginn des Termins sollte das System die Verknüpfung zwischen Encounter und Appointment herstellen. Ausgenommen hiervon sind Termine, die nicht stattfinden, da für diese in der Regel keine Encounter angelegt werden.\n",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "workflow",
      "uri" : "http://hl7.org/fhir/workflow",
      "name" : "Workflow Pattern"
    },
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Encounter",
  "baseDefinition" : "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Encounter",
        "path" : "Encounter"
      },
      {
        "id" : "Encounter.appointment",
        "path" : "Encounter.appointment",
        "comment" : "**Hinweis:**  Zur Umsetzung der Funktionalität zum Dokumentenaustausch gemäß ISiK ist der entsprechende [Implementation Guide zum Modul Dokumentenaustausch](https://simplifier.net/guide/isik-dokumentenaustausch-v4?version=current) zu beachten.\n  \nBegründung Must Support: Die Referenz auf Appointment ermöglicht Portalen den Fallbezug aus dem Termin zu ermitteln und Dokumente an ein KIS zu senden. Das Element 'appointment' ist Must-Support, um sicherzustellen, dass ein Termin immer abrufbar ist, sofern er mit einem Fallkontaktverknüft ist."
      }
    ]
  }
}

```
