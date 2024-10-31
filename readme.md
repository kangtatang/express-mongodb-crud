# A simple Express and MongoDB CRUD
This is a simple application to show CRUD concept using express JS and MongoDB.

## Installation

You will need to run `npm install` after cloning the repository.


## Run the App

You will need postman to test the API


- **Create (POST)**: `http://localhost:5001/api/items`
  - Body (JSON):
    ```json
    {
      "name": "Pensil",
      "quantity": 10
    }
    ```

- **Read (GET)**: `http://localhost:5001/api/items`
  - Get All Items (Untuk mendapatkan semua item).

- **Read by ID (GET)**: `http://localhost:5001/api/items/<id_item>`
  - Get Data By ID (Untuk mendapatkan item berdasarkan ID).

- **Update (PUT)**: `http://localhost:5001/api/items/<id_item>`
  - Update the data By ID
  - Body (JSON):
    ```json
    {
      "name": "Pensil Mekanik",
      "quantity": 15
    }
    ```

- **Delete (DELETE)**: `http://localhost:5001/api/items/<id_item>`
  - Delete Data By ID (Menghapus item berdasarkan ID).

