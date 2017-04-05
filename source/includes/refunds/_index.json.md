```json
{
  "data": [
    {
      "id": "1001",
      "type": "refunds",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/refunds/1001"
      },
      "relationships": {
        "registration": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/registrations/paul-awesomeconf-registration"
          }
        }
      }
    },
    {
      "id": "1002",
      "type": "refunds",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/refunds/1002"
      },
      "relationships": {
        "registration": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/registrations/doc-awesomeconf-registration"
          }
        }
      }
    }
  ]
}
```
