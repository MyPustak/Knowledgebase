# Application Donation

## End points:


1. Donation Table API:

    Function : To fetch the details of Donors according to the total books donated
    
    Url : 'http......../donation/donortable/page<pagenumber>/
    sample: 'http://103.217.220.149:80/donation/page4/'








2. Donor's statewise location API:

    Function : API to fetch the No. of Donors from each state
    
    URL : 'http://103.217.220.149:80/donation/donorslocation/'







3. Donor History API:   [Authentication Required]

    Function: To fetch the past donations requests details of the authenticated donor.
    
    URL
    http://127.0.0.1:8000/donation/donorhistory/
    
    CURL
    curl -X GET \
    http://127.0.0.1:8000/donation/donorhistory/ \
    -H 'Authorization: Token 1243aa55fafd25e769a7159291bced75a262af38' \
    
    Issues: column 'donationreqs.no_of_book' value doesn't match with the number of books fetched through the API

