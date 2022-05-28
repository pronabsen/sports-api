# Get Match Squad

&#x20;**Get Squad by Match ID API**

{% swagger method="get" path="match_squad" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Match Squad API" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="auth-key" required="true" %}
\{{ your-auth-key }}
{% endswagger-parameter %}

{% swagger-parameter in="header" name="secret-key" required="true" %}
\{{ your-secret-key }}
{% endswagger-parameter %}

{% swagger-parameter in="query" name="match_id" %}
\{{ match_id }}
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
      "status": true,
      "msg": "Data found.",
      "data": {
            "homeTeam": {
                  "name": "Bangladesh",
                  "code": "BAN",
                  "logo": "http://127.0.0.1:8000/storage/team/flag/BAN.jpg",
                  "players": [
                        {
                              "player_id": "2133",
                              "name": "Khaled Ahmed",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2133.jpg"
                        },
                        {
                              "player_id": "2077",
                              "name": "Liton Das",
                              "play_role": "WK-Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2077.jpg"
                        },
                        {
                              "player_id": "2076",
                              "name": "Mahmudul Hasan Joy",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2076.jpg"
                        },
                        {
                              "player_id": "2359",
                              "name": "Mominul Haque(c)",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2359.jpg"
                        },
                        {
                              "player_id": "2141",
                              "name": "Mushfiqur Rahim",
                              "play_role": "WK-Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2141.jpg"
                        },
                        {
                              "player_id": "2123",
                              "name": "Najmul Hossain Shanto",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2123.jpg"
                        },
                        {
                              "player_id": "2358",
                              "name": "Nayeem Hasan",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2358.jpg"
                        },
                        {
                              "player_id": "2125",
                              "name": "Shakib Al Hasan",
                              "play_role": "Batting Allrounder",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2125.jpg"
                        },
                        {
                              "player_id": "2087",
                              "name": "Shoriful Islam",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2087.jpg"
                        },
                        {
                              "player_id": "3161",
                              "name": "Taijul Islam",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/3161.jpg"
                        },
                        {
                              "player_id": "2164",
                              "name": "Tamim Iqbal",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2164.jpg"
                        }
                  ]
            },
            "teamAway": {
                  "name": "Sri Lanka",
                  "code": "SL",
                  "logo": "http://127.0.0.1:8000/storage/team/flag/SL.jpg",
                  "players": [
                        {
                              "player_id": "2793",
                              "name": "Angelo Mathews",
                              "play_role": "Batting Allrounder ",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2793.jpg"
                        },
                        {
                              "player_id": "3239",
                              "name": "Asitha Fernando",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/3239.jpg"
                        },
                        {
                              "player_id": "3237",
                              "name": "Dhananjaya de Silva",
                              "play_role": "Batting Allrounder",
                              "logo": "http://127.0.0.1:8000/storage/team/player/3237.jpg"
                        },
                        {
                              "player_id": "2795",
                              "name": "Dimuth Karunaratne(c)",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2795.jpg"
                        },
                        {
                              "player_id": "2610",
                              "name": "Dinesh Chandimal",
                              "play_role": "WK-Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2610.jpg"
                        },
                        {
                              "player_id": "2685",
                              "name": "Kusal Mendis",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2685.jpg"
                        },
                        {
                              "player_id": "2791",
                              "name": "Lasith Embuldeniya",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2791.jpg"
                        },
                        {
                              "player_id": "2796",
                              "name": "Niroshan Dickwella",
                              "play_role": "WK-Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2796.jpg"
                        },
                        {
                              "player_id": "3236",
                              "name": "Oshada Fernando",
                              "play_role": "Batsman",
                              "logo": "http://127.0.0.1:8000/storage/team/player/3236.jpg"
                        },
                        {
                              "player_id": "3238",
                              "name": "Ramesh Mendis",
                              "play_role": "Bowling Allrounder",
                              "logo": "http://127.0.0.1:8000/storage/team/player/3238.jpg"
                        },
                        {
                              "player_id": "2797",
                              "name": "Vishwa Fernando",
                              "play_role": "Bowler",
                              "logo": "http://127.0.0.1:8000/storage/team/player/2797.jpg"
                        }
                  ]
            }
      }
}
```
{% endswagger-response %}
{% endswagger %}

{% tabs %}
{% tab title="Request" %}
```
https://sports-api.xyz/api/cricket/v1/match_squad?match_id=1301
```
{% endtab %}
{% endtabs %}
