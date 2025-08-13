# **MongoDB-employee-queries**
### **Employee Data Generation and Analysis with MongoDB**

This project is a Python-based demonstration of data generation and database querying using MongoDB. It serves as a practical assignment to showcase skills in data handling, database connectivity, and querying using the PyMongo library.

---

### **Project Overview**

The core of this project is a Jupyter Notebook that performs the following tasks:

* **Data Generation**: Populates a MongoDB collection with a large dataset of 10,000 fake employee records using the popular **Faker** library. This simulated data includes fields such as names, departments, salaries, and performance ratings.
* **Database Connectivity**: Establishes a robust connection to a local MongoDB instance using the **PyMongo** driver.
* **Data Analysis Queries**: Executes a series of four specific PyMongo queries to perform data analysis, demonstrating filtering, projection, and aggregation techniques.

---

### **Queries Implemented**

The notebook contains Python functions to solve the following analytical problems:

* **High Performers Query**: Finds employees with a high performance rating and salary, returning only key details.
* **Experience-Based Filtering**: Identifies employees within a specific range of experience and salary, projecting essential contact information.
* **Salary Range Analysis**: Finds employees whose salaries fall outside a predefined range.
* **Recent Hires**: Uses the MongoDB aggregation pipeline to find recent hires with high performance and calculates their tenure in months.

Each function is commented to explain the purpose of the MongoDB operators used, such as `$gte`, `$lt`, `$or`, `$match`, and `$project`.

---

### **Setup and Running the Project**

To run this project on your local machine, follow these steps:

#### **Prerequisites:**
* Python 3.x
* MongoDB installed and running locally.

#### **1. Clone the Repository:**

### **2. Install dependencies:**

 * pip install pymongo faker jupyter
   
### **3. Run the Jupyter Notebook:**

 * Open the notebook file and run all cells in sequence. This will first generate the data and then execute all the queries.
