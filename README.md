# Template for new services

**Remember to overwrite this file**

## Starting a new project 
Firstly we will create a serverless project using our serverless template from GitHub
```
serverless create --template-url https://github.com/Perrep/serverless-template --path service_name
```

Then we need to install nodeJS dependencies
```
npm install
```


## Creating new functions
Use the following command to ease the creations of new functions:

``` 
sls create function --function functionName --handler src/functions/functionName.functionName --path src/tests/
```

