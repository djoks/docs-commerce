---
description: >-
  The Billing page manages the billing accounts for a registered user and also
  displays available payment options.
---

# Billing

This page handles all aspects of billing and payments for our E-Commerce API. Whether you need to view a list of all billing accounts, retrieve details for a specific account, or view available payment options.

{% swagger method="get" path="/billings" baseUrl="" summary="Get all billing addresses" expanded="true" %}
{% swagger-description %}
This endpoint returns an array of billing addresses created by the user.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Success" %}


```json
{
    "data": [
        {
            "id": 3,
            "first_name": "Lewis",
            "last_name": "Bahringer",
            "street_address": "92637 Kristoffer Glens",
            "city": "Odieport",
            "state": "New Jersey",
            "country": "Ghana",
            "is_default": 0
        },
        {
            "id": 1,
            "first_name": "Nova",
            "last_name": "Abernathy",
            "street_address": "128 Nitzsche Port Apt. 018",
            "city": "Maybelleton",
            "state": "Alaska",
            "country": "Ghana",
            "is_default": 0
        },
        {
            "id": 2,
            "first_name": "Lysanne",
            "last_name": "Doyle",
            "street_address": "923 Destiney Turnpike",
            "city": "Naderview",
            "state": "Michigan",
            "country": "Ghana",
            "is_default": 0
        }
    ],
    "links": {
        "first": "http://commerce.test/api/v1/billing?page=1",
        "last": "http://commerce.test/api/v1/billing?page=1",
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
                "url": "http://commerce.test/api/v1/billing?page=1",
                "label": "1",
                "active": true
            },
            {
                "url": null,
                "label": "Next &raquo;",
                "active": false
            }
        ],
        "path": "http://commerce.test/api/v1/billing",
        "per_page": 15,
        "to": 3,
        "total": 3
    }
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/billings/:id" baseUrl="" summary="Get one billing address" expanded="true" %}
{% swagger-description %}
This endpoint returns details for a single billing address using the id passed as a path parameter.
{% endswagger-description %}

{% swagger-parameter in="path" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Success" %}


```php
{
    "id": 3,
    "first_name": "Lewis",
    "last_name": "Bahringer",
    "street_address": "92637 Kristoffer Glens",
    "city": "Odieport",
    "state": "New Jersey",
    "country": "Ghana",
    "is_default": 0
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/billings" baseUrl="" summary="Add billing address" expanded="true" %}
{% swagger-description %}
This endpoint creates a new billing address based on the parameters passed within the body.
{% endswagger-description %}

{% swagger-parameter in="body" name="payment_type_id" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="first_name" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="last_name" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="street_address" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="city" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="state" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="country" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="is_default" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}


```json
{
    "message": "Billing created",
    "data": {
        "id": 6,
        "first_name": "Jon",
        "last_name": "Jonz",
        "street_address": "jonjonz@example.com",
        "city": "Accra",
        "state": "New York",
        "country": "USA",
        "is_default": 0
    }
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/payment/types" baseUrl="" summary="Get payment types" %}
{% swagger-description %}
This endpoint returns a list of all available payment types.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Success" %}


```json
{
    "data": [
        {
            "id": 2,
            "name": "Master"
        },
        {
            "id": 3,
            "name": "Mobile Money"
        },
        {
            "id": 4,
            "name": "Paypal"
        },
        {
            "id": 1,
            "name": "Visa"
        }
    ],
    "links": {
        "first": "http://commerce.test/api/v1/payment-types?page=1",
        "last": "http://commerce.test/api/v1/payment-types?page=1",
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
                "url": "http://commerce.test/api/v1/payment-types?page=1",
                "label": "1",
                "active": true
            },
            {
                "url": null,
                "label": "Next &raquo;",
                "active": false
            }
        ],
        "path": "http://commerce.test/api/v1/payment-types",
        "per_page": 15,
        "to": 4,
        "total": 4
    }
}
```
{% endswagger-response %}
{% endswagger %}

