# Profite API

Api básica utilizada para estudos.

* Ruby version: 2.3.1

* Rails version: 5.0.1


# API

## Endpoints

#### Category

* https://profite-study-api.herokuapp.com/api/categories - GET / POST

* https://profite-study-api.herokuapp.com/api/categories/{:id} - GET / PUT / PATCH


#### Product

* https://profite-study-api.herokuapp.com/api/products - GET / POST

* https://profite-study-api.herokuapp.com/api/products/{:id} - GET / PUT / PATCH


## Schemas
```
{"entity": {
    "attribute1": "value",
    "attribute2": "value",
  }
}
```
#### Expemples
```
{"product": {
    "name": "Livro Rails 5",
    "description": "Livro que ensina o Framework Rails e permite você desenvolver um site do zero ao deploy usando as melhores técnicas de desenvolvimento.",
    "short_description": "Livro que ensina o Framework Rails",
    "price": 40.00,
    "best_price": 29.99,
    "quantity": 50
  }
}
```
