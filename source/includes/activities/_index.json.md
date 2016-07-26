```json
{
  "data": [
    {
      "id": "1000001",
      "type": "activities",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/activities/1000001"
      },
      "relationships": {
        "questions": {
          "links": {
            "related": "http://api.tito.io/v2/an-account/awesome-conf/questions?filter[activity]=1000001"
          }
        }
      }
    },
    {
      "id": "1000002",
      "type": "activities",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/activities/1000002"
      },
      "relationships": {
        "questions": {
          "links": {
            "related": "http://api.tito.io/v2/an-account/awesome-conf/questions?filter[activity]=1000002"
          }
        }
      }
    }
  ]
}
```
