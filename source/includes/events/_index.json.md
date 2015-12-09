```json
{
  "data": [
    {
      "id":"summer-conf",
      "type": "events",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/summer-conf"
      },
      "relationships": {
        "releases": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/summer-conf/releases"
          }
        }
      }
    },
    {
      "id":"winter-conf",
      "type": "events",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/winter-conf"
      },
      "relationships": {
        "releases": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/winter-conf/releases"
          }
        }
      }
    }
  ]
}
```
