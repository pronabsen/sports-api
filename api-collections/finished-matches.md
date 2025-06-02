# Finished Matches

**Finished Matches Fixtures API**

## Finished Matches API

<mark style="color:blue;">`GET`</mark> `https://sports-api.xyz/api/cricket/v1/fixtures_finished`

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
                  "match_id": 1379,
                  "series": "T20 Blast ",
                  "match_start": "28-05-2022 19:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Derbyshire won by 70 runs",
                  "winnerTeam": "Derbyshire",
                  "homeTeam_id": 62,
                  "homeTeam_name": "Leicestershire",
                  "homeTeam_short": "LEIC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LEIC.jpg",
                  "homeTeamScore": {
                        "score": "89",
                        "wickets": "10",
                        "over": "15.3"
                  },
                  "awayTeam_id": 51,
                  "awayTeam_name": "Derbyshire",
                  "awayTeam_short": "DERBY",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DERBY.jpg",
                  "awayTeamScore": {
                        "score": "159",
                        "wickets": "5",
                        "over": "20"
                  }
            }
      ]
}
```
{% endtab %}
{% endtabs %}
