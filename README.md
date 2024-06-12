# python-assessment

# Sample API Requests

This directory contains sample API requests for the Data Pusher Django application. These samples demonstrate how to interact with the various endpoints of the API.

I am accessing the endpoint using Django REST framework views and sending requests via Postman with the incoming_data.json request. All requests are working correctly in Postman. However, I am using the Django REST framework interface for easier reference and management

## Files in core/sample Api

- `create_account.json`: For creating a new account.
- `create_destination.json`: For creating a new destination for an account.
- `get_account.json`: For retrieving account details.
- `get_destinations.json`: For retrieving all destinations for an account.
- `update_account.json`: For updating an account.
- `delete_account.json`: For deleting an account.
- `incoming_data.json`: For sending data to be forwarded to account destinations.
