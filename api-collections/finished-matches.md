# Finished Matches

&#x20;**Finished Matches Fixtures API**

{% swagger method="get" path="fixtures_finished" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Finished Matches API" %}
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
            },
            {
                  "match_id": 1351,
                  "series": "Sri Lanka Women tour of Pakistan",
                  "match_start": "28-05-2022 14:30:00",
                  "match_round": "3rd T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Pakistan Women won by 4 wickets",
                  "winnerTeam": "Pakistan Women",
                  "homeTeam_id": 94,
                  "homeTeam_name": "Pakistan Women",
                  "homeTeam_short": "PAK - W",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PAK - W.jpg",
                  "homeTeamScore": {
                        "score": "108",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 156,
                  "awayTeam_name": "Sri Lanka Women",
                  "awayTeam_short": "SL-W",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SL-W.jpg",
                  "awayTeamScore": {
                        "score": "107",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1372,
                  "series": "T20 Blast ",
                  "match_start": "27-05-2022 23:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Match Tied",
                  "winnerTeam": null,
                  "homeTeam_id": 50,
                  "homeTeam_name": "Lancashire",
                  "homeTeam_short": "LANCS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LANCS.jpg",
                  "homeTeamScore": {
                        "score": "183",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 64,
                  "awayTeam_name": "Yorkshire",
                  "awayTeam_short": "YORKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/YORKS.jpg",
                  "awayTeamScore": {
                        "score": "183",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1374,
                  "series": "T20 Blast ",
                  "match_start": "27-05-2022 23:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Nottinghamshire won by 4 wickets",
                  "winnerTeam": null,
                  "homeTeam_id": 53,
                  "homeTeam_name": "Nottinghamshire",
                  "homeTeam_short": "NOTTS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NOTTS.jpg",
                  "homeTeamScore": {
                        "score": "",
                        "wickets": "",
                        "over": ""
                  },
                  "awayTeam_id": 52,
                  "awayTeam_name": "Worcestershire",
                  "awayTeam_short": "WORCS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/WORCS.jpg",
                  "awayTeamScore": {
                        "score": "",
                        "wickets": "",
                        "over": ""
                  }
            },
            {
                  "match_id": 1366,
                  "series": "Indian Premier League ",
                  "match_start": "27-05-2022 19:30:00",
                  "match_round": "Qualifier 2",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 7 wickets",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "161",
                        "wickets": "3",
                        "over": "18.1"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "157",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1368,
                  "series": "T20 Blast ",
                  "match_start": "26-05-2022 23:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Warwickshire won by 125 runs",
                  "winnerTeam": "Warwickshire",
                  "homeTeam_id": 63,
                  "homeTeam_name": "Warwickshire",
                  "homeTeam_short": "WARKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/WARKS.jpg",
                  "homeTeamScore": {
                        "score": "207",
                        "wickets": "3",
                        "over": "16"
                  },
                  "awayTeam_id": 65,
                  "awayTeam_name": "Northamptonshire",
                  "awayTeam_short": "NOR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NOR.jpg",
                  "awayTeamScore": {
                        "score": "81",
                        "wickets": "10",
                        "over": "14.2"
                  }
            },
            {
                  "match_id": 1369,
                  "series": "T20 Blast ",
                  "match_start": "26-05-2022 23:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Durham won by 54 runs",
                  "winnerTeam": "Durham",
                  "homeTeam_id": 62,
                  "homeTeam_name": "Leicestershire",
                  "homeTeam_short": "LEIC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LEIC.jpg",
                  "homeTeamScore": {
                        "score": "130",
                        "wickets": "10",
                        "over": "17.5"
                  },
                  "awayTeam_id": 66,
                  "awayTeam_name": "Durham",
                  "awayTeam_short": "DUR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DUR.jpg",
                  "awayTeamScore": {
                        "score": "184",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1363,
                  "series": "T20 Blast ",
                  "match_start": "26-05-2022 21:00:00",
                  "match_round": "South Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Middlesex won by 30 runs",
                  "winnerTeam": "Middlesex",
                  "homeTeam_id": 60,
                  "homeTeam_name": "Middlesex",
                  "homeTeam_short": "MDX",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MDX.jpg",
                  "homeTeamScore": {
                        "score": "229",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 59,
                  "awayTeam_name": "Gloucestershire",
                  "awayTeam_short": "GLOUCS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GLOUCS.jpg",
                  "awayTeamScore": {
                        "score": "199",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1506,
                  "series": "Womens T20 Challenge ",
                  "match_start": "26-05-2022 19:30:00",
                  "match_round": "3rd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Trailblazers won by 16 runs",
                  "winnerTeam": "Trailblazers",
                  "homeTeam_id": 159,
                  "homeTeam_name": "Velocity",
                  "homeTeam_short": "VEL",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/VEL.jpg",
                  "homeTeamScore": {
                        "score": "174",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 157,
                  "awayTeam_name": "Trailblazers",
                  "awayTeam_short": "TRL",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/TRL.jpg",
                  "awayTeamScore": {
                        "score": "190",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1350,
                  "series": "Sri Lanka Women tour of Pakistan",
                  "match_start": "26-05-2022 14:30:00",
                  "match_round": "2nd T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Pakistan Women won by 7 wickets",
                  "winnerTeam": "Pakistan Women",
                  "homeTeam_id": 94,
                  "homeTeam_name": "Pakistan Women",
                  "homeTeam_short": "PAK - W",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PAK - W.jpg",
                  "homeTeamScore": {
                        "score": "104",
                        "wickets": "3",
                        "over": "17.1"
                  },
                  "awayTeam_id": 156,
                  "awayTeam_name": "Sri Lanka Women",
                  "awayTeam_short": "SL-W",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SL-W.jpg",
                  "awayTeamScore": {
                        "score": "102",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1362,
                  "series": "T20 Blast ",
                  "match_start": "25-05-2022 23:30:00",
                  "match_round": "South Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Somerset won by 8 wickets",
                  "winnerTeam": "Somerset",
                  "homeTeam_id": 54,
                  "homeTeam_name": "Kent",
                  "homeTeam_short": "KENT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KENT.jpg",
                  "homeTeamScore": {
                        "score": "162",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 56,
                  "awayTeam_name": "Somerset",
                  "awayTeam_short": "SOM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SOM.jpg",
                  "awayTeamScore": {
                        "score": "166",
                        "wickets": "2",
                        "over": "19.1"
                  }
            },
            {
                  "match_id": 1361,
                  "series": "T20 Blast ",
                  "match_start": "25-05-2022 23:00:00",
                  "match_round": "North Group",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Yorkshire won by 7 wickets",
                  "winnerTeam": "Yorkshire",
                  "homeTeam_id": 64,
                  "homeTeam_name": "Yorkshire",
                  "homeTeam_short": "YORKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/YORKS.jpg",
                  "homeTeamScore": {
                        "score": "175",
                        "wickets": "3",
                        "over": "18.1"
                  },
                  "awayTeam_id": 52,
                  "awayTeam_name": "Worcestershire",
                  "awayTeam_short": "WORCS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/WORCS.jpg",
                  "awayTeamScore": {
                        "score": "172",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1365,
                  "series": "Indian Premier League ",
                  "match_start": "25-05-2022 19:30:00",
                  "match_round": "Eliminator",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 14 runs",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "193",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "207",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1364,
                  "series": "Indian Premier League ",
                  "match_start": "24-05-2022 19:30:00",
                  "match_round": "Qualifier 1",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 7 wickets",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "191",
                        "wickets": "3",
                        "over": "19.3"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "188",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1330,
                  "series": "Namibia tour of Zimbabwe",
                  "match_start": "24-05-2022 16:30:00",
                  "match_round": "5th T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Namibia won by 32 runs",
                  "winnerTeam": null,
                  "homeTeam_id": 16,
                  "homeTeam_name": "Zimbabwe",
                  "homeTeam_short": "ZIM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ZIM.jpg",
                  "homeTeamScore": {
                        "score": "",
                        "wickets": "",
                        "over": ""
                  },
                  "awayTeam_id": 105,
                  "awayTeam_name": "Namibia",
                  "awayTeam_short": "NAM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NAM.jpg",
                  "awayTeamScore": {
                        "score": "",
                        "wickets": "",
                        "over": ""
                  }
            },
            {
                  "match_id": 1505,
                  "series": "Womens T20 Challenge ",
                  "match_start": "24-05-2022 15:30:00",
                  "match_round": "2nd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Velocity won by 7 wickets",
                  "winnerTeam": "Velocity",
                  "homeTeam_id": 158,
                  "homeTeam_name": "Supernovas",
                  "homeTeam_short": "SPN",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SPN.jpg",
                  "homeTeamScore": {
                        "score": "150",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 159,
                  "awayTeam_name": "Velocity",
                  "awayTeam_short": "VEL",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/VEL.jpg",
                  "awayTeamScore": {
                        "score": "151",
                        "wickets": "3",
                        "over": "18.2"
                  }
            },
            {
                  "match_id": 1349,
                  "series": "Sri Lanka Women tour of Pakistan",
                  "match_start": "24-05-2022 14:30:00",
                  "match_round": "1st T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Pakistan Women won by 6 wickets",
                  "winnerTeam": "Pakistan Women",
                  "homeTeam_id": 94,
                  "homeTeam_name": "Pakistan Women",
                  "homeTeam_short": "PAK - W",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PAK - W.jpg",
                  "homeTeamScore": {
                        "score": "107",
                        "wickets": "4",
                        "over": "18.2"
                  },
                  "awayTeam_id": 156,
                  "awayTeam_name": "Sri Lanka Women",
                  "awayTeam_short": "SL-W",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SL-W.jpg",
                  "awayTeamScore": {
                        "score": "106",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1504,
                  "series": "Womens T20 Challenge ",
                  "match_start": "23-05-2022 19:30:00",
                  "match_round": "1st Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Supernovas won by 49 runs",
                  "winnerTeam": "Supernovas",
                  "homeTeam_id": 157,
                  "homeTeam_name": "Trailblazers",
                  "homeTeam_short": "TRL",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/TRL.jpg",
                  "homeTeamScore": {
                        "score": "114",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 158,
                  "awayTeam_name": "Supernovas",
                  "awayTeam_short": "SPN",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SPN.jpg",
                  "awayTeamScore": {
                        "score": "163",
                        "wickets": "10",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1319,
                  "series": "Sri Lanka tour of Bangladesh",
                  "match_start": "23-05-2022 10:00:00",
                  "match_round": "2nd Test",
                  "match_type": "Test",
                  "match_status": "Finished",
                  "summery": "Sri Lanka won by 10 wickets",
                  "winnerTeam": "Sri Lanka",
                  "homeTeam_id": 10,
                  "homeTeam_name": "Bangladesh",
                  "homeTeam_short": "BAN",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/BAN.jpg",
                  "homeTeamScore": {
                        "score": "365",
                        "wickets": "10",
                        "over": "116.2 & 55.3"
                  },
                  "awayTeam_id": 17,
                  "awayTeam_name": "Sri Lanka",
                  "awayTeam_short": "SL",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SL.jpg",
                  "awayTeamScore": {
                        "score": "506",
                        "wickets": "0",
                        "over": "165.1 & 3"
                  }
            },
            {
                  "match_id": 1302,
                  "series": "Indian Premier League ",
                  "match_start": "22-05-2022 19:30:00",
                  "match_round": "70th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Punjab Kings won by 5 wickets",
                  "winnerTeam": "Punjab Kings",
                  "homeTeam_id": 31,
                  "homeTeam_name": "Sunrisers Hyderabad",
                  "homeTeam_short": "SRH",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "homeTeamScore": {
                        "score": "157",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "160",
                        "wickets": "5",
                        "over": "15.1"
                  }
            },
            {
                  "match_id": 1329,
                  "series": "Namibia tour of Zimbabwe",
                  "match_start": "22-05-2022 16:30:00",
                  "match_round": "4th T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Namibia won by 6 wickets",
                  "winnerTeam": "Namibia",
                  "homeTeam_id": 16,
                  "homeTeam_name": "Zimbabwe",
                  "homeTeam_short": "ZIM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ZIM.jpg",
                  "homeTeamScore": {
                        "score": "157",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 105,
                  "awayTeam_name": "Namibia",
                  "awayTeam_short": "NAM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NAM.jpg",
                  "awayTeamScore": {
                        "score": "161",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1301,
                  "series": "Indian Premier League ",
                  "match_start": "21-05-2022 19:30:00",
                  "match_round": "69th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Mumbai Indians won by 5 wickets",
                  "winnerTeam": "Mumbai Indians",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "160",
                        "wickets": "5",
                        "over": "19.1"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "159",
                        "wickets": "7",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1328,
                  "series": "Namibia tour of Zimbabwe",
                  "match_start": "21-05-2022 16:30:00",
                  "match_round": "3rd T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Zimbabwe won by 8 wickets",
                  "winnerTeam": "Zimbabwe",
                  "homeTeam_id": 16,
                  "homeTeam_name": "Zimbabwe",
                  "homeTeam_short": "ZIM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ZIM.jpg",
                  "homeTeamScore": {
                        "score": "129",
                        "wickets": "2",
                        "over": "17.1"
                  },
                  "awayTeam_id": 105,
                  "awayTeam_name": "Namibia",
                  "awayTeam_short": "NAM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NAM.jpg",
                  "awayTeamScore": {
                        "score": "128",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1300,
                  "series": "Indian Premier League ",
                  "match_start": "20-05-2022 19:30:00",
                  "match_round": "68th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 5 wickets",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "151",
                        "wickets": "5",
                        "over": "19.4"
                  },
                  "awayTeam_id": 29,
                  "awayTeam_name": "Chennai Super Kings",
                  "awayTeam_short": "CSK",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "awayTeamScore": {
                        "score": "150",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1299,
                  "series": "Indian Premier League ",
                  "match_start": "19-05-2022 19:30:00",
                  "match_round": "67th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 8 wickets",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 28,
                  "homeTeam_name": "Royal Challengers Bangalore",
                  "homeTeam_short": "RCB",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "homeTeamScore": {
                        "score": "170",
                        "wickets": "2",
                        "over": "18.4"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "168",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1327,
                  "series": "Namibia tour of Zimbabwe",
                  "match_start": "19-05-2022 16:30:00",
                  "match_round": "2nd T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Namibia won by 8 wickets",
                  "winnerTeam": "Namibia",
                  "homeTeam_id": 16,
                  "homeTeam_name": "Zimbabwe",
                  "homeTeam_short": "ZIM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ZIM.jpg",
                  "homeTeamScore": {
                        "score": "122",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 105,
                  "awayTeam_name": "Namibia",
                  "awayTeam_short": "NAM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NAM.jpg",
                  "awayTeamScore": {
                        "score": "124",
                        "wickets": "2",
                        "over": "18"
                  }
            },
            {
                  "match_id": 1298,
                  "series": "Indian Premier League ",
                  "match_start": "18-05-2022 19:30:00",
                  "match_round": "66th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 2 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "208",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 155,
                  "awayTeam_name": "Lucknow Super Giants",
                  "awayTeam_short": "LSG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "awayTeamScore": {
                        "score": "210",
                        "wickets": "0",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1297,
                  "series": "Indian Premier League ",
                  "match_start": "17-05-2022 19:30:00",
                  "match_round": "65th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Sunrisers Hyderabad won by 3 runs",
                  "winnerTeam": "Sunrisers Hyderabad",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "190",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "193",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1326,
                  "series": "Namibia tour of Zimbabwe",
                  "match_start": "17-05-2022 16:30:00",
                  "match_round": "1st T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Zimbabwe won by 7 runs",
                  "winnerTeam": "Zimbabwe",
                  "homeTeam_id": 16,
                  "homeTeam_name": "Zimbabwe",
                  "homeTeam_short": "ZIM",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ZIM.jpg",
                  "homeTeamScore": {
                        "score": "153",
                        "wickets": "4",
                        "over": "20"
                  },
                  "awayTeam_id": 105,
                  "awayTeam_name": "Namibia",
                  "awayTeam_short": "NAM",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NAM.jpg",
                  "awayTeamScore": {
                        "score": "146",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1296,
                  "series": "Indian Premier League ",
                  "match_start": "16-05-2022 19:30:00",
                  "match_round": "64th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Delhi Capitals won by 17 runs",
                  "winnerTeam": "Delhi Capitals ",
                  "homeTeam_id": 34,
                  "homeTeam_name": "Punjab Kings",
                  "homeTeam_short": "PBKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "homeTeamScore": {
                        "score": "142",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "159",
                        "wickets": "7",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1295,
                  "series": "Indian Premier League ",
                  "match_start": "15-05-2022 19:30:00",
                  "match_round": "63rd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 24 runs",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "154",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "178",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1294,
                  "series": "Indian Premier League ",
                  "match_start": "15-05-2022 15:30:00",
                  "match_round": "62nd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 7 wickets",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 29,
                  "homeTeam_name": "Chennai Super Kings",
                  "homeTeam_short": "CSK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "homeTeamScore": {
                        "score": "133",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "137",
                        "wickets": "3",
                        "over": "19.1"
                  }
            },
            {
                  "match_id": 1318,
                  "series": "Sri Lanka tour of Bangladesh",
                  "match_start": "15-05-2022 09:30:00",
                  "match_round": "1st Test",
                  "match_type": "Test",
                  "match_status": "Finished",
                  "summery": "Match drawn",
                  "winnerTeam": "Bangladesh",
                  "homeTeam_id": 10,
                  "homeTeam_name": "Bangladesh",
                  "homeTeam_short": "BAN",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/BAN.jpg",
                  "homeTeamScore": {
                        "score": "465",
                        "wickets": "9",
                        "over": "170.1"
                  },
                  "awayTeam_id": 17,
                  "awayTeam_name": "Sri Lanka",
                  "awayTeam_short": "SL",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SL.jpg",
                  "awayTeamScore": {
                        "score": "397",
                        "wickets": "6",
                        "over": "153 & 90.1"
                  }
            },
            {
                  "match_id": 1293,
                  "series": "Indian Premier League ",
                  "match_start": "14-05-2022 19:30:00",
                  "match_round": "61st Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Kolkata Knight Riders won by 54 runs",
                  "winnerTeam": "Kolkata Knight Riders",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "177",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "123",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1292,
                  "series": "Indian Premier League ",
                  "match_start": "13-05-2022 19:30:00",
                  "match_round": "60th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Punjab Kings won by 54 runs",
                  "winnerTeam": "Punjab Kings",
                  "homeTeam_id": 28,
                  "homeTeam_name": "Royal Challengers Bangalore",
                  "homeTeam_short": "RCB",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "homeTeamScore": {
                        "score": "155",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "209",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1291,
                  "series": "Indian Premier League ",
                  "match_start": "12-05-2022 19:30:00",
                  "match_round": "59th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Mumbai Indians won by 5 wickets",
                  "winnerTeam": "Mumbai Indians",
                  "homeTeam_id": 29,
                  "homeTeam_name": "Chennai Super Kings",
                  "homeTeam_short": "CSK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "homeTeamScore": {
                        "score": "97",
                        "wickets": "10",
                        "over": "16"
                  },
                  "awayTeam_id": 27,
                  "awayTeam_name": "Mumbai Indians",
                  "awayTeam_short": "MI",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "awayTeamScore": {
                        "score": "103",
                        "wickets": "5",
                        "over": "14.5"
                  }
            },
            {
                  "match_id": 1290,
                  "series": "Indian Premier League ",
                  "match_start": "11-05-2022 19:30:00",
                  "match_round": "58th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Delhi Capitals won by 8 wickets",
                  "winnerTeam": "Delhi Capitals ",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "160",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "161",
                        "wickets": "2",
                        "over": "18.1"
                  }
            },
            {
                  "match_id": 1289,
                  "series": "Indian Premier League ",
                  "match_start": "10-05-2022 19:30:00",
                  "match_round": "57th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 62 runs",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "82",
                        "wickets": "10",
                        "over": "13.5"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "144",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1288,
                  "series": "Indian Premier League ",
                  "match_start": "09-05-2022 19:30:00",
                  "match_round": "56th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Kolkata Knight Riders won by 52 runs",
                  "winnerTeam": "Kolkata Knight Riders",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "113",
                        "wickets": "10",
                        "over": "17.3"
                  },
                  "awayTeam_id": 32,
                  "awayTeam_name": "Kolkata Knight Riders",
                  "awayTeam_short": "KKR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "awayTeamScore": {
                        "score": "165",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1287,
                  "series": "Indian Premier League ",
                  "match_start": "08-05-2022 19:30:00",
                  "match_round": "55th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Chennai Super Kings won by 91 runs",
                  "winnerTeam": "Chennai Super Kings",
                  "homeTeam_id": 29,
                  "homeTeam_name": "Chennai Super Kings",
                  "homeTeam_short": "CSK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "homeTeamScore": {
                        "score": "208",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "117",
                        "wickets": "10",
                        "over": "17.4"
                  }
            },
            {
                  "match_id": 1286,
                  "series": "Indian Premier League ",
                  "match_start": "08-05-2022 15:30:00",
                  "match_round": "54th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 67 runs",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 31,
                  "homeTeam_name": "Sunrisers Hyderabad",
                  "homeTeam_short": "SRH",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "homeTeamScore": {
                        "score": "125",
                        "wickets": "10",
                        "over": "19.2"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "192",
                        "wickets": "3",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1285,
                  "series": "Indian Premier League ",
                  "match_start": "07-05-2022 19:30:00",
                  "match_round": "53rd match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 75 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "176",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 32,
                  "awayTeam_name": "Kolkata Knight Riders",
                  "awayTeam_short": "KKR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "awayTeamScore": {
                        "score": "101",
                        "wickets": "10",
                        "over": "14.3"
                  }
            },
            {
                  "match_id": 1284,
                  "series": "Indian Premier League ",
                  "match_start": "07-05-2022 15:30:00",
                  "match_round": "52nd match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 6 wickets",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 34,
                  "homeTeam_name": "Punjab Kings",
                  "homeTeam_short": "PBKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "homeTeamScore": {
                        "score": "189",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "190",
                        "wickets": "4",
                        "over": "19.4"
                  }
            },
            {
                  "match_id": 1283,
                  "series": "Indian Premier League ",
                  "match_start": "06-05-2022 19:30:00",
                  "match_round": "51st match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Mumbai Indians won by 5 runs",
                  "winnerTeam": "Mumbai Indians",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "172",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 27,
                  "awayTeam_name": "Mumbai Indians",
                  "awayTeam_short": "MI",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "awayTeamScore": {
                        "score": "177",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1282,
                  "series": "Indian Premier League ",
                  "match_start": "05-05-2022 19:30:00",
                  "match_round": "50th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Delhi Capitals won by 21 runs",
                  "winnerTeam": "Delhi Capitals ",
                  "homeTeam_id": 30,
                  "homeTeam_name": "Delhi Capitals ",
                  "homeTeam_short": "DC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "homeTeamScore": {
                        "score": "207",
                        "wickets": "3",
                        "over": "20"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "186",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1281,
                  "series": "Indian Premier League ",
                  "match_start": "04-05-2022 19:30:00",
                  "match_round": "49th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 13 runs",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 28,
                  "homeTeam_name": "Royal Challengers Bangalore",
                  "homeTeam_short": "RCB",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "homeTeamScore": {
                        "score": "173",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 29,
                  "awayTeam_name": "Chennai Super Kings",
                  "awayTeam_short": "CSK",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "awayTeamScore": {
                        "score": "160",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1280,
                  "series": "Indian Premier League ",
                  "match_start": "03-05-2022 19:30:00",
                  "match_round": "48th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Punjab Kings won by 8 wickets",
                  "winnerTeam": "Punjab Kings",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "143",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "147",
                        "wickets": "2",
                        "over": "16"
                  }
            },
            {
                  "match_id": 1279,
                  "series": "Indian Premier League ",
                  "match_start": "02-05-2022 19:30:00",
                  "match_round": "47th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Kolkata Knight Riders won by 7 wickets",
                  "winnerTeam": "Kolkata Knight Riders",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "158",
                        "wickets": "3",
                        "over": "19.1"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "152",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1278,
                  "series": "Indian Premier League ",
                  "match_start": "01-05-2022 19:30:00",
                  "match_round": "46th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Chennai Super Kings won by 13 runs",
                  "winnerTeam": "Chennai Super Kings",
                  "homeTeam_id": 31,
                  "homeTeam_name": "Sunrisers Hyderabad",
                  "homeTeam_short": "SRH",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "homeTeamScore": {
                        "score": "189",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 29,
                  "awayTeam_name": "Chennai Super Kings",
                  "awayTeam_short": "CSK",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "awayTeamScore": {
                        "score": "202",
                        "wickets": "2",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1277,
                  "series": "Indian Premier League ",
                  "match_start": "01-05-2022 15:30:00",
                  "match_round": "45th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 6 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 30,
                  "homeTeam_name": "Delhi Capitals ",
                  "homeTeam_short": "DC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "homeTeamScore": {
                        "score": "189",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 155,
                  "awayTeam_name": "Lucknow Super Giants",
                  "awayTeam_short": "LSG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "awayTeamScore": {
                        "score": "195",
                        "wickets": "3",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1276,
                  "series": "Indian Premier League ",
                  "match_start": "30-04-2022 19:30:00",
                  "match_round": "44th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Mumbai Indians won by 5 wickets",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "158",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 27,
                  "awayTeam_name": "Mumbai Indians",
                  "awayTeam_short": "MI",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "awayTeamScore": {
                        "score": "155",
                        "wickets": "5",
                        "over": "19.1"
                  }
            },
            {
                  "match_id": 1275,
                  "series": "Indian Premier League ",
                  "match_start": "30-04-2022 15:30:00",
                  "match_round": "43rd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 6 wickets",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "174",
                        "wickets": "4",
                        "over": "19.3"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "170",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1274,
                  "series": "Indian Premier League ",
                  "match_start": "29-04-2022 19:30:00",
                  "match_round": "42nd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 20 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 34,
                  "homeTeam_name": "Punjab Kings",
                  "homeTeam_short": "PBKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "homeTeamScore": {
                        "score": "133",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 155,
                  "awayTeam_name": "Lucknow Super Giants",
                  "awayTeam_short": "LSG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "awayTeamScore": {
                        "score": "153",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1273,
                  "series": "Indian Premier League ",
                  "match_start": "28-04-2022 19:30:00",
                  "match_round": "41st Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Delhi Capitals won by 4 wickets",
                  "winnerTeam": "Kolkata Knight Riders",
                  "homeTeam_id": 30,
                  "homeTeam_name": "Delhi Capitals ",
                  "homeTeam_short": "DC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "homeTeamScore": {
                        "score": "",
                        "wickets": "",
                        "over": ""
                  },
                  "awayTeam_id": 32,
                  "awayTeam_name": "Kolkata Knight Riders",
                  "awayTeam_short": "KKR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "awayTeamScore": {
                        "score": "146",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1272,
                  "series": "Indian Premier League ",
                  "match_start": "27-04-2022 19:30:00",
                  "match_round": "40th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 5 wickets",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "199",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "195",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1271,
                  "series": "Indian Premier League ",
                  "match_start": "26-04-2022 19:30:00",
                  "match_round": "39th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 29 runs",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 28,
                  "homeTeam_name": "Royal Challengers Bangalore",
                  "homeTeam_short": "RCB",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "homeTeamScore": {
                        "score": "115",
                        "wickets": "10",
                        "over": "19.3"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "144",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1270,
                  "series": "Indian Premier League ",
                  "match_start": "25-04-2022 19:30:00",
                  "match_round": "38th match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Punjab Kings won by 11 runs",
                  "winnerTeam": "Punjab Kings",
                  "homeTeam_id": 34,
                  "homeTeam_name": "Punjab Kings",
                  "homeTeam_short": "PBKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "homeTeamScore": {
                        "score": "187",
                        "wickets": "4",
                        "over": "20"
                  },
                  "awayTeam_id": 29,
                  "awayTeam_name": "Chennai Super Kings",
                  "awayTeam_short": "CSK",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "awayTeamScore": {
                        "score": "176",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1269,
                  "series": "Indian Premier League ",
                  "match_start": "24-04-2022 19:30:00",
                  "match_round": "37th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 36 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "168",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 27,
                  "awayTeam_name": "Mumbai Indians",
                  "awayTeam_short": "MI",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "awayTeamScore": {
                        "score": "132",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1268,
                  "series": "Indian Premier League ",
                  "match_start": "23-04-2022 19:30:00",
                  "match_round": "36th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Sunrisers Hyderabad won by 9 wickets",
                  "winnerTeam": "Sunrisers Hyderabad",
                  "homeTeam_id": 28,
                  "homeTeam_name": "Royal Challengers Bangalore",
                  "homeTeam_short": "RCB",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "homeTeamScore": {
                        "score": "68",
                        "wickets": "10",
                        "over": "16.1"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "72",
                        "wickets": "1",
                        "over": "8"
                  }
            },
            {
                  "match_id": 1267,
                  "series": "Indian Premier League ",
                  "match_start": "23-04-2022 15:30:00",
                  "match_round": "35th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 8 runs",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "148",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "156",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1266,
                  "series": "Indian Premier League ",
                  "match_start": "22-04-2022 19:30:00",
                  "match_round": "34th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 15 runs",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 30,
                  "homeTeam_name": "Delhi Capitals ",
                  "homeTeam_short": "DC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "homeTeamScore": {
                        "score": "207",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "222",
                        "wickets": "2",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1265,
                  "series": "Indian Premier League ",
                  "match_start": "21-04-2022 19:30:00",
                  "match_round": "33rd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Chennai Super Kings won by 3 wickets",
                  "winnerTeam": "Chennai Super Kings",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "155",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 29,
                  "awayTeam_name": "Chennai Super Kings",
                  "awayTeam_short": "CSK",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "awayTeamScore": {
                        "score": "156",
                        "wickets": "7",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1264,
                  "series": "Indian Premier League ",
                  "match_start": "20-04-2022 19:30:00",
                  "match_round": "32nd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Delhi Capitals won by 9 wickets",
                  "winnerTeam": "Delhi Capitals ",
                  "homeTeam_id": 30,
                  "homeTeam_name": "Delhi Capitals ",
                  "homeTeam_short": "DC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "homeTeamScore": {
                        "score": "119",
                        "wickets": "1",
                        "over": "10.3"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "115",
                        "wickets": "10",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1263,
                  "series": "Indian Premier League ",
                  "match_start": "19-04-2022 19:30:00",
                  "match_round": "31st Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 18 runs",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "163",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "181",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1262,
                  "series": "Indian Premier League ",
                  "match_start": "18-04-2022 19:30:00",
                  "match_round": "30th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 7 runs",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "217",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 32,
                  "awayTeam_name": "Kolkata Knight Riders",
                  "awayTeam_short": "KKR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "awayTeamScore": {
                        "score": "210",
                        "wickets": "10",
                        "over": "19.4"
                  }
            },
            {
                  "match_id": 1261,
                  "series": "Indian Premier League ",
                  "match_start": "17-04-2022 19:30:00",
                  "match_round": "29th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 3 wickets",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "170",
                        "wickets": "7",
                        "over": "19.5"
                  },
                  "awayTeam_id": 29,
                  "awayTeam_name": "Chennai Super Kings",
                  "awayTeam_short": "CSK",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "awayTeamScore": {
                        "score": "169",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1260,
                  "series": "Indian Premier League ",
                  "match_start": "17-04-2022 15:30:00",
                  "match_round": "28th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Sunrisers Hyderabad won by 7 wickets",
                  "winnerTeam": "Sunrisers Hyderabad",
                  "homeTeam_id": 34,
                  "homeTeam_name": "Punjab Kings",
                  "homeTeam_short": "PBKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "homeTeamScore": {
                        "score": "151",
                        "wickets": "10",
                        "over": "20"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "152",
                        "wickets": "3",
                        "over": "18.5"
                  }
            },
            {
                  "match_id": 1259,
                  "series": "Indian Premier League ",
                  "match_start": "16-04-2022 19:30:00",
                  "match_round": "27th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 16 runs",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 30,
                  "homeTeam_name": "Delhi Capitals ",
                  "homeTeam_short": "DC",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "homeTeamScore": {
                        "score": "173",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "189",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1258,
                  "series": "Indian Premier League ",
                  "match_start": "16-04-2022 15:30:00",
                  "match_round": "26th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 18 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "181",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 155,
                  "awayTeam_name": "Lucknow Super Giants",
                  "awayTeam_short": "LSG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "awayTeamScore": {
                        "score": "199",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1257,
                  "series": "Indian Premier League ",
                  "match_start": "15-04-2022 19:30:00",
                  "match_round": "25th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Sunrisers Hyderabad won by 7 wickets",
                  "winnerTeam": "Sunrisers Hyderabad",
                  "homeTeam_id": 31,
                  "homeTeam_name": "Sunrisers Hyderabad",
                  "homeTeam_short": "SRH",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "homeTeamScore": {
                        "score": "176",
                        "wickets": "3",
                        "over": "17.5"
                  },
                  "awayTeam_id": 32,
                  "awayTeam_name": "Kolkata Knight Riders",
                  "awayTeam_short": "KKR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "awayTeamScore": {
                        "score": "175",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1256,
                  "series": "Indian Premier League ",
                  "match_start": "14-04-2022 19:30:00",
                  "match_round": "24th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 37 runs",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "155",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "192",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1255,
                  "series": "Indian Premier League ",
                  "match_start": "13-04-2022 19:30:00",
                  "match_round": "23rd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Punjab Kings won by 12 runs",
                  "winnerTeam": "Punjab Kings",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "186",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "198",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1254,
                  "series": "Indian Premier League ",
                  "match_start": "12-04-2022 19:30:00",
                  "match_round": "22nd Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Chennai Super Kings won by 23 runs",
                  "winnerTeam": "Chennai Super Kings",
                  "homeTeam_id": 29,
                  "homeTeam_name": "Chennai Super Kings",
                  "homeTeam_short": "CSK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "homeTeamScore": {
                        "score": "216",
                        "wickets": "4",
                        "over": "20"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "193",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1253,
                  "series": "Indian Premier League ",
                  "match_start": "11-04-2022 19:30:00",
                  "match_round": "21st Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Sunrisers Hyderabad won by 8 wickets",
                  "winnerTeam": "Sunrisers Hyderabad",
                  "homeTeam_id": 31,
                  "homeTeam_name": "Sunrisers Hyderabad",
                  "homeTeam_short": "SRH",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "homeTeamScore": {
                        "score": "168",
                        "wickets": "2",
                        "over": "19.1"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "162",
                        "wickets": "7",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1252,
                  "series": "Indian Premier League ",
                  "match_start": "10-04-2022 19:30:00",
                  "match_round": "20th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 3 runs",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "165",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 155,
                  "awayTeam_name": "Lucknow Super Giants",
                  "awayTeam_short": "LSG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "awayTeamScore": {
                        "score": "162",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1251,
                  "series": "Indian Premier League ",
                  "match_start": "10-04-2022 15:30:00",
                  "match_round": "19th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Delhi Capitals won by 44 runs",
                  "winnerTeam": "Delhi Capitals ",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "171",
                        "wickets": "10",
                        "over": "19.4"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "215",
                        "wickets": "5",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1250,
                  "series": "Indian Premier League ",
                  "match_start": "09-04-2022 19:30:00",
                  "match_round": "18th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 7 wickets",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 28,
                  "homeTeam_name": "Royal Challengers Bangalore",
                  "homeTeam_short": "RCB",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "homeTeamScore": {
                        "score": "152",
                        "wickets": "3",
                        "over": "18.3"
                  },
                  "awayTeam_id": 27,
                  "awayTeam_name": "Mumbai Indians",
                  "awayTeam_short": "MI",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "awayTeamScore": {
                        "score": "151",
                        "wickets": "6",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1249,
                  "series": "Indian Premier League ",
                  "match_start": "09-04-2022 15:30:00",
                  "match_round": "17th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Sunrisers Hyderabad won by 8 wickets",
                  "winnerTeam": "Sunrisers Hyderabad",
                  "homeTeam_id": 29,
                  "homeTeam_name": "Chennai Super Kings",
                  "homeTeam_short": "CSK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "homeTeamScore": {
                        "score": "154",
                        "wickets": "7",
                        "over": "20"
                  },
                  "awayTeam_id": 31,
                  "awayTeam_name": "Sunrisers Hyderabad",
                  "awayTeam_short": "SRH",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "awayTeamScore": {
                        "score": "155",
                        "wickets": "2",
                        "over": "17.4"
                  }
            },
            {
                  "match_id": 1248,
                  "series": "Indian Premier League ",
                  "match_start": "08-04-2022 19:30:00",
                  "match_round": "16th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 6 wickets",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 34,
                  "homeTeam_name": "Punjab Kings",
                  "homeTeam_short": "PBKS",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "homeTeamScore": {
                        "score": "189",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 154,
                  "awayTeam_name": "Gujarat Titans",
                  "awayTeam_short": "GT",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "awayTeamScore": {
                        "score": "190",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1202,
                  "series": "Bangladesh tour of South Africa",
                  "match_start": "08-04-2022 13:30:00",
                  "match_round": "2nd Test",
                  "match_type": "Test",
                  "match_status": "Finished",
                  "summery": "South Africa won by 332 runs",
                  "winnerTeam": "South Africa",
                  "homeTeam_id": 9,
                  "homeTeam_name": "South Africa",
                  "homeTeam_short": "RSA",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RSA.jpg",
                  "homeTeamScore": {
                        "score": "453",
                        "wickets": "6",
                        "over": "136.2 & 39.5"
                  },
                  "awayTeam_id": 10,
                  "awayTeam_name": "Bangladesh",
                  "awayTeam_short": "BAN",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/BAN.jpg",
                  "awayTeamScore": {
                        "score": "217",
                        "wickets": "10",
                        "over": "74.2 & 23.3"
                  }
            },
            {
                  "match_id": 1247,
                  "series": "Indian Premier League ",
                  "match_start": "07-04-2022 19:30:00",
                  "match_round": "15th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 6 wickets",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 155,
                  "homeTeam_name": "Lucknow Super Giants",
                  "homeTeam_short": "LSG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "homeTeamScore": {
                        "score": "155",
                        "wickets": "4",
                        "over": "19.4"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "149",
                        "wickets": "3",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1246,
                  "series": "Indian Premier League ",
                  "match_start": "06-04-2022 19:30:00",
                  "match_round": "14th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Kolkata Knight Riders won by 5 wickets",
                  "winnerTeam": "Kolkata Knight Riders",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "162",
                        "wickets": "5",
                        "over": "16"
                  },
                  "awayTeam_id": 27,
                  "awayTeam_name": "Mumbai Indians",
                  "awayTeam_short": "MI",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "awayTeamScore": {
                        "score": "161",
                        "wickets": "4",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1151,
                  "series": "Australia tour of Pakistan",
                  "match_start": "05-04-2022 20:30:00",
                  "match_round": "Only T20I",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Australia won by 3 wickets",
                  "winnerTeam": "Australia",
                  "homeTeam_id": 8,
                  "homeTeam_name": "Pakistan",
                  "homeTeam_short": "PAK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PAK.jpg",
                  "homeTeamScore": {
                        "score": "162",
                        "wickets": "8",
                        "over": "20"
                  },
                  "awayTeam_id": 14,
                  "awayTeam_name": "Australia",
                  "awayTeam_short": "AUS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/AUS.jpg",
                  "awayTeamScore": {
                        "score": "163",
                        "wickets": "7",
                        "over": "19.1"
                  }
            },
            {
                  "match_id": 1245,
                  "series": "Indian Premier League ",
                  "match_start": "05-04-2022 19:30:00",
                  "match_round": "13th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Royal Challengers Bangalore won by 4 wickets",
                  "winnerTeam": "Royal Challengers Bangalore",
                  "homeTeam_id": 33,
                  "homeTeam_name": "Rajasthan Royals",
                  "homeTeam_short": "RR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "homeTeamScore": {
                        "score": "169",
                        "wickets": "3",
                        "over": "20"
                  },
                  "awayTeam_id": 28,
                  "awayTeam_name": "Royal Challengers Bangalore",
                  "awayTeam_short": "RCB",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RCB.jpg",
                  "awayTeamScore": {
                        "score": "173",
                        "wickets": "6",
                        "over": "19.1"
                  }
            },
            {
                  "match_id": 1244,
                  "series": "Indian Premier League ",
                  "match_start": "04-04-2022 19:30:00",
                  "match_round": "12th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Lucknow Super Giants won by 12 runs",
                  "winnerTeam": "Lucknow Super Giants",
                  "homeTeam_id": 31,
                  "homeTeam_name": "Sunrisers Hyderabad",
                  "homeTeam_short": "SRH",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/SRH.jpg",
                  "homeTeamScore": {
                        "score": "157",
                        "wickets": "9",
                        "over": "20"
                  },
                  "awayTeam_id": 155,
                  "awayTeam_name": "Lucknow Super Giants",
                  "awayTeam_short": "LSG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/LSG.jpg",
                  "awayTeamScore": {
                        "score": "169",
                        "wickets": "7",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1316,
                  "series": "Nepal T20I Tri-Series ",
                  "match_start": "04-04-2022 12:15:00",
                  "match_round": "Final",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Nepal won by 49 runs",
                  "winnerTeam": "Nepal",
                  "homeTeam_id": 37,
                  "homeTeam_name": "Nepal",
                  "homeTeam_short": "NEP",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NEP.jpg",
                  "homeTeamScore": {
                        "score": "168",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 90,
                  "awayTeam_name": "Papua New Guinea",
                  "awayTeam_short": "PNG",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PNG.jpg",
                  "awayTeamScore": {
                        "score": "118",
                        "wickets": "10",
                        "over": "16.1"
                  }
            },
            {
                  "match_id": 1216,
                  "series": "Netherlands tour of New Zealand",
                  "match_start": "04-04-2022 07:30:00",
                  "match_round": "3rd ODI",
                  "match_type": "ODI",
                  "match_status": "Finished",
                  "summery": "New Zealand won by 115 runs",
                  "winnerTeam": "New Zealand",
                  "homeTeam_id": 13,
                  "homeTeam_name": "New Zealand",
                  "homeTeam_short": "NZ",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NZ.jpg",
                  "homeTeamScore": {
                        "score": "333",
                        "wickets": "8",
                        "over": "50"
                  },
                  "awayTeam_id": 38,
                  "awayTeam_name": "Netherlands",
                  "awayTeam_short": "NED",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NED.jpg",
                  "awayTeamScore": {
                        "score": "218",
                        "wickets": "10",
                        "over": "42.3"
                  }
            },
            {
                  "match_id": 1243,
                  "series": "Indian Premier League ",
                  "match_start": "03-04-2022 19:30:00",
                  "match_round": "11th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Punjab Kings won by 54 runs",
                  "winnerTeam": "Punjab Kings",
                  "homeTeam_id": 29,
                  "homeTeam_name": "Chennai Super Kings",
                  "homeTeam_short": "CSK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/CSK.jpg",
                  "homeTeamScore": {
                        "score": "126",
                        "wickets": "10",
                        "over": "18"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "180",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1231,
                  "series": "ICC Womens World Cup",
                  "match_start": "03-04-2022 06:30:00",
                  "match_round": "Final",
                  "match_type": "ODI",
                  "match_status": "Finished",
                  "summery": "Australia Women won by 71 runs",
                  "winnerTeam": "Australia Women",
                  "homeTeam_id": 87,
                  "homeTeam_name": "Australia Women",
                  "homeTeam_short": "AUS-W",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/AUS-W.jpg",
                  "homeTeamScore": {
                        "score": "356",
                        "wickets": "5",
                        "over": "50"
                  },
                  "awayTeam_id": 85,
                  "awayTeam_name": "England Women",
                  "awayTeam_short": "ENG-W",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/ENG-W.jpg",
                  "awayTeamScore": {
                        "score": "285",
                        "wickets": "10",
                        "over": "43.4"
                  }
            },
            {
                  "match_id": 1242,
                  "series": "Indian Premier League ",
                  "match_start": "02-04-2022 19:30:00",
                  "match_round": "10th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Gujarat Titans won by 14 runs",
                  "winnerTeam": "Gujarat Titans",
                  "homeTeam_id": 154,
                  "homeTeam_name": "Gujarat Titans",
                  "homeTeam_short": "GT",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/GT.jpg",
                  "homeTeamScore": {
                        "score": "171",
                        "wickets": "6",
                        "over": "20"
                  },
                  "awayTeam_id": 30,
                  "awayTeam_name": "Delhi Capitals ",
                  "awayTeam_short": "DC",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/DC.jpg",
                  "awayTeamScore": {
                        "score": "157",
                        "wickets": "9",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1150,
                  "series": "Australia tour of Pakistan",
                  "match_start": "02-04-2022 15:30:00",
                  "match_round": "3rd ODI",
                  "match_type": "ODI",
                  "match_status": "Finished",
                  "summery": "Pakistan won by 9 wickets",
                  "winnerTeam": "Pakistan",
                  "homeTeam_id": 8,
                  "homeTeam_name": "Pakistan",
                  "homeTeam_short": "PAK",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PAK.jpg",
                  "homeTeamScore": {
                        "score": "214",
                        "wickets": "1",
                        "over": "37.5"
                  },
                  "awayTeam_id": 14,
                  "awayTeam_name": "Australia",
                  "awayTeam_short": "AUS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/AUS.jpg",
                  "awayTeamScore": {
                        "score": "210",
                        "wickets": "10",
                        "over": "41.5"
                  }
            },
            {
                  "match_id": 1241,
                  "series": "Indian Premier League ",
                  "match_start": "02-04-2022 15:30:00",
                  "match_round": "9th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Rajasthan Royals won by 23 runs",
                  "winnerTeam": "Rajasthan Royals",
                  "homeTeam_id": 27,
                  "homeTeam_name": "Mumbai Indians",
                  "homeTeam_short": "MI",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MI.jpg",
                  "homeTeamScore": {
                        "score": "170",
                        "wickets": "7",
                        "over": "19.3"
                  },
                  "awayTeam_id": 33,
                  "awayTeam_name": "Rajasthan Royals",
                  "awayTeam_short": "RR",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/RR.jpg",
                  "awayTeamScore": {
                        "score": "193",
                        "wickets": "8",
                        "over": "20"
                  }
            },
            {
                  "match_id": 1315,
                  "series": "Nepal T20I Tri-Series ",
                  "match_start": "02-04-2022 12:15:00",
                  "match_round": "6th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Nepal won by 86 runs",
                  "winnerTeam": "Nepal",
                  "homeTeam_id": 37,
                  "homeTeam_name": "Nepal",
                  "homeTeam_short": "NEP",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NEP.jpg",
                  "homeTeamScore": {
                        "score": "223",
                        "wickets": "5",
                        "over": "20"
                  },
                  "awayTeam_id": 39,
                  "awayTeam_name": "Malaysia",
                  "awayTeam_short": "MLY",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MLY.jpg",
                  "awayTeamScore": {
                        "score": "138",
                        "wickets": "10",
                        "over": "19.5"
                  }
            },
            {
                  "match_id": 1215,
                  "series": "Netherlands tour of New Zealand",
                  "match_start": "02-04-2022 06:30:00",
                  "match_round": "2nd ODI",
                  "match_type": "ODI",
                  "match_status": "Finished",
                  "summery": "New Zealand won by 118 runs",
                  "winnerTeam": "New Zealand",
                  "homeTeam_id": 13,
                  "homeTeam_name": "New Zealand",
                  "homeTeam_short": "NZ",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NZ.jpg",
                  "homeTeamScore": {
                        "score": "264",
                        "wickets": "9",
                        "over": "50"
                  },
                  "awayTeam_id": 38,
                  "awayTeam_name": "Netherlands",
                  "awayTeam_short": "NED",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/NED.jpg",
                  "awayTeamScore": {
                        "score": "146",
                        "wickets": "10",
                        "over": "34.1"
                  }
            },
            {
                  "match_id": 1240,
                  "series": "Indian Premier League ",
                  "match_start": "01-04-2022 19:30:00",
                  "match_round": "8th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Kolkata Knight Riders won by 6 wickets",
                  "winnerTeam": "Kolkata Knight Riders",
                  "homeTeam_id": 32,
                  "homeTeam_name": "Kolkata Knight Riders",
                  "homeTeam_short": "KKR",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/KKR.jpg",
                  "homeTeamScore": {
                        "score": "141",
                        "wickets": "4",
                        "over": "14.3"
                  },
                  "awayTeam_id": 34,
                  "awayTeam_name": "Punjab Kings",
                  "awayTeam_short": "PBKS",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PBKS.jpg",
                  "awayTeamScore": {
                        "score": "137",
                        "wickets": "10",
                        "over": "18.2"
                  }
            },
            {
                  "match_id": 1314,
                  "series": "Nepal T20I Tri-Series ",
                  "match_start": "01-04-2022 12:15:00",
                  "match_round": "5th Match",
                  "match_type": "T20",
                  "match_status": "Finished",
                  "summery": "Papua New Guinea won by 8 wickets",
                  "winnerTeam": "Papua New Guinea",
                  "homeTeam_id": 90,
                  "homeTeam_name": "Papua New Guinea",
                  "homeTeam_short": "PNG",
                  "homeTeam_logo": "http://127.0.0.1:8000/storage/team/flag/PNG.jpg",
                  "homeTeamScore": {
                        "score": "199",
                        "wickets": "2",
                        "over": "17.5"
                  },
                  "awayTeam_id": 39,
                  "awayTeam_name": "Malaysia",
                  "awayTeam_short": "MLY",
                  "awayTeam_logo": "http://127.0.0.1:8000/storage/team/flag/MLY.jpg",
                  "awayTeamScore": {
                        "score": "196",
                        "wickets": "6",
                        "over": "20"
                  }
            }
      ]
}
```
{% endswagger-response %}
{% endswagger %}
