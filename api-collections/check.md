# Check

**Check API**

## Check API

<mark style="color:blue;">`GET`</mark> `https://sports-api.xyz/api/cricket/v1/check`

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
      "msg": "Perfect! Your api working."
}
```
{% endtab %}
{% endtabs %}
