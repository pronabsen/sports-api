# Live Matches

&#x20;**Live Matches Fixtures API**

{% swagger method="get" path="fixtures_live" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Live Matches API" %}
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
                  "match_id": 1507,
                  "series": "Womens T20 Challenge ",
                  "match_start": "28-05-2022 19:30:00",
                  "match_round": "Final",
                  "match_type": "T20",
                  "match_status": "Live",
                  "winner_team": "SPN",
                  "super_over": "",
                  "summery": "Live",
                  "tossWon": {
                        "id": 158,
                        "team": "Supernovas",
                        "code": "SPN"
                  },
                  "homeTeam_id": 158,
                  "homeTeam_name": "Supernovas",
                  "homeTeam_short": "SPN",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SPN.jpg",
                  "homeTeamScore": {
                        "score": 165,
                        "over": "20",
                        "wickets": 7
                  },
                  "awayTeam_id": 159,
                  "awayTeam_name": "Velocity",
                  "awayTeam_short": "VEL",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/VEL.jpg",
                  "awayTeamScore": {
                        "score": 40,
                        "over": "6.2",
                        "wickets": 3
                  }
            }
      ]
}
```
{% endswagger-response %}
{% endswagger %}
