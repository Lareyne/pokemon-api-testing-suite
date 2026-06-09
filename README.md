# PokeAPI Testing Project

A Postman project built to learn and demonstrate the fundamentals of API testing using the public PokeAPI. This project tests how a system responds to correct data, filtered data, and user errors.

## What This Project Demonstrates:
* **Successful Data Retrieval:** Confirms that searching for a valid Pokémon (like Pikachu or Dragonite) successfully connects to the server and returns the correct information.
* **Error and Edge-Case Handling:** Tests how the system handles mistakes by intentionally searching for a non-existent Pokémon and confirming the server safely rejects it with a "404 Not Found" error.
* **Filtering and Sorting Results:** Uses search parameters to limit a list of Pokémon to exactly 5 results, proving how websites handle large databases.
* **Page Navigation (Pagination):** Uses page controls to skip the first 5 records and view the next set, showing how website pages function.
* **Speed and Performance Testing:** Sets an automated timer to verify that the server responds quickly to ensure a good user experience.

## How To Run This Project
1. Download the `Pokemon API Testing.postman_collection.json` file from this repository.
2. Open Postman, click **Import** in the top-left corner, and select the downloaded file.
3. Click on the folder name on the left side and select **Run Collection** to watch all the tests automatically run at once.
