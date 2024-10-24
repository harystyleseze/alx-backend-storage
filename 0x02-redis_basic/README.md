# Redis Basic Project

## Author
**Harrison Eze**  
GitHub: [harystyleseze](https://github.com/harystyleseze)

## Repository
This repository contains a series of exercises and implementations focusing on using Redis for caching and data storage.

### Repository Link
[alx-backend-storage](https://github.com/harystyleseze/alx-backend-storage)

### Directory
`0x02-redis_basic`

## Project Overview
The primary goal of this project is to explore the capabilities of Redis as an in-memory data store, particularly its use cases in caching, data retrieval, and handling expiring data.

## Contents
This project consists of the following tasks:

1. **Writing Strings to Redis**
   - Implementing a `Cache` class that stores data in Redis using random keys.

2. **Reading from Redis and Recovering Original Type**
   - Implementing methods to retrieve data from Redis, converting it back to its original type.

3. **Incrementing Values**
   - Using a decorator to count how many times methods of the `Cache` class are called.

4. **Storing Lists**
   - Implementing a decorator to keep a history of inputs and outputs for a function.

5. **Retrieving Lists**
   - Implementing a `replay` function to display the history of calls for a specific function.

6. **Implementing an Expiring Web Cache and Tracker**
   - Creating a `get_page` function that caches HTML content of a URL with an expiration time, along with tracking access counts.

## Requirements
- Python 3.7 or higher
- Redis server
- Required Python packages:
  - `redis`
  - `requests`

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/harystyleseze/alx-backend-storage.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd alx-backend-storage/0x02-redis_basic
   ```

3. **Install the required packages:**
   ```bash
   pip install redis requests
   ```

4. **Ensure you have a Redis server running.** You can start Redis using:
   ```bash
   redis-server
   ```

## Usage
- Each task is implemented in the `exercise.py` and `web.py` files.
- You can run the scripts using:
  ```bash
  python3 main.py  # For testing the Cache class
  python3 web.py   # For testing the get_page function
  ```

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments
- Special thanks to the ALX program for providing the structure and resources for this project.

