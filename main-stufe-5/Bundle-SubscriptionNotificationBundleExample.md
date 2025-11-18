# SubscriptionNotificationBundleExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SubscriptionNotificationBundleExample**

## Example Bundle: SubscriptionNotificationBundleExample

Profile: [ISiKSubscriptionNotification](StructureDefinition-ISiKSubscriptionNotification.md)

Bundle SubscriptionNotificationBundleExample of type history

-------

Entry 1 - fullUrl = urn:uuid:9bb6fcbd-8391-4e35-bd4c-620a2db47af0

Resource Parameters:

> 

Profile: [ISiK Subscription Status](StructureDefinition-ISiKSubscriptionStatus.md)

## Parameters


Request:

```
GET https://gematik.de/fhir/isik/SubscriptionTopic/patient-merge/$status

```

Response:

```
200

```

-------

Entry 2 - fullUrl = http://example.org/fhir/Patient/DorisQuelle

Resource Patient:

> 

Profile: [ISiKPatient](StructureDefinition-ISiKPatient.md)

Doris Duplikat (official) Female, DoB: 1964-08-12 ( Krankenversichertennummer)
-------

Request:

```
PUT Patient

```

Response:

```
201

```



## Resource Content

```json
{
  "resourceType" : "Bundle",
  "id" : "SubscriptionNotificationBundleExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKSubscriptionNotification"
    ]
  },
  "type" : "history",
  "entry" : [
    {
      "fullUrl" : "urn:uuid:9bb6fcbd-8391-4e35-bd4c-620a2db47af0",
      "resource" : {
        "resourceType" : "Parameters",
        "id" : "ISiKSubscriptionStatusExample",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKSubscriptionStatus"
          ]
        },
        "parameter" : [
          {
            "name" : "subscription",
            "valueReference" : {
              "reference" : "Subscription/1"
            }
          },
          {
            "name" : "topic",
            "valueCanonical" : "https://gematik.de/fhir/isik/SubscriptionTopic/patient-merge"
          },
          {
            "name" : "status",
            "valueCode" : "active"
          },
          {
            "name" : "type",
            "valueCode" : "event-notification"
          },
          {
            "name" : "events-since-subscription-start",
            "valueString" : "1"
          },
          {
            "name" : "notification-event",
            "part" : [
              {
                "name" : "event-number",
                "valueString" : "1"
              },
              {
                "name" : "timestamp",
                "valueInstant" : "2024-02-22T18:30:05+01:00"
              },
              {
                "name" : "focus",
                "valueReference" : {
                  "reference" : "Patient/DorisQuelle"
                }
              }
            ]
          }
        ]
      },
      "request" : {
        "method" : "GET",
        "url" : "https://gematik.de/fhir/isik/SubscriptionTopic/patient-merge/$status"
      },
      "response" : {
        "status" : "200"
      }
    },
    {
      "fullUrl" : "http://example.org/fhir/Patient/DorisQuelle",
      "resource" : {
        "resourceType" : "Patient",
        "id" : "DorisQuelle",
        "meta" : {
          "profile" : [
            "http://gefyra.info/training/StructureDefinition/ISiKPatient"
          ]
        },
        "text" : {
          "status" : "generated",
          "div" : "<div xmlns=\"http://www.w3.org/1999/xhtml\"><a name=\"Patient_DorisQuelle\"> </a><p class=\"res-header-id\"><b>Generated Narrative: Patient DorisQuelle</b></p><a name=\"DorisQuelle\"> </a><a name=\"hcDorisQuelle\"> </a><div style=\"display: inline-block; background-color: #d9e0e7; padding: 6px; margin: 4px; border: 1px solid #8da1b4; border-radius: 5px; line-height: 60%\"><p style=\"margin-bottom: 0px\"/><p style=\"margin-bottom: 0px\">Profile: <a href=\"StructureDefinition-ISiKPatient.html\">ISiKPatient</a></p></div><p style=\"border: 1px #661aff solid; background-color: #e6e6ff; padding: 10px;\">Doris Duplikat (official) Female, DoB: 1964-08-12 ( Krankenversichertennummer)</p><hr/><table class=\"grid\"><tr><td style=\"background-color: #f3f5da\" title=\"Record is active\">Active:</td><td colspan=\"3\">false</td></tr><tr><td style=\"background-color: #f3f5da\" title=\"Other Id (see the one above)\">Other Id:</td><td colspan=\"3\">Medical record number/654321</td></tr></table></div>"
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
            "value" : "A123456789"
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
            "system" : "https://fhir.krankenhaus.example/sid/PID",
            "value" : "654321"
          }
        ],
        "active" : false,
        "name" : [
          {
            "use" : "official",
            "family" : "Duplikat",
            "given" : ["Doris"]
          }
        ],
        "gender" : "female",
        "birthDate" : "1964-08-12"
      },
      "request" : {
        "method" : "PUT",
        "url" : "Patient"
      },
      "response" : {
        "status" : "201"
      }
    }
  ]
}

```
