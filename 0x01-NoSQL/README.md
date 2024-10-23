# ALX Backend Storage

Welcome to the **ALX Backend Storage** project! This repository contains a series of implementations and tasks designed to enhance your understanding of backend storage solutions using NoSQL databases, specifically MongoDB.

## Author Information

- **Name**: Harrison Eze  
- **GitHub Username**: [harystyleseze](https://github.com/harystyleseze)  
- **Profile**: [GitHub Profile](https://github.com/harystyleseze)

## Project Overview

The **ALX Backend Storage** project is part of the ALX curriculum, focusing on practical applications of NoSQL databases. This repository emphasizes MongoDB, where you will learn how to:

- Insert and update documents in collections.
- Query data using different filtering methods.
- Utilize aggregation for data analysis.
- Work with regular expressions for data retrieval.

## Directory Structure

```
alx-backend-storage/
└── 0x01-NoSQL/
    ├── 0-insert_school.py
    ├── 1-update_topics.py
    ├── 2-schools_by_topic.py
    ├── 3-log_stats.py
    ├── 4-regex_filter.py
    ├── 5-top_students.py
    └── 6-log_stats_v2.py
```

### Task Descriptions

1. **Insert a Document**
   - Functionality to insert a document into a MongoDB collection.
   - Example usage: Adding new school information.

2. **Change School Topics**
   - Update all topics of a school based on its name.
   - Utilizes MongoDB's update operations to modify existing documents.

3. **Where Can I Learn Python?**
   - Retrieves a list of schools that offer a specified topic.
   - Demonstrates querying capabilities using specific attributes.

4. **Log Stats**
   - Provides statistics about Nginx logs stored in MongoDB.
   - Counts total logs and breaks down by HTTP methods.

5. **Regex Filter**
   - Lists all documents where the name starts with "Holberton".
   - Showcases the use of regular expressions for querying.

6. **Top Students**
   - Returns students sorted by average scores across various topics.
   - Calculates average scores and sorts results accordingly.

7. **Log Stats - New Version**
   - Enhances log statistics by including the top 10 most frequent IP addresses in the logs.
   - Utilizes aggregation functions for more complex data retrieval.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.x**
- **MongoDB**: Follow the official [MongoDB installation guide](https://docs.mongodb.com/manual/installation/) for your operating system.
- **pymongo**: Python driver for MongoDB. Install it via pip:
  ```bash
  pip install pymongo
  ```

### Cloning the Repository

To clone the repository, run the following commands in your terminal:

```bash
git clone https://github.com/harystyleseze/alx-backend-storage.git
cd alx-backend-storage/0x01-NoSQL
```

### Running the Scripts

Each task contains a script that can be executed independently. For example, to run the log stats script, use:

```bash
python3 3-log_stats.py
```

Make sure your MongoDB server is running and accessible.

### Sample Data

To test the scripts, you may need sample data. Ensure your MongoDB collection has relevant documents corresponding to each task's requirements.

## Expected Outputs

When you run the scripts, expect outputs in the console that indicate the success of the operations. Here are a few examples:

- **For log stats**:
  ```
  94778 logs
  Methods:
      method GET: 93842
      method POST: 229
      ...
  47415 status check
  ```

- **For top students**:
  ```
  [5a90776bd4321e1ec94fc408] John => 9.533333333333333
  [5a90776bd4321e1ec94fc409] Bob => 6.066666666666667
  ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- **ALX**: Thanks to ALX for providing the curriculum and resources for learning.
- **Community**: Special thanks to the community for support and collaboration.

## Contact

For any questions or further information, feel free to reach out to me on GitHub.

---

Thank you for checking out the ALX Backend Storage project! Happy coding!
```
