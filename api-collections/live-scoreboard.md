# Live Scoreboard

**Get Scoreboard of Live Match API**

## Scoreboard of Live Match API

<mark style="color:blue;">`GET`</mark> `https://sports-api.xyz/api/cricket/v1/live_scores`

#### Query Parameters

| Name      | Type   | Description       |
| --------- | ------ | ----------------- |
| match\_id | String | \{{ match\_id \}} |

#### Headers

| Name                                         | Type   | Description             |
| -------------------------------------------- | ------ | ----------------------- |
| auth-key<mark style="color:red;">\*</mark>   | String | \{{ your-auth-key \}}   |
| secret-key<mark style="color:red;">\*</mark> | String | \{{ your-secret-key \}} |

{% tabs %}
{% tab title="200: OK " %}
```javascript
{
      "status": true,
      "msg": "Data found.",
      "data": [
            {
                  "match_id": 1507,
                  "series_id": 118,
                  "match_type": "T20",
                  "match_over": "20",
                  "match_status": "Live",
                  "tossWon": "Velocity opt to bowl",
                  "summery": "",
                  "second_circle": "",
                  "liveLine": "Over",
                  "powerPlay": "2",
                  "homeTeam": {
                        "id": 158,
                        "name": "Supernovas",
                        "code": "SPN",
                        "logo": "http://127.0.0.1:8000/storage/team/flag/SPN.jpg"
                  },
                  "awayTeam": {
                        "id": 159,
                        "name": "Velocity",
                        "code": "VEL",
                        "logo": "http://127.0.0.1:8000/storage/team/flag/VEL.jpg"
                  },
                  "currentInning": 2,
                  "target": 166,
                  "currRunRate": "6.14",
                  "reqRunRate": "9.46",
                  "runNeed": 123,
                  "ballRemaining": 78,
                  "battingTeam": "Velocity",
                  "balling_team": "Supernovas",
                  "next_batsman": "-",
                  "homeTeamScore": {
                        "score": 165,
                        "over": "20",
                        "wickets": 7
                  },
                  "awayTeamScore": {
                        "score": "43",
                        "over": "7.0",
                        "wickets": "3"
                  },
                  "lastWicket": [
                        {
                              "player": "K Navgire",
                              "run": 0,
                              "ball": "13"
                        }
                  ],
                  "batsman": [
                        {
                              "name": "N Chantham*",
                              "run": "3",
                              "ball": "7",
                              "fours": "0",
                              "sixes": "0",
                              "strike_rate": "42.86",
                              "out_by": ""
                        },
                        {
                              "name": "L Wolvaardt",
                              "run": "2",
                              "ball": "5",
                              "fours": "0",
                              "sixes": "0",
                              "strike_rate": "40.00",
                              "out_by": ""
                        }
                  ],
                  "partnership": [
                        {
                              "run": "5",
                              "ball": "8"
                        }
                  ],
                  "bowler": [
                        {
                              "name": "Pooja Vastrakar",
                              "over": "0.0",
                              "maiden": "",
                              "run": "3",
                              "wicket": "3",
                              "economy": "0"
                        }
                  ],
                  "last6ball": [
                        "1",
                        "1",
                        "1",
                        "0",
                        "1",
                        "0"
                  ],
                  "last4overs": [
                        {
                              "over": 5,
                              "runs": 0,
                              "balls": [
                                    "0",
                                    "0",
                                    "0",
                                    "0",
                                    "0",
                                    "0"
                              ]
                        },
                        {
                              "over": 6,
                              "runs": 1,
                              "balls": [
                                    "0",
                                    "1",
                                    "0",
                                    "w",
                                    "0",
                                    "0"
                              ]
                        },
                        {
                              "over": 7,
                              "runs": 4,
                              "balls": [
                                    "1",
                                    "1",
                                    "1",
                                    "0",
                                    "1",
                                    "0"
                              ]
                        }
                  ]
            }
      ]
}
```
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Request" %}
```
https://sports-api.xyz/api/cricket/v1/live_scores?match_id=1507
```
{% endtab %}
{% endtabs %}
