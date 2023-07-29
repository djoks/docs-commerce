---
description: >-
  The Authentication page manages user access and security, offering
  registration, login, OTP verification, and logout methods for our E-Commerce
  API.
---

# Authentication

This page manages user authentication and security for our E-Commerce API. As a critical component of any online application, authentication ensures that only authorized users can access specific features and data. Here, you'll find four essential methods: **Register**, **Login**, **Verify OTP**, and **Logout**, each serving a particular purpose in the authentication process. Understanding and utilizing these methods correctly will help you build a secure and user-friendly customer experience.



{% swagger method="get" path="/auth/register" baseUrl="" summary="Create new account" expanded="true" %}
{% swagger-description %}
This endpoint allows you to create a new user account based on the parameters supplied.
{% endswagger-description %}

{% swagger-parameter in="body" name="phone" required="true" %}
A valid phone number.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="email" required="true" %}
A valid email address.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="password" required="true" %}
A mix of alphanumeric characters not less than six characters long.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="password_confirmation" required="true" %}
A repeat of the password field.
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Success" %}


```json
{
    "message": "Your account has been created successfully.",
    "data": {
        "user": {
            "id": 40,
            "email": "email@example.com",
            "phone": "+233263257625",
            "is_active": null,
            "roles": [
                "customer"
            ]
        }
    }
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/auth/login" baseUrl="" summary="Account login" %}
{% swagger-description %}
This endpoint allows you to log in to an existing account using a registered email and password combination.
{% endswagger-description %}

{% swagger-parameter in="body" name="email" required="true" %}
Registered email address of user.
{% endswagger-parameter %}

{% swagger-parameter in="body" name="password" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Success" %}


```json
{
    "message": "Login success",
    "data": {
        "token": "2|fmYONPS7tA1sP70DI7Jzd7v78cyz41tlK9G6S7pC",
        "user": {
            "id": 38,
            "email": "email@example.com",
            "phone": "+233263257625",
            "is_active": true,
            "roles": [
                "customer"
            ]
        }
    }
}
```
{% endswagger-response %}
{% endswagger %}
