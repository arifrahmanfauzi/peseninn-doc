---
description: Berisi semua menu item dari semua cafe
---

# All Menu Item

{% api-method method="get" host="https://api.peseninn.com" path="/api/menu-item" %}
{% api-method-summary %}
List All Menu Item
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Content-Tyoe" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="Accept" type="string" required=false %}
application/json
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{
    "success": true,
    "message": "data berhasil ke view",
    "data": [
        {
            "id": 1,
            "menu_name": "Salad Jowo",
            "description": "salad",
            "image_url": null,
            "price": 8000,
            "category_id": 1,
            "cafe_name": "45 coffe",
            "address": "sukodono",
            "deleted_at": null,
            "img_logo": null
        },
        {
            "id": 2,
            "menu_name": "Kentang Goreng",
            "description": "makanan",
            "image_url": "https://peseninn.test/images/1605590126.jpeg",
            "price": 7000,
            "category_id": 1,
            "cafe_name": "crema coffe",
            "address": "jemursari",
            "deleted_at": null,
            "img_logo": null
        },
    ]
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

