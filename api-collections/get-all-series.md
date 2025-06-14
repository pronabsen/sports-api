# Get All Series

**Get all series API**

## Series API

<mark style="color:blue;">`GET`</mark> `https://sports-api.xyz/api/cricket/v1/series`

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
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Request" %}
```
https://sports-api.xyz/api/cricket/v1/series
```
{% endtab %}
{% endtabs %}
