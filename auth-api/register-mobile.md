---
description: End-Point ini untuk registrasi pengguna  dari sisi mobile
---

# Register Mobile

{% api-method method="post" host="https://api.peseninn.com/api" path="/register/guest" %}
{% api-method-summary %}
Register Mobile
{% endapi-method-summary %}

{% api-method-description %}
Register User via mobile  
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="uuid" type="string" required=true %}
uuid didapat setelah diverifikasi
{% endapi-method-parameter %}

{% api-method-parameter name="phone" type="string" required=true %}
nomor telepon yang telah diverifikasi
{% endapi-method-parameter %}

{% api-method-parameter name="name" type="string" required=true %}
nama pengguna
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
    "user": {
        "uuid": 35,
        "name": "hiro",
        "phone_number": "087851394079",
        "device_token": null,
        "updated_at": "2021-04-19T13:20:57.000000Z",
        "created_at": "2021-04-19T13:20:57.000000Z"
    }
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



