---
description: Untuk login ke dalam dashboard kasir
---

# Login Kasir

{% api-method method="post" host="https://api.peseninn.com" path="/api/login" %}
{% api-method-summary %}
Login
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="" type="string" required=true %}
kebersamaan@
{% endapi-method-parameter %}

{% api-method-parameter name="email" type="string" required=true %}
test@gmail.com
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
    "message": "Login Success!",
    "data": {
        "id": 30,
        "uuid": 0,
        "name": "arif",
        "role_id": null,
        "email": "test@gmail.com",
        "phone_number": null,
        "email_verified_at": null,
        "token": null,
        "device_token": null,
        "created_at": "2021-01-28T09:31:48.000000Z",
        "updated_at": "2021-01-28T09:31:48.000000Z"
    },
    "token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJhdWQiOiI5Mjk5YmZiZi05ZmU2LTQzYTItYTQzYi1hNWUxZTUwMjkxMGUiLCJqdGkiOiIyYzM4YWIxMzE5NjU2ZTQ1ZmI2YmExNGFhZWM1ZDJlZTAzZmQ1NDdmMzFjNDYxYzU4YjA0MjkyYWVkZmJmZjI0MjkzM2RlNzBlYmNjZDNiNCIsImlhdCI6IjE2MTk0Nzc3MzkuNDc5OTk4IiwibmJmIjoiMTYxOTQ3NzczOS40ODAwMDIiLCJleHAiOiIxNjI3MzQwMTM5LjMxMTI0MCIsInN1YiI6IjAiLCJzY29wZXMiOltdfQ.crbcAUef5rYM4GBOZ4zE01XaJvfB529Y0fi30trubGBN1LqXMUmPbbL5D6lgnBO-ylOlAoii58Vxkus2jBrggSetrTXot659IRKMRUwieYFdNcEHQXmN5-pE63A6UjGgeCEQgD8mTU0TSdBz4a3rhvVGksJhjW6zEE9o1OYk2OfHvTcauQr6Yks4tGyX4w37RD0K3YSxxoq8U0pZsvS1adGyDMgad3fSH80v56kRt2Hgeky0ceQz72yrqKV0sZsL8D75zw2_cLhPswnMImxIJ6VVtOnSXMQCzZ_i4ou-R_c4Bgrjo3KjfGByksc6cj87RUAiJY6-IVMeOdUbzfXQ_cKSHrxPCY-9pFn8wxC9pI9dq4a3HQsWZSAUx-Uf7Hw8D3h57quQ3B5nQn3jFuYvkVkAQQE8YcGxuHsGywIA7KJXLg-EzkWpqZn_TZOwAGU-S_YF852xHkRf4f7jaJxJDmq9KTENbJERJ0Yy4_0G95tk5eZTjBN5abZcgqNytECaw-GFOYN2GcFU2N4zwwZVDS-Qj01QhdMl4rPoLFLQTbuFTCYYqg3zQYGFDZDM6NDN7kGN7bX1Jo-NShoDSs0kxVXEhVoPOvLCJbDbBz2YQxu0ldshLE8nW_Win0Sm1L5qAdast42njjzkNP6EUcOKUDE3zbPHASlpxBlERl4loV0"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

