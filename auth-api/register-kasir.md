---
description: Pendaftaran user untuk role kasir
---

# Register Kasir

{% api-method method="post" host="https://api.peseninn.com" path="/api/register" %}
{% api-method-summary %}
Register
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="password\_confirmation" type="string" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="password" type="string" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="email" type="string" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="name" type="string" required=true %}

{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{
    "success": true,
    "message": "Register Success!",
    "user": {
        "name": "test",
        "email": "test@gmail.com",
        "uuid": 35,
        "updated_at": "2021-04-26T23:18:46.000000Z",
        "created_at": "2021-04-26T23:18:46.000000Z"
    }
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

