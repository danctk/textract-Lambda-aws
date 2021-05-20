# textract-Lambda-aws

This project is an API that recieves Base64 encoded images and uses ML enabled algorithims using AWS Textract to determine text relationships and creates a dictionary of paired values to be used in application.

USE case: analyze an image to extract text to fill out online forms

you will need to create a BOTO3 layer in the lambda function to import the library
