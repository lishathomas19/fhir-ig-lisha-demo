# Demo Patient Example - Lisha Demo Implementation Guide v0.0.1

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Demo Patient Example**

## Example Patient: Demo Patient Example

Profile: [Demo Patient Profile](StructureDefinition-demo-patient.md)

Erika Mustermann Female, DoB: 1980-05-12 ( http://example.org/fhir/ids/patient#12345)

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "DemoPatientExample",
  "meta" : {
    "profile" : [
      "https://lishathomas19.github.io/fhir-ig-lisha-demo/StructureDefinition/demo-patient"
    ]
  },
  "identifier" : [
    {
      "system" : "http://example.org/fhir/ids/patient",
      "value" : "12345"
    }
  ],
  "name" : [
    {
      "family" : "Mustermann",
      "given" : ["Erika"]
    }
  ],
  "gender" : "female",
  "birthDate" : "1980-05-12"
}

```
