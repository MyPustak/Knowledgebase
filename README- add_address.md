### README- edit_address


#### Description-
- This API edits address details present in the *useraddresses* table.
- Data is passed to the API in JSON by frontend application.
- POST Method used.
- Assuming that pincode api is already applied.
- **The API will work only when the User is Logged in as we are passing token in Headers.**


#### API Url-
- http://103.217.220.149:80/api/v1/post/edit_address
- Headers: **KEY**- *Authorization*, **VALUE**- *Token da0a3bed7fd86b67f0cddd7f49248813a14f00f4*
- The token belonged to **mukul.meri@gmail.com** login.


#### Test Data-
	{
		"data" :
		{
		"address_id" : 32934,
		"title" : "test_final_2_update",
	    "rec_name" : "aayush_test_2",
	    "pincode" : 123456,
	    "address" : "test_2",
	    "landmark" : "test_2",
	    "phone_no" : 1234567892,
	    "state_name" : "test_2",
	    "city_name" : "test_2",
	    "country_name" : "test2",
	    "is_primary" : "Y"
	}
	}


#### Output-
- Postman Output *(when properly data passed)*
![Postman Output](output_postman_edit_address_1.png)

- Postman Output *(when improperly data passed)*
![Postman Output](output_postman_edit_address_2.png)

- MySQL Output
![MySQL Output](output_mysql_edit_address_1.png)


#### Improvements-
- *Nothing to make.*


#### AUTHOR-
- **coded by AAYUSH GADIA** 
- **contact info: gadia.aayush@gmail.com**
- **written on: 1st March' 2019**