```json
{
  "data": [
    {
      "id": "paul-awesomeconf-ticket",
      "type": "tickets",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/tickets/paul-awesomeconf-ticket"
      },
      "relationships": {
        "registration": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/registrations/paul-awesomeconf-registration"
          }
        },
        "release": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/releases/awesomeconf-ticket"
          }
        }
      }
    },
    {
      "id": "doc-awesomeconf-ticket",
      "type": "tickets",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/tickets/doc-awesomeconf-ticket"
      },
      "relationships": {
        "registration": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/registrations/doc-awesomeconf-registration"
          }
        },
        "release": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/releases/awesomeconf-ticket"
          }
        }
      }
    }
  ]
}
```
