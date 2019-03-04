### README- user_orders


#### Description-
- **Fetches i_date, payusing, status, actual_date_upload, amount, order no, no_of_book, book thumb, book title,
book price by joining orders, order_books & books table.**
- **Here the recent orders are showed first.**
- **The data fetched changes dynamically on changing the page number in url.**
- Data is returned in JSON.
- GET Method used.
- Fetched by passing token to the API in headers.
- **The API will work only when the User is Logged in as we are passing token in Headers.**


#### API Url-
- http://103.217.220.149:80/api/v1/get/user_orders/1/
- http://103.217.220.149:80/api/v1/get/user_orders/2/
- Headers: **KEY**- *Authorization*, **VALUE**- *Token da0a3bed7fd86b67f0cddd7f49248813a14f00f4*
- The token belonged to **mukul.meri@gmail.com** login.


#### Test Data-
- No data to pass.


#### Output-
- Postman Output **(when entered a page viz within limits)**
![Postman Output](output_postman_user_orders_1.png)

- Postman Output **(when entered a page viz outside limits)**
![Postman Output](output_postman_user_orders_2.png)


#### References-
- *ORDER STATUS :: 
   0- processing, 1- complete, 2- cancel, 3- refund, 4- fail, 5- shipping, 6- shippment booked, 7- ready to ship*


#### Improvements-
- Nothing to make.


#### AUTHOR-
- **coded by AAYUSH GADIA** 
- **contact info: gadia.aayush@gmail.com**
- **written on: 25th Feb' 2019**
- **updated on: 28th Feb' 2019** (converted it to token based, common models integrated & url changed)
