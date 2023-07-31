---
description: The Categories page displays a list of all available product categories.
---

# Categories

The Categories page displays a list of all available product categories.  Product categories group similar products together making it easy to find or browse items.

{% swagger method="get" path="/categories" baseUrl="" summary="Get all categories" expanded="true" %}
{% swagger-description %}
This endpoint returns an array of categories available in the system.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Success" %}


```json
{
    "data": [
        {
            "name": "Automotive Parts",
            "slug": "automotive-parts"
        },
        {
            "name": "Beauty Products",
            "slug": "beauty-products"
        },
        {
            "name": "Books",
            "slug": "books"
        },
        {
            "name": "Clothing",
            "slug": "clothing"
        },
        {
            "name": "Electronics",
            "slug": "electronics"
        },
        {
            "name": "Furniture",
            "slug": "furniture"
        },
        {
            "name": "Home Appliances",
            "slug": "home-appliances"
        },
        {
            "name": "Pet Supplies",
            "slug": "pet-supplies"
        },
        {
            "name": "Sports Equipment",
            "slug": "sports-equipment"
        },
        {
            "name": "Test",
            "slug": "test"
        },
        {
            "name": "Toys",
            "slug": "toys"
        }
    ],
    "links": {
        "first": "http://commerce.test/api/v1/categories?page=1",
        "last": "http://commerce.test/api/v1/categories?page=1",
        "prev": null,
        "next": null
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 1,
        "links": [
            {
                "url": null,
                "label": "&laquo; Previous",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/categories?page=1",
                "label": "1",
                "active": true
            },
            {
                "url": null,
                "label": "Next &raquo;",
                "active": false
            }
        ],
        "path": "http://commerce.test/api/v1/categories",
        "per_page": 15,
        "to": 11,
        "total": 11
    }
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger expanded="true" method="get" path="/categories/:id" baseUrl="" summary="Get one category" %}
{% swagger-description %}
This endpoint returns a single category object available in the system.
{% endswagger-description %}

{% swagger-parameter in="path" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Success" %}


```php
{
    "name": "Books",
    "slug": "books"
}
```
{% endswagger-response %}
{% endswagger %}
