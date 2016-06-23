```json
{
  "data": [
    {
      "id": "paul-awesomeconf-registration",
      "type": "registrations",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/registrations/paul-awesomeconf-registration"
      },
      "relationships": {
        "tickets": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/tickets?filter[registration]=paul-awesomeconf-registration"
          }
        }
      },
      "meta": {
        "link": "https://tito.io/an-account/awesome-conf/registrations/paul-awesomeconf-ticket"
      }
    },
    {
      "id": "doc-awesomeconf-registration",
      "type": "registrations",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/registrations/doc-awesomeconf-registration"
      },
      "relationships": {
        "tickets": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesome-conf/tickets?filter[registration]=doc-awesomeconf-registration"
          }
        }
      },
      "meta": {
        "link": "https://tito.io/an-account/awesome-conf/registrations/doc-awesomeconf-ticket"
      }
    }
  ]
}
```
