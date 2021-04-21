---
description: login via mobile
---

# Login Mobile

{% api-method method="post" host="https://api.peseninn.com/api" path="/login/guest" %}
{% api-method-summary %}
Login via Mobile
{% endapi-method-summary %}

{% api-method-description %}
untuk login mobile, uuid sudah ada
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="uuid" type="string" required=false %}
uui di dapat dari verifikasi
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{
    "success": true
    "token": "xaa113seq"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

