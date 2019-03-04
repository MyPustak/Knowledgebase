### README- get_productinfo


#### Description-
- This API fetches the product details as well as product condition.
- Product details comprises of book_id, title, slug, thumb, price, publication etc.
- Product condition tells about the different conditions of books avaialable & for each condition it picks up the oldest user & returns the book_inv_id, donor_name, rack_no, shipping **(if available)** , its avatar & the **total no of books available for that particular condition & all the book_inv_id's for that particular condition.**
- It returns data in JSON format.
- GET Method used.


#### API Url-
- In-Stock URL:
  http://103.217.220.149:80/api/v1/get/product/object-oriented-programming-in-turbo-c-in-english

- Out of Stock URL:
  http://103.217.220.149:80/api/v1/get/product/you-can-win

- **IMPORTANT**-
	- **All the below urls will fetch the same output.**
	- http://103.217.220.149:80/api/v1/get/get-books/810/
	- http://103.217.220.149:80/api/v1/get/category/810/
	- http://103.217.220.149:80/api/v1/get/product/810/	
	- *All these urls are dynamically changed by changing the page number, each page gives 10 products as output.*


#### Test Data-
- *No data given as input.*   


#### Output-
- Postman Output 1 (when in stock)
![Postman Output 1](output_postman_get_productinfo_1.png)

- MySQL Output 1 (when in stock)
![MySQL Output 1](output_mysql_get_productinfo_1.png)

- Postman Output 2 (when out of stock)
![Postman Output 2](output_postman_get_productinfo_2.png)

- Postman Output 3 (for get-books, category, product)
![Postman Output 3](output_postman_get_books_3.png)
![Postman Output 4](output_postman_category_3.png)
![Postman Output 5](output_postman_product_3.png)


#### References-
- when a book exists in book inventory table & it is in stock but its corr. row isn't present in new_pricing_model table, then an output of "NA" is returned for "shipping" field.


#### Improvements-
- generate the row in new_pricing_model table for each book present in book inventory table.
- for fixing the existing books issue, make a script that will open the urls of all the books which are in stock.
- for fixing the future books issue, make the row insert in new_pricing_model table at the time of book entry in book inventory table.
- divide this API into 2 API's, one for fetching product details & other for fetching product condition.


#### AUTHOR-
- **coded by AAYUSH GADIA** 
- **contact info: gadia.aayush@gmail.com**
- **written on: 23rd Feb' 2019**
- **updated on: 25th Feb' 2019** (made /product url dynamic by page_no & added /get-books & category info in readme & fixed limit offset)
- **updated on: 26th Feb' 2019** (feature added- total qty for each condition of book)
- **updated on: 27th Feb' 2019** (common models integrated, book_id, book_inv_id & all the book_inv_id fetch enabled)

