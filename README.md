<h1 align="center">Shark Store 🛒</h1>

## Description
------------

This project is a simple e-commerce web application to provide a basic online shopping experience. The application allows users to browse and purchase products from a catalog, manage their shopping cart, and complete transactions using a secure payment gateway.

The application provides the following core features:

* **Product Catalog**: A comprehensive catalog of products, including product details, images, and pricing information.
* **Shopping Cart**: A secure shopping cart that allows users to add, remove, and update products.
* **Checkout**: A streamlined checkout process that allows users to complete transactions using a secure payment gateway.
* **User Management**: Basic user management features, including user registration, login, and profile management.
* **Order Management**: Basic order management features, including order tracking and history.

Overall, this project provides a solid foundation for a basic e-commerce application.

## Project Setup
------------
### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=production
```

### Build the application

```shell
npm run build
```

### Start the app

```shell
npm run start
```

## Testing
To test the application, you can use the following login credentials:
* Customer:
	+ Email: `abc@gmail.com`
	+ Password: `123456`
* Admin:
	+ Email: `john@gmail.com`
	+ Password: `123456`

Please note that these credentials are only for testing purposes and should not be used in production.

After logging in, you can test the admin role by accessing the admin dashboard and verifying that you have the expected permissions.