```json
{
  "data": {
    "id": "1000001",
    "type": "activities",
    "attributes": {
      "capacity": 100,
      "date": "2016-07-26",
      "description": null,
      "end-time": "20:00",
      "name": "Day 2 Dinner",
      "private": false,
      "question-ids": [],
      "release-ids": ["conf-ticket", "workshop-ticket"],
      "start-time": "18:00"
    },
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
  }
}
```
