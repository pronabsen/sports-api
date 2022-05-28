# Check

&#x20;**Check API**

{% swagger method="get" path="check" baseUrl="https://sports-api.xyz/api/cricket/v1/" summary="Check API" %}
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
      "msg": "Perfect! Your api working."
}
```
{% endswagger-response %}
{% endswagger %}
