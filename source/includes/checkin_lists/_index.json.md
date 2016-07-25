```json
{
  "data": [
    {
      "id": "awesomeconf-check-in-list",
      "type": "checkin-lists",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/checkin_lists/awesomeconf-check-in-list"
      },
      "relationships": {
        "activities": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/activities?filter[checkin_list]=awesomeconf-check-in-list"
          }
        },
        "checkins": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/checkin_lists/awesomeconf-check-in-list/checkins"
          }
        },
        "questions": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/questions?filter[checkin_list]=awesomeconf-check-in-list"
          }
        },
        "releases": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/releases?filter[checkin_list]=awesomeconf-check-in-list"
          }
        },
        "tickets": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/tickets?filter[checkin_list]=awesomeconf-check-in-list"
          }
        }
      }
    },
    {
      "id": "workshop-check-in-list",
      "type": "checkin-lists",
      "attributes": { ... },
      "links": {
        "self": "https://api.tito.io/v2/an-account/awesome-conf/checkin_lists/workshop-check-in-list"
      },
      "relationships": {
        "activities": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/activities?filter[checkin_list]=workshop-check-in-list"
          }
        },
        "checkins": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/checkin_lists/workshop-check-in-list/checkins"
          }
        },
        "questions": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/questions?filter[checkin_list]=workshop-check-in-list"
          }
        },
        "releases": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/releases?filter[checkin_list]=workshop-check-in-list"
          }
        },
        "tickets": {
          "links": {
            "related": "https://api.tito.io/v2/an-account/awesomeconf/tickets?filter[checkin_list]=workshop-check-in-list"
          }
        }
      }
    }
  ]
}
```
