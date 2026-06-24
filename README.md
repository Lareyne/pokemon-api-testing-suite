# PokeAPI Testing Project

A Postman project built to learn and demonstrate the fundamentals of API testing using the public PokeAPI. This project tests how a system responds to correct data, filtered data, and user errors.

## What This Project Demonstrates:
* **Successful Data Retrieval (Positive Test):** Confirms that searching for a valid Pokémon (like Pikachu) successfully connects to the server and returns the correct 200 OK status code and database information.
* **Error and Edge-Case Handling (Negative Test):** Tests how the system handles mistakes by intentionally sending an invalid query string (`notarealpokemon`) and verifying that the server safely rejects it with an expected "404 Not Found" error.
* **Filtering and Sorting Results:** Uses API query parameters to limit a list of Pokémon to exactly 5 results, proving how websites handle large databases efficiently.
* **Page Navigation (Pagination):** Uses an offset control parameter to skip the first 5 records and view the next set, showing how website pages function.
* **Speed and Performance Testing:** Implements an automated validation check script to verify that the server responds under 500ms to ensure a good user experience.

## How To Run This Project
1. Download the Collection: Download the [Pokemon_API_Testing.json]([https://github.com/Lareyne/pokemon-api-testing-suite/blob/main/Pokemon%20API%20Testing.postman_collection.json) file from this repository to your computer.
2. Import into Postman: Open Postman, click the Import button in the top-left corner of your workspace sidebar, and upload the downloaded .json file.
3. Open the Runner: Hover over the imported PokeAPI Testing Project folder in your left sidebar, click the three dots (...), and select Run.
4. Execute the Tests: In the functional runner configuration tab that opens, click the Start Run button.
5. Verify the Results: Review the automated test results page to verify that all functional, performance, and boundary checks complete successfully with green status pass marks.





