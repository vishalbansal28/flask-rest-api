
# flask-rest-api

A flask-driven RESTful API for managing bucketlists. This project provides endpoints for creating, reading, updating, and deleting bucketlists and associated items. 

## Features

* **User Authentication:** Securely manage user accounts with registration and login. 
* **Bucketlist Creation:** Users can create their own bucketlists with descriptive titles.
* **Bucketlist Items:** Users can add items to their bucketlists, including descriptions.
* **CRUD Operations:**
    * **Create:** Create new bucketlists and items.
    * **Read:** Retrieve existing bucketlists and their items.
    * **Update:** Modify bucketlist titles and item details.
    * **Delete:** Remove bucketlists and items.
* **Pagination:** Efficiently handle large datasets by retrieving data in manageable chunks.
* **Error Handling:** Provides informative error messages for invalid requests or data.
* **Testing:** Includes unit tests to ensure API functionality and robustness.


## Getting Started

1. **Clone the repository:** `git clone git@github.com:vishalbansal28/flask-rest-api.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Configure environment variables:**
   - Create a `.env` file with the following values:
     ```bash
     SECRET="your-secret-key"
     APP_SETTINGS="development"
     DATABASE_URL="postgresql://username:password@localhost:5432/database_name"
     ```
   - Replace placeholders with your actual values.
4. **Create and migrate the database:**
   - `flask db init`
   - `flask db migrate`
   - `flask db upgrade`
5. **Run the application:** `flask run`
6. **Access the API:** The API is available at `http://localhost:5000`. You can use Postman or similar tools to explore the endpoints and interact with the API.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.

## License

This project is licensed under the MIT License.