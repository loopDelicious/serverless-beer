# serverless-beer-rating

Use Serverless Framework to create 2 lambda functions (addRating post request, getRating get request)

Install node dependencies

    $ npm install
    
Set AWS credentials in your user directory, and add Admin Access to Role in IAM

    ~/.aws/credentials
    
Adjust config details in `serverless.yml` and lambda functions in `handler.js`
    
Trigger a new deploy, and test new endpoints with Postman or cURL

    $ serverless deploy
    
    
From tutorials:

Part 1:

https://www.netlify.com/blog/2016/09/15/serverless-jam---a-serverless-framework-tutorial/
Part 2: 

https://www.netlify.com/blog/2016/10/13/serverless-jam---a-serverless-framework-tutorial-part-2/
