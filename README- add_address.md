### README- add_address


#### Description-
- This API inserts address details into the *useraddresses* table.
- Data is passed to the API in JSON by frontend application.
- POST Method used.
- Assuming that pincode api is already applied.
- **The API will work only when the User is Logged in as we are passing token in Headers.**


#### API Url-
- http://103.217.220.149:80/api/v1/post/address_form
- Headers: **KEY**- *Authorization*, **VALUE**- *Token da0a3bed7fd86b67f0cddd7f49248813a14f00f4*
- The token belonged to **mukul.meri@gmail.com** login.


#### Test Data-
	{
		"data" :
		{
		"title" : "test_final",
	    "rec_name" : "aayush_test",
	    "pincode" : 12345,
	    "address" : "test",
	    "landmark" : "test",
	    "phone_no" : 123456789,
	    "state_name" : "test",
	    "city_name" : "test",
	    "country_name" : "test",
	    "is_primary" : "Y"
	}
	}


#### Output-
- Postman Output *(when properly data passed)*
![Postman Output](output_postman_add_address_1.png)

- Postman Output *(when improperly data passed)*
![Postman Output](output_postman_add_address_2.png)

- MySQL Output
![MySQL Output](output_mysql_add_address.png)


#### Improvements-
- **executed the following queries in useraddresses table.**
   - ALTER TABLE useraddresses DROP COLUMN country_id, DROP COLUMN state_id, DROP COLUMN city_id;
- **execute all the queries in MyPustak Live database.** 


#### AUTHOR-
- **coded by AAYUSH GADIA** 
- **contact info: gadia.aayush@gmail.com**
- **written on: 19th Feb' 2019**
- **updated on: 1st March' 2019** (converted it to token based & common models integrated)