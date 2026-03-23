# lambda-function-aws
lambda function aws

# code 


def lambda_handler(event, context):

    name=event['name']
    
    age = event['age']
    
    return {
        "message": "Hello " + name,
        "age": age
    }

  # create test event

  {
 "name": "Alice",
 "age": 22
}


# next is API gateway + lambda function

API gateway

create API

HTTP API

Build

add integration

choose lambda

my_lambda_function

next

configure route

GET/Hello

deploy API
  
