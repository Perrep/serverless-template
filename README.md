# Template for new services

**Remember to overwrite this file after creating new service using this as a template**

## Starting a new service 
Firstly we will create a serverless project using our serverless template from GitHub
```
serverless create --template-url https://github.com/Perrep/serverless-template --path service_name
```

Then we need to install nodeJS dependencies
```
npm install
```

Change the content of serverless.yml
```
service: SERVICE_NAME
app: APP_NAME
org: ORG_NAME
```

Now you can deploy the service to serverless and aws
```
serverless deploy
```

## Creating new functions
Use the following command to ease the creations of new functions:

``` 
serverless create function --function functionName --handler src/functions/functionName.functionName --path src/tests/
```

