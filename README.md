# Order Stock Manager

## About

Order Stock Manager is a Go-based application designed to manage product orders and ingredient stock for food service operations. It uses MongoDB to store and manage data about products, ingredients, and their stock levels.

## How it works

1. The system maintains two main collections: Products and Ingredients.
2. Products are defined with their ingredients and required quantities.
3. Ingredients are tracked with their current stock levels.
4. When orders are processed, the system automatically updates ingredient stock levels.
5. The application provides real-time stock management and can alert when ingredients are running low.

## Features

- Product management with ingredient details
- Real-time stock tracking
- Order processing with automatic stock updates
- Separate environments for production and testing

## How to run

1. Ensure you have Docker installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory.
4. Run the following commands:




1. Run `docker compose up -d`
2. Run `go run main.go`


5. The application should now be running and ready to use.

## Database

The application uses two MongoDB databases:
- `order-stock-manager` for production
- `order-stock-manager-test` for testing

Seed data is provided for both environments in the `seeds` directory.

## Development

To contribute or modify the application, refer to the Go files in the project. The main application logic can be found in `main.go` and the `model` directory.