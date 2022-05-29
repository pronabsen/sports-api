# 🎆 Quick Start

Before you are able to use our API services you need a Sport-API account. [Register now.](https://sports-api.xyz/register)

To make our first request, we’ll need to authenticate first. Our Sport-API has Cricket API Version 1.0 utilizes API Auth & App Secret Key for the authentication of requests. You can obtain and manage your API Auth & App Secret Key in [SPORTS-API](https://sports-api.xyz/login).

**Example API Auth Key: \[HdoiD312ND….]**

**Example API Secret Key: \[HdoiD312ND….]**

Sport-API (Cricket API) Version 1.0 utilizes response codes to indicate successful and failed API requests.

{% hint style="info" %}
We recommend you use Postman for convenience. Every endpoint has an example request ready to be requested by you. Hit the button below to import our Cricket API collection.\
[​![](https://run.pstmn.io/button.svg)​](https://documenter.getpostman.com/view/13066863/Uz5CLdUZ)​
{% endhint %}

## Build your first Request

The best way to interact with our API is to use one of our official libraries:

{% tabs %}
{% tab title="Base URL" %}
```
https://sports-api.xyz/api/cricket/v1/
```
{% endtab %}
{% endtabs %}

## Check your API

To make your first request, send an authenticated request to the pets endpoint. This will create a `pet`, which is nice.

{% swagger baseUrl="https://sports-api.xyz/api/cricket/v1/check" method="get" path="" summary="Create GET request and Check your API ." %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="auth-key" required="true" %}
\{{ your-auth-key }}
{% endswagger-parameter %}

{% swagger-parameter in="header" name="secret-key" required="true" %}
\{{ your-secret-key }}
{% endswagger-parameter %}

{% swagger-response status="200" description="Perfectly Working" %}
```javascript
{
    "name"="Wilson",
    "owner": {
        "id": "sha7891bikojbkreuy",
        "name": "Samuel Passet",
    "species": "Dog",}
    "breed": "Golden Retriever",
}
```
{% endswagger-response %}

{% swagger-response status="401: Unauthorized" description="Permission denied" %}

{% endswagger-response %}
{% endswagger %}
