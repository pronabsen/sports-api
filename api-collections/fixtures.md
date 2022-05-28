# Fixtures

&#x20;**Home Fixtures API**

{% swagger method="get" path="fixtures" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Home Fixtures API" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="auth-key" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="header" name="secret-key" required="true" %}

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
            },
            {
                  "match_id": 1507,
                  "series": "Womens T20 Challenge ",
                  "match_start": "28-05-2022 19:30:00",
                  "match_round": "Final",
                  "match_type": "T20",
                  "match_status": "Live",
                  "winner_team": "VEL",
                  "super_over": "",
                  "summery": "",
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
                        "score": 29,
                        "over": "2",
                        "wickets": 0
                  }
            },
            {
                  "match_id": 1351,
                  "series": "Sri Lanka Women tour of Pakistan",
                  "match_start": "28-05-2022 14:30:00",
                  "match_round": "3rd T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "winner_team": "PAK - W",
                  "super_over": "",
                  "summery": "Pakistan Women won by 4 wickets",
                  "tossWon": {
                        "id": 156,
                        "team": "Sri Lanka Women",
                        "code": "SL-W"
                  },
                  "homeTeam_id": 94,
                  "homeTeam_name": "Pakistan Women",
                  "homeTeam_short": "PAK - W",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PAK - W.jpg",
                  "homeTeamScore": {
                        "score": 108,
                        "over": "20",
                        "wickets": 6
                  },
                  "awayTeam_id": 156,
                  "awayTeam_name": "Sri Lanka Women",
                  "awayTeam_short": "SL-W",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SL-W.jpg",
                  "awayTeamScore": {
                        "score": 107,
                        "over": "20",
                        "wickets": 8
                  }
            },
            {
                  "match_id": 1380,
                  "series": "T20 Blast ",
                  "match_start": "29-05-2022 19:00:00",
                  "match_round": "South Group",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 56,
                  "homeTeam_name": "Somerset",
                  "homeTeam_short": "SOM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SOM.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 57,
                  "awayTeam_name": "Essex",
                  "awayTeam_short": "ESS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ESS.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            },
            {
                  "match_id": 1381,
                  "series": "T20 Blast ",
                  "match_start": "29-05-2022 19:00:00",
                  "match_round": "South Group",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 67,
                  "homeTeam_name": "Sussex",
                  "homeTeam_short": "SUS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SUS.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 54,
                  "awayTeam_name": "Kent",
                  "awayTeam_short": "KENT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KENT.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            },
            {
                  "match_id": 1382,
                  "series": "T20 Blast ",
                  "match_start": "29-05-2022 19:00:00",
                  "match_round": "South Group",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 60,
                  "homeTeam_name": "Middlesex",
                  "homeTeam_short": "MDX",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MDX.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 58,
                  "awayTeam_name": "Glamorgan",
                  "awayTeam_short": "GLAM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GLAM.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            },
            {
                  "match_id": 1383,
                  "series": "T20 Blast ",
                  "match_start": "29-05-2022 19:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 50,
                  "homeTeam_name": "Lancashire",
                  "homeTeam_short": "LANCS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LANCS.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 52,
                  "awayTeam_name": "Worcestershire",
                  "awayTeam_short": "WORCS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/WORCS.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            },
            {
                  "match_id": 1384,
                  "series": "T20 Blast ",
                  "match_start": "29-05-2022 19:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 63,
                  "homeTeam_name": "Warwickshire",
                  "homeTeam_short": "WARKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/WARKS.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 66,
                  "awayTeam_name": "Durham",
                  "awayTeam_short": "DUR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DUR.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            },
            {
                  "match_id": 1367,
                  "series": "Indian Premier League ",
                  "match_start": "29-05-2022 19:30:00",
                  "match_round": "Final",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            },
            {
                  "match_id": 1385,
                  "series": "T20 Blast ",
                  "match_start": "29-05-2022 19:30:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Upcoming",
                  "winner_team": "",
                  "super_over": "",
                  "summery": "",
                  "tossWon": {
                        "id": null,
                        "team": null,
                        "code": null
                  },
                  "homeTeam_id": 64,
                  "homeTeam_name": "Yorkshire",
                  "homeTeam_short": "YORKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/YORKS.jpg",
                  "homeTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  },
                  "awayTeam_id": 62,
                  "awayTeam_name": "Leicestershire",
                  "awayTeam_short": "LEIC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LEIC.jpg",
                  "awayTeamScore": {
                        "score": null,
                        "over": null,
                        "wickets": null
                  }
            }
      ]
}
```
{% endswagger-response %}
{% endswagger %}
