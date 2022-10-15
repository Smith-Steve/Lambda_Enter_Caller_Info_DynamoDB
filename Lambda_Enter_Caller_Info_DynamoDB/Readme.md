# AWS Lambda Empty Function Project

## Purpose

This code base originated as a 'AWS Lambda Empty Function' Project.

This starter project consists of:
* Function.cs - class file containing a class with a single function handler method
* aws-lambda-tools-defaults.json - default argument settings for use with Visual Studio and command line deployment tools for AWS

This function's purpose is divided up into a couple of different areas

1.) Add new phone numbers to the DynamoDB table.
2.) Check if phone number is already in there.
3.) If phone number is in there, update the entry for the number.