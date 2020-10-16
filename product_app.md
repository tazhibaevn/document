# APPLICATION PRODUCT

##### List of links 

>1. [Top sales](#get-list-of-top-sales)
>2. [Product card](#get-list-of-product-card)
>3. [Store](#get-list-of-store )
>4. [Branch by id](#get-branch-by-id)
>7. [Branch products ](#get-branch-products)
>5. [Branch rating ](#get-list-of-branch-rating)
>6. [Branch schedule](#get-list-of-schedule)
>7. [Branch moderator](#get-list-of-branch-moderator)
>2. [Branch main branch](#get-list-of-main-branch)
>2. [Suggesting store](#get-list-of-suggesting-store)

## Get list of top sales
#### Request method: GET

## [/product/top_sales/](https://demoapp.baitushum.kg/product/top_sales/) 


### Sample response

	{
    "count": 3,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": 17,
            "card_image": "https://demoapp.baitushum.kg/media/product_card/err_serv_.png",
            "card_name": "Xioami Redmi note 9",
            "price": 23000
        },
        {
            "id": 18,
            "card_image": "https://demoapp.baitushum.kg/media/product_card/Samsung-S20-BTS-Edition.jpg",
            "card_name": "Samsung Galaxy S20",
            "price": 10000
        },
        {
            "id": 22,
            "card_image": "https://demoapp.baitushum.kg/media/product_card/refrigerator_PNG9035.png",
            "card_name": "Холодильник   Xiaomi",
            "price": 23000
        }
        ]
    }
    
## Get list of product card
#### Request method: GET

[https://demoapp.baitushum.kg/product/card/](https://demoapp.baitushum.kg/product/card/) 


### Sample response

	{
    "count": 20,
    "next": "https://demoapp.baitushum.kg/product/card/?page=2",
    "previous": null,
    "results": [
        {
            "id": 4,
            "card_name": "Телевизоры Смарт XIAOMI MI TV 4A 32 81 см",
            "card_image": "https://demoapp.baitushum.kg/media/product_card/xiaomi-mi-tv-4a-32-81-sm-cernyj-1801503-1.webp",
            "price_min": 0,
            "price_max": 0
        },
        {
            "id": 5,
            "card_name": "Телевизор LED Samsung UE50NU7090U 125 см черный",
            "card_image": "https://demoapp.baitushum.kg/media/product_card/imagesassas.jpeg",
            "price_min": 0,
            "price_max": 0
        },
        {
            "id": 6,
            "card_name": "Thomas Graf SCMLW0130_173 однотонная синяя XL",
            "card_image": "https://demoapp.baitushum.kg/media/product_card/f1.png",
            "price_min": 0,
            "price_max": 0
        },
        {
            "id": 7,
            "card_name": "DeFacto N3733AZ в полоску коричневый S",
            "card_image": "https://demoapp.baitushum.kg/media/product_card/p1.jpeg",
            "price_min": 0,
            "price_max": 0
        }
      ]
      }
     
             
## Get an item of product card
#### Request method: GET

[https://demoapp.baitushum.kg/product/card/1/](https://demoapp.baitushum.kg/product/card/1/) 


### Sample response
	{
    "id": 4,
    "card_name": "Телевизоры Смарт XIAOMI MI TV 4A 32 81 см",
    "attribute_type": [
        {
            "id": 3,
            "name": "Размер",
            "tag_attribute_type": "SIZE",
            "attributes": [
                {
                    "id": 13,
                    "name": "S-XL",
                    "attribute_type": 3,
                    "tag_attribute": null
                }
            ]
        }
    ],
    "category": {
        "id": 1,
        "name": "Электроника",
        "image": "https://demoapp.baitushum.kg/media/category/Screenshot_from_2020-09-15_11-08-15_VxLQMFT.png"
    },
    "sub_category": {
        "id": 4,
        "name": "Телевизоры",
        "category_name": "Электроника"
    },
    "brand": {
        "id": 4,
        "name": "XIAOMI",
        "description": "",
        "logo": "https://demoapp.baitushum.kg/media/brand/images.png"
    },
    "scope": {
        "id": 1,
        "name": "Товар"
    },
    "card_gallery": [
        {
            "id": 11,
            "card": 4,
            "image": "https://demoapp.baitushum.kg/media/product_card/xiaomi-mi-tv-4a-32-81-sm-cernyj-1801503-2.webp"
        },
        {
            "id": 12,
            "card": 4,
            "image": "https://demoapp.baitushum.kg/media/product_card/xiaomi-mi-tv-4a-32-81-sm-cernyj-1801503-1_zhvpX3H.webp"
        },
        {
            "id": 44,
            "card": 4,
            "image": "https://demoapp.baitushum.kg/media/product_card/Screenshot_from_2020-08-20_16-36-55.png"
        }
    ],
    "price_min": 0,
    "price_max": 100000000,
    "products": []
}
