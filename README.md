# Flask API with MySQL

This is a simple Flask API that interacts with a MySQL database. It provides CRUD operations for managing customer records.

## Getting Started

1. Clone this repository.
2. Install Docker and Docker Compose.
3. Run `docker-compose up` to start the Flask app and MySQL database.

## API Endpoints

- `GET /api/customers`: Get a list of all customers.
- `GET /api/customers/<customer_id>`: Get details of a specific customer.
- `POST /api/customers`: Create a new customer.
- `PATCH /api/customers/<customer_id>`: Update an existing customer.
- `DELETE /api/customers/<customer_id>`: Delete a customer.

## Sample Request (POST)

```json
{
    "cnpj": "12345678901234",
    "name": "Sample Customer",
    "longitude": "123.456",
    "latitude": "-45.678"
}
