# Fixtures

&#x20;**Home Fixtures API**

{% swagger method="get" path="fixtures" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Home Fixtures API" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="auth-key" required="true" %}
\{{ your-auth-key }}
{% endswagger-parameter %}

{% swagger-parameter in="header" name="secret-key" required="true" %}
\{{ your-secret-key }}
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
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
                  "match_status": "Live",
                  "winner_team": "DERBY",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": 51,
                        "team": "Derbyshire",
                        "code": "DERBY"
                  },
                  "homeTeam_id": 62,
                  "homeTeam_name": "Leicestershire",
                  "homeTeam_short": "LEIC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LEIC.jpg",
                  "homeTeamScore": {
                        "score": 89,
                        "over": "15.3",
                        "wickets": 10
                  },
                  "awayTeam_id": 51,
                  "awayTeam_name": "Derbyshire",
                  "awayTeam_short": "DERBY",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DERBY.jpg",
                  "awayTeamScore": {
                        "score": 159,
                        "over": "20",
                        "wickets": 5
                  }
            }
      ]
}
```
{% endswagger-response %}
{% endswagger %}
