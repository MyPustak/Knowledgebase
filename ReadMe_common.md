# Common

## Endpoints

1. Data for sending recommendations to users on the basis of notify option

#### URL  :  http://103.217.220.149:80/common/recommender/<page-number>/

Sample  :  http://103.217.220.149:80/common/recommender/4/               [(For page 4)]






2. Add To Cart an item for authenticated user

#### URL:  http://103.217.220.149:80/common/addtocart/

CURL SAMPLE : curl -X POST \
http://103.217.220.149:80/common/addtocart/ \
-H 'Authorization: Token 8798e8b27ea9d392616af9565fe200e8adefbf2f' \
-H 'content-type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW' \
-F book_id=142

#### Description: Adds the book_id with authenticated user_id in a newly created row in 'cart_session' table. 
