Product data read from 
http://redsky.target.com/v2/pdp/tcin/<PRODUCTID>?excludes=taxonomy,price,promotion,bulk_ship,rating_and_review_reviews,rating_and_review_statistics,question_answer_statistics


URL and Curl commands to run  the application.

http://localhost:8080/products/13860428

curl -X PUT -H "Content-Type: application/json" -d '{"id":13860428,"name":"The Big Lebowski (Blu-ray)","price":{"value":16.99,"currencyCode":"USD"}}' "http://localhost:8080/products/13860428"

Pricing data read from no sql mongoDB database

current data in the database

{ name : "The Big Lebowski (Blu-ray)", value : "16.99", currency_code : "USD", id : "13860428" }
{ name : "IPhone 8 16GB", value : "800.5", currency_code : "USD", id : "13860429" }
{ name : "Samsung Galaxy S8", value : "700.99", currency_code : "USD", id : "13860430" }