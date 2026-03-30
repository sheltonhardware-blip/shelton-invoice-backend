# shelton-invoice-backend

A simple Node.js backend for managing invoices using Express and MongoDB.

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Ensure MongoDB is running locally on port 27017.

3. Start the server:
   ```
   npm start
   ```

The server will run on http://localhost:3000

## API Endpoints

- `GET /invoices` - Retrieve all invoices
- `POST /invoices` - Create a new invoice

Example POST body:
```json
{
  "client": "Client Name",
  "amount": 100.00,
  "date": "2023-01-01",
  "description": "Invoice description"
}
```