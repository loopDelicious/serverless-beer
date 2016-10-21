# serverless-beer-rating

Use Serverless Framework to create 2 lambda functions (addRating post request, getRating get request)

Install node dependencies

    $ npm install
    
Set AWS credentials in your user directory, and add Admin Access to Role in IAM

    ~/.aws/credentials
    
Adjust config details in `serverless.yml` and lambda functions in `handler.js`
    
Trigger a new deploy, and test new endpoints with Postman or cURL

    $ serverless deploy