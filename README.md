# Strapi application

Running in production at: https://um-exam-api.herokuapp.com/

Endpoints:

GET Products: https://um-exam-api.herokuapp.com/products 

GET by id: https://um-exam-api.herokuapp.com/products/1  

GET Categories: https://um-exam-api.herokuapp.com/categories 

GET Colors: https://um-exam-api.herokuapp.com/colors 

GET Sizes: https://um-exam-api.herokuapp.com/sizes  

GET Types: https://um-exam-api.herokuapp.com/clothes 

GET Brands: https://um-exam-api.herokuapp.com/brands 

POST Products:

```
{
    "name": "INSERT NAME",
    "description": "INSERT DESCRIPTION",
    "price": 479,
    "stock": 10,
    "clothing": {
      "id": 5
    },
    "brand": {
      "id": 11
    },
    "images": [
      {
        "id": 1
      }
    ],
    "categories": [
      {
        "id": 1
      }
    ],
    "sizes": [
      {
      "id": 2
    },
    {
      "id": 3
    },
    {
      "id": 4
    }
  ],
  "colors": [
    {
      "id": 1
    }
  ]
}
```
