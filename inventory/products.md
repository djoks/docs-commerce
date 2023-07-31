---
description: This page allows you to explore and discover the diverse range of products.
---

# Products

This page allows you to explore and discover the diverse range of products on our E-Commerce platform. Here, you'll find various high-quality products from multiple categories, each carefully curated to cater to your unique preferences and needs.

{% swagger method="get" path="/products" baseUrl="" summary="Get all products" expanded="true" %}
{% swagger-description %}
This endpoint returns an array of products that are available within the system.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Success" %}


```json
{
    "data": [
        {
            "id": 4,
            "name": "Aperiam molestiae nobis.",
            "slug": "aperiam-molestiae-nobis",
            "category": {
                "name": "Electronics",
                "slug": "electronics"
            },
            "price": 471.77,
            "quantity": 107,
            "barcode": "6847687495477",
            "notes": "Ut quo provident voluptatem quia accusantium. Iure quo minima ut nostrum assumenda harum. Laudantium esse est maiores deleniti ut.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 31,
            "name": "Asperiores aut.",
            "slug": "asperiores-aut",
            "category": {
                "name": "Furniture",
                "slug": "furniture"
            },
            "price": 867.1,
            "quantity": 0,
            "barcode": "3044463718383",
            "notes": "In corporis alias commodi in. Tempora expedita non magnam adipisci nesciunt assumenda minus ullam. Facere voluptate architecto id id ut ut at. Nulla perferendis amet error molestiae deleniti sint.",
            "photo": null,
            "status": "Out Of Stock"
        },
        {
            "id": 64,
            "name": "Asperiores qui dolorem.",
            "slug": "asperiores-qui-dolorem",
            "category": {
                "name": "Pet Supplies",
                "slug": "pet-supplies"
            },
            "price": 231.66,
            "quantity": 0,
            "barcode": "8192918495336",
            "notes": "Velit et beatae quo ex sit laboriosam. Consequatur molestiae laborum numquam fuga eligendi tenetur. Dolores rerum dolore deleniti dolores.",
            "photo": null,
            "status": "Out Of Stock"
        },
        {
            "id": 68,
            "name": "Asperiores vero.",
            "slug": "asperiores-vero",
            "category": {
                "name": "Clothing",
                "slug": "clothing"
            },
            "price": 9.64,
            "quantity": 0,
            "barcode": "2856105328529",
            "notes": "White Rabbit blew three blasts on the song, 'I'd have said to the Knave 'Turn them over!' The Knave did so, very carefully, remarking, 'I really must be growing small again.' She got up and to.",
            "photo": null,
            "status": "Out Of Stock"
        },
        {
            "id": 60,
            "name": "Aut corporis.",
            "slug": "aut-corporis",
            "category": {
                "name": "Automotive Parts",
                "slug": "automotive-parts"
            },
            "price": 964.03,
            "quantity": 968,
            "barcode": "8353238326407",
            "notes": "Rerum repellendus totam placeat consequatur suscipit velit est. Omnis atque ad omnis voluptatem. Ducimus odit voluptatem est inventore occaecati quod.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 13,
            "name": "Aut eveniet.",
            "slug": "aut-eveniet",
            "category": {
                "name": "Home Appliances",
                "slug": "home-appliances"
            },
            "price": 116.39,
            "quantity": 1098,
            "barcode": "0366690331146",
            "notes": "Eaque quia quo vitae velit veniam et voluptatibus non. Et unde expedita est est a repellat. Est inventore voluptatem nobis tempora. Voluptates sequi rerum et.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 10,
            "name": "Aut non modi.",
            "slug": "aut-non-modi",
            "category": {
                "name": "Home Appliances",
                "slug": "home-appliances"
            },
            "price": 856.95,
            "quantity": 1754,
            "barcode": "0300929981351",
            "notes": "Natus corrupti consequatur id qui omnis odit. Voluptates et enim vero nam omnis omnis id. Doloremque quos dolorem aut beatae ut quia molestias quod.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 35,
            "name": "Blanditiis aliquid.",
            "slug": "blanditiis-aliquid",
            "category": {
                "name": "Toys",
                "slug": "toys"
            },
            "price": 379.85,
            "quantity": 0,
            "barcode": "9240204799817",
            "notes": "Et deleniti perferendis velit temporibus molestiae eligendi nisi. Fugiat odit accusantium reprehenderit nihil rerum quo dicta ut. Et dolores sed cupiditate.",
            "photo": null,
            "status": "Out Of Stock"
        },
        {
            "id": 12,
            "name": "Consectetur repudiandae.",
            "slug": "consectetur-repudiandae",
            "category": {
                "name": "Home Appliances",
                "slug": "home-appliances"
            },
            "price": 122.75,
            "quantity": 2357,
            "barcode": "6214460971914",
            "notes": "Repellat sint quia consectetur enim sit. Expedita qui explicabo possimus omnis veritatis. Expedita et consequuntur eum sequi illo ullam. Reiciendis quam voluptatem sunt facere nulla.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 6,
            "name": "Consequatur a voluptas.",
            "slug": "consequatur-a-voluptas",
            "category": {
                "name": "Electronics",
                "slug": "electronics"
            },
            "price": 177.38,
            "quantity": 1377,
            "barcode": "2526631302644",
            "notes": "Et incidunt quae commodi. Voluptatem at facilis unde et saepe. Ipsum at pariatur atque minus et laborum. Veritatis odio temporibus blanditiis deserunt voluptate. Vero distinctio doloribus eos hic beatae.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 8,
            "name": "Corporis in.",
            "slug": "corporis-in",
            "category": {
                "name": "Clothing",
                "slug": "clothing"
            },
            "price": 994.22,
            "quantity": 1906,
            "barcode": "1085081194656",
            "notes": "Ut sint doloribus necessitatibus earum maiores dolor. Laudantium temporibus rerum placeat quos. Quidem ut consequatur earum quasi quam.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 20,
            "name": "Corporis vel ut.",
            "slug": "corporis-vel-ut",
            "category": {
                "name": "Books",
                "slug": "books"
            },
            "price": 545.2,
            "quantity": 0,
            "barcode": "6027883024125",
            "notes": "Quis dolore laboriosam eum in incidunt cupiditate. Voluptas voluptatem laboriosam est porro eaque porro. Distinctio id enim deleniti alias assumenda. Rem sunt voluptas consequatur ut aut provident.",
            "photo": null,
            "status": "Out Of Stock"
        },
        {
            "id": 55,
            "name": "Corrupti accusamus.",
            "slug": "corrupti-accusamus",
            "category": {
                "name": "Automotive Parts",
                "slug": "automotive-parts"
            },
            "price": 674.31,
            "quantity": 2072,
            "barcode": "1010267683037",
            "notes": "Amet error eum minima ullam quia omnis. At autem maxime laboriosam reprehenderit. Quasi rem iure placeat consequatur est voluptatem. Culpa magni quae iure earum.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 29,
            "name": "Cum doloremque qui.",
            "slug": "cum-doloremque-qui",
            "category": {
                "name": "Furniture",
                "slug": "furniture"
            },
            "price": 270.7,
            "quantity": 883,
            "barcode": "7659388635088",
            "notes": "Magni rerum labore expedita magni illum in possimus quis. Ut et omnis aut. Id dolore ipsum molestiae. Labore asperiores delectus aspernatur ipsa vitae et. Placeat laudantium sit quibusdam et ut quis.",
            "photo": null,
            "status": "Available"
        },
        {
            "id": 7,
            "name": "Delectus dolor corporis.",
            "slug": "delectus-dolor-corporis",
            "category": {
                "name": "Electronics",
                "slug": "electronics"
            },
            "price": 472.88,
            "quantity": 0,
            "barcode": "8677006635622",
            "notes": "Autem deserunt dignissimos reprehenderit incidunt architecto rerum. Provident eos atque ratione eligendi exercitationem. Et incidunt aut aut laborum.",
            "photo": null,
            "status": "Out Of Stock"
        }
    ],
    "links": {
        "first": "http://commerce.test/api/v1/products?page=1",
        "last": "http://commerce.test/api/v1/products?page=5",
        "prev": null,
        "next": "http://commerce.test/api/v1/products?page=2"
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 5,
        "links": [
            {
                "url": null,
                "label": "&laquo; Previous",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/products?page=1",
                "label": "1",
                "active": true
            },
            {
                "url": "http://commerce.test/api/v1/products?page=2",
                "label": "2",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/products?page=3",
                "label": "3",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/products?page=4",
                "label": "4",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/products?page=5",
                "label": "5",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/products?page=2",
                "label": "Next &raquo;",
                "active": false
            }
        ],
        "path": "http://commerce.test/api/v1/products",
        "per_page": 15,
        "to": 15,
        "total": 68
    }
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/products/:id" baseUrl="" summary="Get a single product" expanded="true" %}
{% swagger-description %}
This endpoint returns a single product object based on the id passed as a path parameter.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Success" %}


```php
{
    "id": 4,
    "name": "Aperiam molestiae nobis.",
    "slug": "aperiam-molestiae-nobis",
    "category": {
        "name": "Electronics",
        "slug": "electronics"
    },
    "price": 471.77,
    "quantity": 107,
    "barcode": "6847687495477",
    "notes": "Ut quo provident voluptatem quia accusantium. Iure quo minima ut nostrum assumenda harum. Laudantium esse est maiores deleniti ut.",
    "photo": null,
    "status": "Available"
}
```
{% endswagger-response %}
{% endswagger %}
