# estore
a Documentation for Api endpoints 

1. view wish-list (cart items)[vwl]
2. add to wishlist
3. remove from wishlist

## View WishList :

Request : GET -> https://india-naa.in/api/v1/cutomer/wish-list/

with no param or request body 

## Add To WishList :

Request : POST -> https://india-naa.in/api/v1/cutomer/wish-list/add/

| Parameter | description |
|-----------|-------------|
| product_id | required  |

## Remove From WishList :

Request : Delete -> https://india-naa.in/api/v1/cutomer/wish-list/remove/

| Parameter | description |
|-----------|-------------|
| product_id | required  |
