### Steps

1. npm install -g serverless

2. serverless login

3. serverless config credentials --provider aws --key xxxxxxxxxxxxxx --secret xxxxxxxxxxxxxx


//create the boilerplate mentioned above

4. sls create --template  hello-world

// generate a package.json file

5. npm init


//install express - a simple web framework
//install the body-parser middleware
//install view engine for express
//you'll need serverless-http to connect your api to aws

6. npm i --save express body-parser hbs serverless-http

7. change handler.js

8. copy view/index.hbs

9. change serverless.yml

10. sls deploy

### Local testing

1. serverless invoke local -f app
