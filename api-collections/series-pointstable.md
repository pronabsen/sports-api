# Series PointsTable

&#x20;**Get Series PointsTable API**

{% swagger method="get" path="series_pointstable" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Series API" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="auth-key" required="true" %}
\{{ your-auth-key }}
{% endswagger-parameter %}

{% swagger-parameter in="header" name="secret-key" required="true" %}
\{{ your-secret-key }}
{% endswagger-parameter %}

{% swagger-parameter in="query" name="series_id" %}
\{{ series_id }}
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
      "status": true,
      "msg": "Data found.",
      "data": [
            {
                  "teams_name": "Gujarat Titans",
                  "points": "14",
                  "matchWin": "10",
                  "matchLoss": "4",
                  "netRun ": "0",
                  "Pts ": "20",
                  "netRunRate ": "+0.316"
            },
            {
                  "teams_name": "Rajasthan Royals",
                  "points": "14",
                  "matchWin": "9",
                  "matchLoss": "5",
                  "netRun ": "0",
                  "Pts ": "18",
                  "netRunRate ": "+0.298"
            },
            {
                  "teams_name": "Lucknow Super Giants",
                  "points": "14",
                  "matchWin": "9",
                  "matchLoss": "5",
                  "netRun ": "0",
                  "Pts ": "18",
                  "netRunRate ": "+0.251"
            },
            {
                  "teams_name": "Royal Challengers Bangalore",
                  "points": "14",
                  "matchWin": "8",
                  "matchLoss": "6",
                  "netRun ": "0",
                  "Pts ": "16",
                  "netRunRate ": "-0.253"
            },
            {
                  "teams_name": "Delhi Capitals ",
                  "points": "14",
                  "matchWin": "7",
                  "matchLoss": "7",
                  "netRun ": "0",
                  "Pts ": "14",
                  "netRunRate ": "+0.204"
            },
            {
                  "teams_name": "Punjab Kings",
                  "points": "14",
                  "matchWin": "7",
                  "matchLoss": "7",
                  "netRun ": "0",
                  "Pts ": "14",
                  "netRunRate ": "+0.126"
            },
            {
                  "teams_name": "Kolkata Knight Riders",
                  "points": "14",
                  "matchWin": "6",
                  "matchLoss": "8",
                  "netRun ": "0",
                  "Pts ": "12",
                  "netRunRate ": "+0.146"
            },
            {
                  "teams_name": "Sunrisers Hyderabad",
                  "points": "14",
                  "matchWin": "6",
                  "matchLoss": "8",
                  "netRun ": "0",
                  "Pts ": "12",
                  "netRunRate ": "-0.379"
            },
            {
                  "teams_name": "Chennai Super Kings",
                  "points": "14",
                  "matchWin": "4",
                  "matchLoss": "10",
                  "netRun ": "0",
                  "Pts ": "8",
                  "netRunRate ": "-0.203"
            },
            {
                  "teams_name": "Mumbai Indians",
                  "points": "14",
                  "matchWin": "4",
                  "matchLoss": "10",
                  "netRun ": "0",
                  "Pts ": "8",
                  "netRunRate ": "-0.506"
            }
      ]
}
```
{% endswagger-response %}
{% endswagger %}

{% tabs %}
{% tab title="Request" %}
```
https://sports-api.xyz/api/cricket/v1/series_pointstable?series_id=98
```
{% endtab %}
{% endtabs %}
