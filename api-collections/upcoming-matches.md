# Upcoming Matches

**Finished Matches Fixtures API**

## Upcoming Matches API

<mark style="color:blue;">`GET`</mark> `https://sports-api.xyz/api/cricket/v1/fixtures_upcoming`

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
                  "match_id": 1380,
                  "series_id": 115,
                  "series_name": "T20 Blast ",
                  "match_start": "29-05-2022 19:00:00",
                  "match_round": "South Group",
                  "match_type": "T20",
                  "venue": "The Cooper Associates County Ground, Taunton",
                  "match_status": "Upcoming",
                  "homeTeam_id": 56,
                  "homeTeam_name": "Somerset",
                  "homeTeam_short": "SOM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SOM.jpg",
                  "awayTeam_id": 57,
                  "awayTeam_name": "Essex",
                  "awayTeam_short": "ESS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ESS.jpg"
            }
      ]
}
```
{% endtab %}
{% endtabs %}
