# Application_Health_Checker
Python script that checks the uptime of an application and determine if it is functioning correctly or not.It also accurately assess the application's status by checking HTTP status codes.

## Prerequisites
- Python 
- `requests` library

Install the `requests` library using pip:

This script checks the Application health and gives result whether the application is "UP" or "DOWN".
If the application is Down it also shows the HTTP status code.

Here to obtain different results or check the code for different case modify the variable "URL" with different application urls.

For example:
    URL = "https://www.youtube.com" --gives result as application is up
  Now test with other url
    URL = "https://www.accuknox.com" --gives result as application is down with status code 403

