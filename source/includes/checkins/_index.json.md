```json
{
  "data": [
    {
      "id": "0489139c-f279-449f-9146-8a22214d5909",
      "type": "checkins",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/checkin_lists/awesome-conf-check-in-list/checkins/0489139c-f279-449f-9146-8a22214d5909"
      },
      "relationships": {
        "checkin-list": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/checkin_lists/awesomeconf-check-in-list"
          }
        },
        "ticket": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/tickets/paul-awesomeconf-ticket"
          }
        }
      }
    },
    {
      "id": "12345678-f279-449f-9146-8a22214d5909",
      "type": "checkins",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/checkin_lists/awesome-conf-check-in-list/checkins/12345678-f279-449f-9146-8a22214d5909"
      },
      "relationships": {
        "checkin-list": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/checkin_lists/awesomeconf-check-in-list"
          }
        },
        "ticket": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/tickets/doc-awesomeconf-ticket"
          }
        }
      }
    }
  ]
}
```
