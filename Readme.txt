Greetings 

To execute the available unittests from the VS terminal, use the command: python manage.py test tests/. Ensure that you activate the virtual environment and navigate to the 'littlelemon' directory before running the unit-tests command.

For checking the serving of static HTML content with images and styles in the web application, utilize the following path: /restaurant.

You have the option to employ the API paths below for testing purposes, either through Insomnia or Postman clients, or by simply browsing with your preferred web browser.

JDOSER endpoint: For example, to make a POST request and create a new user, use /auth/users/.

To login and obtain authentication token: /api-token-auth/. For login using the JDOSER endpoint, use /auth/token/login.

Menu items:

/restaurant/menu/
/restaurant/menu/{menuItemId}
Table booking:

/restaurant/booking/tables/
/restaurant/booking/tables/{bookingId}
