```json
{
  "data": {
    "id": "awesomeconf-check-in-list",
    "type": "checkin-lists",
    "attributes": {
      "activity-ids": [],
      "expires-at": null,
      "question-ids": [],
      "release-ids": [],
      "show-company-name": true,
      "show-email": true,
      "show-phone-number": true,
      "title": "Awesomeconf Check-in List"
    },
    "links": {
      "self": "https://api.tito.io/v2/an-account/awesomeconf/checkin_lists/awesomeconf-check-in-list"
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
  }
}
```
