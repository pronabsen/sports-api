# Get All Series

&#x20;**Get all series API**

{% swagger method="get" path="series" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Series API" %}
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
                  "series_id": 98,
                  "series_name": "Indian Premier League 2022",
                  "season": "26 Mar - 29 May 2022",
                  "status": "Live",
                  "total_matches": 74,
                  "start_date": "2022-03-26",
                  "end_date": "2022-05-29"
            },
            {
                  "series_id": 118,
                  "series_name": "Womens T20 Challenge 2022",
                  "season": "23 May - 28 May 2022",
                  "status": "Finished",
                  "total_matches": 4,
                  "start_date": "2022-05-23",
                  "end_date": "2022-05-28"
            }
      ]
}
```
{% endswagger-response %}
{% endswagger %}

{% tabs %}
{% tab title="Request" %}
```
https://sports-api.xyz/api/cricket/v1/series
```
{% endtab %}
{% endtabs %}
