# UMN-SplunkRA
This moduel is a Powershell wrapper for Splunk Rest API based off http://dev.splunk.com/restapi

The first step is to log in.  Use the function Connect-Splunk, this will return a properly formatted header containing the authorization token that will be used is all the other functions.
This function is based off the following: http://docs.splunk.com/Documentation/Splunk/latest/RESTUM/RESTusing#Authentication_and_authorization

Invoke-SplunkBase is the base function that all the others are built on top of.  Anything you need the API to do that there is not already a specific function for can be called with this one function.

