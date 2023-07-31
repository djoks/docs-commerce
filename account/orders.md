---
description: The Orders page displays all orders made by a particular user.
---

# Orders

This page is designed exclusively for providing a hassle-free way to view and track your orders. We prioritize transparency and convenience, ensuring you have complete visibility into your purchase history and shipment status.

{% swagger expanded="true" method="get" path="/orders" baseUrl="" summary="Get all orders" %}
{% swagger-description %}
This endpoint returns an array of all completed orders by the user.
{% endswagger-description %}

{% swagger-response status="200: OK" description="Success" %}




```json
{
    "data": [
        {
            "id": 81,
            "code": "INV-2023-0081",
            "sub_total": 26133747,
            "tax": 5723291,
            "discount": 28877,
            "total": 31828161,
            "items": [
                {
                    "id": 444,
                    "product": {
                        "id": 38,
                        "name": "Pariatur rerum maxime."
                    },
                    "price": 32479
                },
                {
                    "id": 445,
                    "product": {
                        "id": 11,
                        "name": "Velit error."
                    },
                    "price": 54418
                },
                {
                    "id": 446,
                    "product": {
                        "id": 29,
                        "name": "Cum doloremque qui."
                    },
                    "price": 27070
                },
                {
                    "id": 447,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 448,
                    "product": {
                        "id": 2,
                        "name": "Voluptas veniam."
                    },
                    "price": 97736
                },
                {
                    "id": 449,
                    "product": {
                        "id": 30,
                        "name": "Dolorem veniam."
                    },
                    "price": 50289
                },
                {
                    "id": 450,
                    "product": {
                        "id": 55,
                        "name": "Corrupti accusamus."
                    },
                    "price": 67431
                },
                {
                    "id": 451,
                    "product": {
                        "id": 1,
                        "name": "Suscipit qui."
                    },
                    "price": 9512
                },
                {
                    "id": 452,
                    "product": {
                        "id": 17,
                        "name": "Quo totam."
                    },
                    "price": 37156
                },
                {
                    "id": 453,
                    "product": {
                        "id": 19,
                        "name": "Vero assumenda accusantium."
                    },
                    "price": 81854
                }
            ],
            "billing": null,
            "payment": {
                "id": 81,
                "order_id": 81,
                "reference": "RCTE4WM0UVQE",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-20T00:55:19.000000Z",
                "updated_at": "2023-07-20T00:55:19.000000Z"
            },
            "shipping": {
                "city": "West Earlineview",
                "state": "Missouri",
                "country": "Tuvalu",
                "last_name": "Gleichner",
                "first_name": "Evangeline",
                "street_address": "53020 Freddie Viaduct"
            },
            "meta": null
        },
        {
            "id": 54,
            "code": "INV-2023-0054",
            "sub_total": 17540104,
            "tax": 3841283,
            "discount": 0,
            "total": 21381387,
            "items": [
                {
                    "id": 309,
                    "product": {
                        "id": 50,
                        "name": "Sunt sit exercitationem."
                    },
                    "price": 91982
                },
                {
                    "id": 310,
                    "product": {
                        "id": 24,
                        "name": "Et nesciunt."
                    },
                    "price": 55660
                },
                {
                    "id": 311,
                    "product": {
                        "id": 17,
                        "name": "Quo totam."
                    },
                    "price": 37156
                }
            ],
            "billing": null,
            "payment": {
                "id": 54,
                "order_id": 54,
                "reference": "Y78G0VKDZ4IV",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-19T14:32:42.000000Z",
                "updated_at": "2023-07-19T14:32:42.000000Z"
            },
            "shipping": {
                "city": "Kuhnview",
                "state": "Virginia",
                "country": "Afghanistan",
                "last_name": "Langosh",
                "first_name": "Barton",
                "street_address": "6875 Beryl Mountains Apt. 056"
            },
            "meta": null
        },
        {
            "id": 105,
            "code": "INV-2023-0105",
            "sub_total": 34657142,
            "tax": 7589914,
            "discount": 29520,
            "total": 42217536,
            "items": [
                {
                    "id": 603,
                    "product": {
                        "id": 58,
                        "name": "Et et."
                    },
                    "price": 94242
                },
                {
                    "id": 604,
                    "product": {
                        "id": 38,
                        "name": "Pariatur rerum maxime."
                    },
                    "price": 32479
                },
                {
                    "id": 605,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 606,
                    "product": {
                        "id": 56,
                        "name": "Velit minima."
                    },
                    "price": 92748
                },
                {
                    "id": 607,
                    "product": {
                        "id": 23,
                        "name": "Harum odit."
                    },
                    "price": 14393
                },
                {
                    "id": 608,
                    "product": {
                        "id": 50,
                        "name": "Sunt sit exercitationem."
                    },
                    "price": 91982
                },
                {
                    "id": 609,
                    "product": {
                        "id": 30,
                        "name": "Dolorem veniam."
                    },
                    "price": 50289
                },
                {
                    "id": 610,
                    "product": {
                        "id": 40,
                        "name": "Voluptas molestiae."
                    },
                    "price": 53446
                },
                {
                    "id": 611,
                    "product": {
                        "id": 58,
                        "name": "Et et."
                    },
                    "price": 94242
                }
            ],
            "billing": null,
            "payment": {
                "id": 105,
                "order_id": 105,
                "reference": "RFHEO5FFISDN",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-18T22:11:34.000000Z",
                "updated_at": "2023-07-18T22:11:34.000000Z"
            },
            "shipping": {
                "city": "Barrowsview",
                "state": "Oregon",
                "country": "Anguilla",
                "last_name": "Zulauf",
                "first_name": "Ryann",
                "street_address": "5871 Hermann Island Apt. 791"
            },
            "meta": null
        },
        {
            "id": 134,
            "code": "INV-2023-0134",
            "sub_total": 44088975,
            "tax": 9655486,
            "discount": 0,
            "total": 53744461,
            "items": [
                {
                    "id": 773,
                    "product": {
                        "id": 58,
                        "name": "Et et."
                    },
                    "price": 94242
                },
                {
                    "id": 774,
                    "product": {
                        "id": 19,
                        "name": "Vero assumenda accusantium."
                    },
                    "price": 81854
                },
                {
                    "id": 775,
                    "product": {
                        "id": 15,
                        "name": "Deserunt unde qui."
                    },
                    "price": 55543
                },
                {
                    "id": 776,
                    "product": {
                        "id": 40,
                        "name": "Voluptas molestiae."
                    },
                    "price": 53446
                }
            ],
            "billing": null,
            "payment": {
                "id": 134,
                "order_id": 134,
                "reference": "AAONL6QCVQMV",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-18T18:58:20.000000Z",
                "updated_at": "2023-07-18T18:58:20.000000Z"
            },
            "shipping": {
                "city": "Lake Dominic",
                "state": "Nevada",
                "country": "Latvia",
                "last_name": "Hirthe",
                "first_name": "Joaquin",
                "street_address": "8168 Ludwig Ranch"
            },
            "meta": null
        },
        {
            "id": 21,
            "code": "INV-2023-0021",
            "sub_total": 7560570,
            "tax": 1655765,
            "discount": 0,
            "total": 9216335,
            "items": [
                {
                    "id": 131,
                    "product": {
                        "id": 10,
                        "name": "Aut non modi."
                    },
                    "price": 85695
                },
                {
                    "id": 132,
                    "product": {
                        "id": 4,
                        "name": "Aperiam molestiae nobis."
                    },
                    "price": 47177
                },
                {
                    "id": 133,
                    "product": {
                        "id": 10,
                        "name": "Aut non modi."
                    },
                    "price": 85695
                },
                {
                    "id": 134,
                    "product": {
                        "id": 25,
                        "name": "Praesentium ut."
                    },
                    "price": 40534
                },
                {
                    "id": 135,
                    "product": {
                        "id": 10,
                        "name": "Aut non modi."
                    },
                    "price": 85695
                },
                {
                    "id": 136,
                    "product": {
                        "id": 26,
                        "name": "Libero sit occaecati."
                    },
                    "price": 40486
                },
                {
                    "id": 137,
                    "product": {
                        "id": 26,
                        "name": "Libero sit occaecati."
                    },
                    "price": 40486
                },
                {
                    "id": 138,
                    "product": {
                        "id": 6,
                        "name": "Consequatur a voluptas."
                    },
                    "price": 17738
                }
            ],
            "billing": null,
            "payment": {
                "id": 21,
                "order_id": 21,
                "reference": "HLZAWDSGGKGW",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-18T02:49:08.000000Z",
                "updated_at": "2023-07-18T02:49:08.000000Z"
            },
            "shipping": {
                "city": "West Lelahborough",
                "state": "Florida",
                "country": "Saint Kitts and Nevis",
                "last_name": "Fadel",
                "first_name": "Estel",
                "street_address": "207 Collier Manors Suite 045"
            },
            "meta": null
        },
        {
            "id": 111,
            "code": "INV-2023-0111",
            "sub_total": 35883939,
            "tax": 7858583,
            "discount": 0,
            "total": 43742522,
            "items": [
                {
                    "id": 637,
                    "product": {
                        "id": 33,
                        "name": "Et architecto."
                    },
                    "price": 74941
                },
                {
                    "id": 638,
                    "product": {
                        "id": 11,
                        "name": "Velit error."
                    },
                    "price": 54418
                }
            ],
            "billing": null,
            "payment": {
                "id": 111,
                "order_id": 111,
                "reference": "CWPXJSXUFFZQ",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-17T11:52:32.000000Z",
                "updated_at": "2023-07-17T11:52:32.000000Z"
            },
            "shipping": {
                "city": "Lake Dulcehaven",
                "state": "Idaho",
                "country": "Macedonia",
                "last_name": "Beer",
                "first_name": "Hailey",
                "street_address": "350 Quitzon Oval Apt. 958"
            },
            "meta": null
        },
        {
            "id": 199,
            "code": "INV-2023-0199",
            "sub_total": 66470754,
            "tax": 14557095,
            "discount": 5643,
            "total": 81022206,
            "items": [
                {
                    "id": 1159,
                    "product": {
                        "id": 33,
                        "name": "Et architecto."
                    },
                    "price": 74941
                },
                {
                    "id": 1160,
                    "product": {
                        "id": 26,
                        "name": "Libero sit occaecati."
                    },
                    "price": 40486
                },
                {
                    "id": 1161,
                    "product": {
                        "id": 58,
                        "name": "Et et."
                    },
                    "price": 94242
                },
                {
                    "id": 1162,
                    "product": {
                        "id": 8,
                        "name": "Corporis in."
                    },
                    "price": 99422
                },
                {
                    "id": 1163,
                    "product": {
                        "id": 19,
                        "name": "Vero assumenda accusantium."
                    },
                    "price": 81854
                },
                {
                    "id": 1164,
                    "product": {
                        "id": 10,
                        "name": "Aut non modi."
                    },
                    "price": 85695
                }
            ],
            "billing": null,
            "payment": {
                "id": 199,
                "order_id": 199,
                "reference": "CU6YVVC90ZID",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-17T00:42:39.000000Z",
                "updated_at": "2023-07-17T00:42:39.000000Z"
            },
            "shipping": {
                "city": "West Andreanneville",
                "state": "Wisconsin",
                "country": "Macao",
                "last_name": "Schiller",
                "first_name": "Moriah",
                "street_address": "5681 Auer Villages Apt. 781"
            },
            "meta": null
        },
        {
            "id": 17,
            "code": "INV-2023-0017",
            "sub_total": 5963082,
            "tax": 1305915,
            "discount": 44626,
            "total": 7224371,
            "items": [
                {
                    "id": 102,
                    "product": {
                        "id": 1,
                        "name": "Suscipit qui."
                    },
                    "price": 9512
                },
                {
                    "id": 103,
                    "product": {
                        "id": 28,
                        "name": "Eos quo consequatur."
                    },
                    "price": 83567
                },
                {
                    "id": 104,
                    "product": {
                        "id": 2,
                        "name": "Voluptas veniam."
                    },
                    "price": 97736
                },
                {
                    "id": 105,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 106,
                    "product": {
                        "id": 46,
                        "name": "Et doloribus adipisci."
                    },
                    "price": 49220
                },
                {
                    "id": 107,
                    "product": {
                        "id": 11,
                        "name": "Velit error."
                    },
                    "price": 54418
                }
            ],
            "billing": null,
            "payment": {
                "id": 17,
                "order_id": 17,
                "reference": "SSHPTUGOEWW3",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-16T22:32:38.000000Z",
                "updated_at": "2023-07-16T22:32:38.000000Z"
            },
            "shipping": {
                "city": "Stantonton",
                "state": "District of Columbia",
                "country": "Angola",
                "last_name": "Lockman",
                "first_name": "Zita",
                "street_address": "74821 Maya Estate Apt. 887"
            },
            "meta": null
        },
        {
            "id": 101,
            "code": "INV-2023-0101",
            "sub_total": 33469396,
            "tax": 7329798,
            "discount": 20284,
            "total": 40778910,
            "items": [
                {
                    "id": 579,
                    "product": {
                        "id": 28,
                        "name": "Eos quo consequatur."
                    },
                    "price": 83567
                },
                {
                    "id": 580,
                    "product": {
                        "id": 33,
                        "name": "Et architecto."
                    },
                    "price": 74941
                },
                {
                    "id": 581,
                    "product": {
                        "id": 29,
                        "name": "Cum doloremque qui."
                    },
                    "price": 27070
                },
                {
                    "id": 582,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 583,
                    "product": {
                        "id": 38,
                        "name": "Pariatur rerum maxime."
                    },
                    "price": 32479
                },
                {
                    "id": 584,
                    "product": {
                        "id": 25,
                        "name": "Praesentium ut."
                    },
                    "price": 40534
                },
                {
                    "id": 585,
                    "product": {
                        "id": 28,
                        "name": "Eos quo consequatur."
                    },
                    "price": 83567
                },
                {
                    "id": 586,
                    "product": {
                        "id": 30,
                        "name": "Dolorem veniam."
                    },
                    "price": 50289
                },
                {
                    "id": 587,
                    "product": {
                        "id": 52,
                        "name": "Fugiat minima dolorum."
                    },
                    "price": 57429
                }
            ],
            "billing": null,
            "payment": {
                "id": 101,
                "order_id": 101,
                "reference": "7TTDS8VP8F1B",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-16T07:16:41.000000Z",
                "updated_at": "2023-07-16T07:16:41.000000Z"
            },
            "shipping": {
                "city": "Janebury",
                "state": "Missouri",
                "country": "Turkey",
                "last_name": "Wehner",
                "first_name": "Yessenia",
                "street_address": "738 Valerie Islands Apt. 379"
            },
            "meta": null
        },
        {
            "id": 127,
            "code": "INV-2023-0127",
            "sub_total": 42009912,
            "tax": 9200171,
            "discount": 0,
            "total": 51210083,
            "items": [
                {
                    "id": 737,
                    "product": {
                        "id": 11,
                        "name": "Velit error."
                    },
                    "price": 54418
                },
                {
                    "id": 738,
                    "product": {
                        "id": 15,
                        "name": "Deserunt unde qui."
                    },
                    "price": 55543
                }
            ],
            "billing": null,
            "payment": {
                "id": 127,
                "order_id": 127,
                "reference": "XFUUO3MZCJCJ",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-15T03:07:36.000000Z",
                "updated_at": "2023-07-15T03:07:36.000000Z"
            },
            "shipping": {
                "city": "North Erwinmouth",
                "state": "Delaware",
                "country": "Saint Kitts and Nevis",
                "last_name": "Stroman",
                "first_name": "Dillon",
                "street_address": "728 Welch Club Apt. 422"
            },
            "meta": null
        },
        {
            "id": 176,
            "code": "INV-2023-0176",
            "sub_total": 58650794,
            "tax": 12844524,
            "discount": 0,
            "total": 71495318,
            "items": [
                {
                    "id": 1031,
                    "product": {
                        "id": 11,
                        "name": "Velit error."
                    },
                    "price": 54418
                },
                {
                    "id": 1032,
                    "product": {
                        "id": 28,
                        "name": "Eos quo consequatur."
                    },
                    "price": 83567
                }
            ],
            "billing": null,
            "payment": {
                "id": 176,
                "order_id": 176,
                "reference": "L4KWPK8HXORK",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-14T03:51:17.000000Z",
                "updated_at": "2023-07-14T03:51:17.000000Z"
            },
            "shipping": {
                "city": "Port Daniellashire",
                "state": "Colorado",
                "country": "Central African Republic",
                "last_name": "Becker",
                "first_name": "Ryann",
                "street_address": "369 O'Reilly Crest Suite 043"
            },
            "meta": null
        },
        {
            "id": 58,
            "code": "INV-2023-0058",
            "sub_total": 18164392,
            "tax": 3978002,
            "discount": 27326,
            "total": 22115068,
            "items": [
                {
                    "id": 322,
                    "product": {
                        "id": 28,
                        "name": "Eos quo consequatur."
                    },
                    "price": 83567
                }
            ],
            "billing": null,
            "payment": {
                "id": 58,
                "order_id": 58,
                "reference": "LHGIJMZUHRWB",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-13T21:08:19.000000Z",
                "updated_at": "2023-07-13T21:08:19.000000Z"
            },
            "shipping": {
                "city": "Lake Clementinahaven",
                "state": "Nevada",
                "country": "Chile",
                "last_name": "Osinski",
                "first_name": "Boris",
                "street_address": "5942 Gulgowski Dam Suite 369"
            },
            "meta": null
        },
        {
            "id": 113,
            "code": "INV-2023-0113",
            "sub_total": 36911744,
            "tax": 8083672,
            "discount": 8129,
            "total": 44987287,
            "items": [
                {
                    "id": 648,
                    "product": {
                        "id": 50,
                        "name": "Sunt sit exercitationem."
                    },
                    "price": 91982
                },
                {
                    "id": 649,
                    "product": {
                        "id": 53,
                        "name": "Harum omnis."
                    },
                    "price": 80641
                },
                {
                    "id": 650,
                    "product": {
                        "id": 2,
                        "name": "Voluptas veniam."
                    },
                    "price": 97736
                },
                {
                    "id": 651,
                    "product": {
                        "id": 2,
                        "name": "Voluptas veniam."
                    },
                    "price": 97736
                },
                {
                    "id": 652,
                    "product": {
                        "id": 10,
                        "name": "Aut non modi."
                    },
                    "price": 85695
                }
            ],
            "billing": null,
            "payment": {
                "id": 113,
                "order_id": 113,
                "reference": "RPYFVWTJXQ5S",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-13T12:13:20.000000Z",
                "updated_at": "2023-07-13T12:13:20.000000Z"
            },
            "shipping": {
                "city": "North Cara",
                "state": "Hawaii",
                "country": "Tonga",
                "last_name": "Wuckert",
                "first_name": "Theron",
                "street_address": "922 Elenor Squares"
            },
            "meta": null
        },
        {
            "id": 178,
            "code": "INV-2023-0178",
            "sub_total": 59288379,
            "tax": 12984155,
            "discount": 22147,
            "total": 72250387,
            "items": [
                {
                    "id": 1036,
                    "product": {
                        "id": 38,
                        "name": "Pariatur rerum maxime."
                    },
                    "price": 32479
                },
                {
                    "id": 1037,
                    "product": {
                        "id": 53,
                        "name": "Harum omnis."
                    },
                    "price": 80641
                },
                {
                    "id": 1038,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 1039,
                    "product": {
                        "id": 1,
                        "name": "Suscipit qui."
                    },
                    "price": 9512
                },
                {
                    "id": 1040,
                    "product": {
                        "id": 6,
                        "name": "Consequatur a voluptas."
                    },
                    "price": 17738
                },
                {
                    "id": 1041,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 1042,
                    "product": {
                        "id": 60,
                        "name": "Aut corporis."
                    },
                    "price": 96403
                },
                {
                    "id": 1043,
                    "product": {
                        "id": 23,
                        "name": "Harum odit."
                    },
                    "price": 14393
                }
            ],
            "billing": null,
            "payment": {
                "id": 178,
                "order_id": 178,
                "reference": "SLVMHGRJLR3Q",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-11T02:28:05.000000Z",
                "updated_at": "2023-07-11T02:28:05.000000Z"
            },
            "shipping": {
                "city": "Kassulkeshire",
                "state": "Maine",
                "country": "Belize",
                "last_name": "Sauer",
                "first_name": "Nathanial",
                "street_address": "3941 Connelly Greens"
            },
            "meta": null
        },
        {
            "id": 202,
            "code": "INV-2023-0202",
            "sub_total": 67418856,
            "tax": 14764729,
            "discount": 22181,
            "total": 82161404,
            "items": [
                {
                    "id": 1176,
                    "product": {
                        "id": 8,
                        "name": "Corporis in."
                    },
                    "price": 99422
                },
                {
                    "id": 1177,
                    "product": {
                        "id": 6,
                        "name": "Consequatur a voluptas."
                    },
                    "price": 17738
                },
                {
                    "id": 1178,
                    "product": {
                        "id": 28,
                        "name": "Eos quo consequatur."
                    },
                    "price": 83567
                }
            ],
            "billing": null,
            "payment": {
                "id": 202,
                "order_id": 202,
                "reference": "G92GTTB68MOS",
                "status": "Paid",
                "meta": null,
                "created_at": "2023-07-09T22:37:45.000000Z",
                "updated_at": "2023-07-09T22:37:45.000000Z"
            },
            "shipping": {
                "city": "Noeliamouth",
                "state": "New Hampshire",
                "country": "Djibouti",
                "last_name": "Yundt",
                "first_name": "Jessyca",
                "street_address": "3872 Kathryne Manor Apt. 175"
            },
            "meta": null
        }
    ],
    "links": {
        "first": "http://commerce.test/api/v1/orders?page=1",
        "last": "http://commerce.test/api/v1/orders?page=16",
        "prev": null,
        "next": "http://commerce.test/api/v1/orders?page=2"
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 16,
        "links": [
            {
                "url": null,
                "label": "&laquo; Previous",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=1",
                "label": "1",
                "active": true
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=2",
                "label": "2",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=3",
                "label": "3",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=4",
                "label": "4",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=5",
                "label": "5",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=6",
                "label": "6",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=7",
                "label": "7",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=8",
                "label": "8",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=9",
                "label": "9",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=10",
                "label": "10",
                "active": false
            },
            {
                "url": null,
                "label": "...",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=15",
                "label": "15",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=16",
                "label": "16",
                "active": false
            },
            {
                "url": "http://commerce.test/api/v1/orders?page=2",
                "label": "Next &raquo;",
                "active": false
            }
        ],
        "path": "http://commerce.test/api/v1/orders",
        "per_page": 15,
        "to": 15,
        "total": 227
    }
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/orders/:id" baseUrl="" summary="Get one order" %}
{% swagger-description %}
This endpoint returns a single order item based on the id passed within the path parameter.
{% endswagger-description %}

{% swagger-parameter in="path" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Success" %}


```php
{
    "id": 81,
    "code": "INV-2023-0081",
    "sub_total": 26133747,
    "tax": 5723291,
    "discount": 28877,
    "total": 31828161,
    "items": [
        {
            "id": 444,
            "product": {
                "id": 38,
                "name": "Pariatur rerum maxime."
            },
            "price": 32479
        },
        {
            "id": 445,
            "product": {
                "id": 11,
                "name": "Velit error."
            },
            "price": 54418
        },
        {
            "id": 446,
            "product": {
                "id": 29,
                "name": "Cum doloremque qui."
            },
            "price": 27070
        },
        {
            "id": 447,
            "product": {
                "id": 60,
                "name": "Aut corporis."
            },
            "price": 96403
        }
    ],
    "billing": null,
    "payment": {
        "id": 81,
        "order_id": 81,
        "reference": "RCTE4WM0UVQE",
        "status": "Paid",
        "meta": null,
        "created_at": "2023-07-20T00:55:19.000000Z",
        "updated_at": "2023-07-20T00:55:19.000000Z"
    },
    "shipping": {
        "city": "West Earlineview",
        "state": "Missouri",
        "country": "Tuvalu",
        "last_name": "Gleichner",
        "first_name": "Evangeline",
        "street_address": "53020 Freddie Viaduct"
    },
    "meta": null
}
```
{% endswagger-response %}
{% endswagger %}
