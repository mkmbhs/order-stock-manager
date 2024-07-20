# Order Stock Manager

A robust Go-based application for managing product orders and ingredient stock in food service operations, utilizing MongoDB for efficient data management.

## Features

- Product management with detailed ingredient tracking
- Real-time stock level monitoring
- Automated stock updates upon order processing
- Separate environments for production and testing
- Docker-based deployment for easy setup and scalability

## How to run

### Prerequisites

- Docker
- Go (version 1.x or later)

### Steps

1. Clone this repository:



    ```git clone https://github.com/yourusername/order-stock-manager.git cd order-stock-manager```


2. Start the MongoDB container:



docker compose up -d


3. Run the application:



go run main.go


4. The application is now running and ready to use.

## Configuration

Environment variables (if any) can be set in a `.env` file in the project root.

## Testing

To run tests using the test database:

1. Ensure the MongoDB container is running.
2. Execute:



go test ./...


## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Troubleshooting

If you encounter any issues, please check the following:
- Ensure Docker is running and the MongoDB container is up
- Verify that all required Go packages are installed
- Check the application logs for any error messages

For further assistance, please open an issue on the GitHub repository.

## Contact

For support or queries, please open an issue on GitHub.



