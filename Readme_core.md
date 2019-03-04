# Token Based Authetication

Usage Example


# 1. Get Token 
curl -X POST \
http://103.217.220.149:80/core/get_token/ \
-H 'content-type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW' \
-F email=test2018@gmail.com \
-F password=password


#### Description: A token wil be returned that the client can use to make requests to server
The token should be included as a header file as given below.


# 2. Test Token
curl -X GET \
http://103.217.220.149:80/core/hello/ \
-H 'Authorization: Token 9d2d3e9ca2cdbe2203584a47d9975206f01e581c' \
-H 'cache-control: no-cache'

#### Description: The API return the user email associated with the passed token

# 3. Password Reset

## WOrking : 
1. The front-end calls 'Send Reset Email' API with the email of the user as post data
2. The API generates a reset url and send an email to the user.
3. Clicking on the link, the landing page should extract the 'token' parameter from the url and present the reset page to user.
4. On submitting the form the front-end should call the 'Reset Password' API with the extracted token as header and validated password as form data.

### A) Send Reset Email
curl -X POST \
http://103.217.220.149:80/core/forgot_password/ \
-H 'content-type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW' \
-F email=test2018@gmail.com

#### Description: The API sends the password reset email to the verified user with authentication token as url parameter

### B) Reset Password
curl -X POST \
http://103.217.220.149:80/core/reset_password/ \
-H 'Authorization: Token 59928dbe6d7687cf9a6c89de5673a07e8c5e253c' \
-H 'cache-control: no-cache' \
-H 'content-type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW' \
-F password=password

#### Description: The Token in the header is used to determine the user andf the password is reset to that of the value passed in the post request.


# 3. Logout
curl -X GET \
http://103.217.220.149:80/core/logout/ \
-H 'Authorization: Token 9d2d3e9ca2cdbe2203584a47d9975206f01e581c' \
-H 'cache-control: no-cache'

#### Description: The API deletes the token of the user making it invalid





##### Room for Improvement
1. For password reset temporary tokens with expiration can be implemented to strengthen security further.
